# Treasure-Island-game
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.") 

left_o_right = input("You have two road options. Do you want to go left or right??")
if left_o_right == "right":
  swim_o_wait = input("you have come across a river. Do you want to swim or wait for a boat?")
  if swim_o_wait == "Wait":
    which_door = input("you have three doors in front of you to end the game. Do you wanna choose yellow, red, or bluew road or just choose jump off? ")
    if which_door == "Yellow":
      print("Congrats! You win")
    elif which_door == "Blue":
      print("OOps! You were eaten by beasts. Game over!")
    elif which_door == "Red":
      print("oops! You were burnt by fire. Game over!!")
    else:
      print("Sorry! Game over. try again")    
  else:
    print("oops! you' were attacked by a trout. Game over!")  
else:
  print("OOps! you fell into a hole. Game over.")  
