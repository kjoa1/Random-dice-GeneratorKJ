# Random-dice-GeneratorKJ
import random

#This rolls the dice
x = random.randint(1,6)
y = random.randint(1,6)

#this runs the game
while True:
    run = input("Roll the dice? (y/n): ")
    if run == 'y':
        print(x, y)
    elif run == 'n':
        print("Thanks for playing!")
        break
    else:
        print("Invalid choice!")
