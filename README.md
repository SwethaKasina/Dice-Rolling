# Dice-Rolling
A simple Python project that simulates rolling a dice using the random module. It generates numbers between 1 and 6, allowing users to roll once or multiple times until they choose to stop. This beginner-friendly program is great for learning the basics of Python, randomness, and user input handling.
'''DICE Rolling'''
import random
print("Dice Rolling")
while True:
    roll=input("Roll Dice? (Y/N):")
    if roll.lower()=="y":
        print("You Got:",random.randint(1,6))
    else:
        print("Game Over!")
        break

