rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''

#Write your code below this line 👇
import random

user_input = int(
    input(
        "what is your choice? type o for Rock, 1 for paper, 2 for scissors.\n")
)
computer_choice = random.randint(0, 2)
print(f"computer choice{computer_choice}")
if user_input == 0 and computer_choice == 2:
    print("you win")
elif computer_choice > user_input:
    print("computer wins")
elif user_input == computer_choice:
    print("Draw")
elif computer_choice == 0 and user_input == 2:
    print("User will loss")
elif user_input > computer_choice:
    print("user win")
else:
    print("invalid number or input")
