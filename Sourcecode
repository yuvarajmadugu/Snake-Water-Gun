'''
1 is for Snake
-1 is for Water 
0 is for Gun
'''

import random
computer = random.choice([1, 0, -1])

# Dictionary mappings
Dict = {"snake": 1, "water": -1, "gun": 0}
reverseDict = {1: "snake", -1: "water", 0: "gun"}

try:
    user_input = input("Enter Your Choice (snake, water, gun): ").lower()
    you = Dict[user_input]

    # Now you and computer both have numbers
    print(f"Your choice: {reverseDict[you]}\nComputer choice: {reverseDict[computer]}")

    # if(computer == you):
    #     print("It is a draw")
    # else:
    #     if(computer==-1 and you==1):
    #         print("You win")
    #     elif(computer==-1 and you==0):
    #         print("You lose")
    #     elif(computer==1 and you==0):
    #         print("You win")
    #     elif(computer==0 and you==-1):
    #         print("You win")
    #     elif(computer==1 and you==-1):
    #         print("You lose")
    #     elif(computer==0 and you==1):
    #         print("You lose")
    #     else:
    #         (print("Something went wrong"))

    if computer == you:
        print("It is a draw")
    else:
        if (computer == -1 and you == 1) or (computer == 1 and you == 0) or (computer == 0 and you == -1):
            print("You win")
        else:
            print("You lose")

except KeyError:
    print("Invalid input! Please enter only 'snake', 'water', or 'gun'. Try again.")
