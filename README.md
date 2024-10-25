# DiceRolling
#make a Loop(Infinate)
    # Ask: Roll the Dice
    #if user enter y
    #then generate 2 random number and print them
    #if user enter n
    #then print "No roll"
    # if user enter any thing else 
    #then print "Invalid input"
import random

while True:
    choice= input("Roll The Dice? (y/n):").lower()
    if choice=="y":
        dice1= random.randint(1,6)
        dice2= random.randint(1,6)
        print("Dice 1:",dice1)
        print("Dice 2:",dice2)
    elif choice=="n":
        print("Thank You For playing")
        break
    else:
        print("Invalid Input")

