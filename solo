from random import randint
 
#create a list of play options

t = ["Rock", "Paper", "Scissors"]
 
#assign a random play to the computer

computer = t[randint(0,2)]
 
#set player to False

player = False
 
while player == False:

#set player to True
    
    player = input("Rock, Paper, Scissors.. SHOOT!")
    
    
    if player == computer:
        print("Tie!")
    
    
    elif player == "Rock":
        if computer == "Paper":
            print("You lose!", computer, "covers", player)
        else:
            print("You win!", player, "beats", computer)
    
    
    elif player == "Paper":
        if computer == "Scissors":
            print("You lose!", computer, "cut", player)
        else:
            print("You win!", player, "covers", computer)
    
    
    elif player == "Scissors":
        if computer == "Rock":
            print("You lose...", computer, "beats", player)
        else:
            print("You win!", player, "cut", computer)
    
    
    else:
        print("Not a valid play, Try Again")
    
    
    #player was set to True, want it to be False so the loop continues
    
    
    player = False
    computer = t[randint(0,2)]

