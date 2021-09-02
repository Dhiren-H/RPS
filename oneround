from random import randint
weapons = ["rock", "paper", "scissors"]
message = {
  "draw": "Boring, it's a draw...",
  "won": "Congrats! You won!",
  "lost": "Lol, you lost"
}

def decide_winner(user_choice, computer_choice):
  print "You chose: %s" % user_choice
  print "I chose: %s" % computer_choice
  if user_choice == computer_choice:
    print message["draw"]
  elif user_choice == weapons[0] and computer_choice == weapons[2]:
    print message["won"]
  elif user_choice == weapons[1] and computer_choice == weapons[0]:
    print message["won"]
  elif user_choice == weapons[2] and computer_choice == weapons [1]:
    print message["won"]
  elif user_choice not in weapons:
    print "That's not one of the options mate, you'll have to play again"
  else:
    print message["lost"]

def play_game():
  user_choice = raw_input("""Rock, Paper or Scissors?
  """)
  user_choice = user_choice.lower()
  computer_choice = weapons[randint(0,2)]
  decide_winner(user_choice, computer_choice)

play_game()
