# number-guesser
a simple game named " number guesser" made using basics of python
import random

target_number = random.randint(1, 100)

print("Welcome to the Number Guesser Game!")
print("Try to guess the number I'm thinking of!")

while True:
    guess = int(input("Enter your guess: "))
    if guess == target_number:
        print("Congratulations! You guessed the number!")
        break
    elif guess < target_number:
        print("low! Try again.")
    else:
        print("high! Try again.")


    
