import random

def hand_cricket(player_choice):
    computer_choice = random.randint(1, 6)
    print("Computer's choice:", computer_choice)
    if player_choice == computer_choice:
        return "Out! You scored " + str(player_choice)
    else:
        return "You scored " + str(player_choice)

# Example usage
player_choice = int(input("Enter your choice (1-6): "))
result = hand_cricket(player_choice)
print(result)
