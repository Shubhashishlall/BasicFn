import random
item_list = ["Rock","Paper","Scissor"]
 user_choice = input("Enter your choice =")

 comp_choice = random.choice(item_list)

 print(f"lets see who wins the game, user choice = {user_choice}, computer choice ={comp_choice}")


##if function to handle each and every condition which user gives - 


 if user_choice == comp_choice:
    print("Both chooses same so Match Tie ")

elif user_choice == "Rock":
    if comp_choice == "Scissor":
        print("Rock smashes scissor User wins")
    else:
        print("Scissor cuts paper Computer wins")


elif user_choice == "Scissor":
    if comp_choice == "Paper":
        print("Scissor cuts paper user wins ")
    else:
        print("Paper covers Rock computer wins")

elif user_choice == "Paper":
    if comp_choice == "Rock":
        print("Paper covers Rock user wins")
    else:
        print("Paper covers Rock computer wins")
else:
    print("Enjoy it failed")

"""Output - 

Scissor cuts paper user wins"""

     
