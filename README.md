# Python-Programming-for-Beginners

- https://www.youtube.com/watch?v=eWRfhZUzrAc&t=921s
- https://raw.githubusercontent.com/RodrigoMvs123/Python-Programming-for-Beginners/main/README.md
- https://github.com/RodrigoMvs123/Python-Programming-for-Beginners/blame/main/README.md
- https://www.python.org/downloads/
- https://replit.com/

```python
import random
def get_choises():
  options = ["rock", "paper", "scissors"]
  player_choise = input ("Enter a choise (rock,paper,scissors): ")
  computer_choise = ramdom.choise(options)
  choises = {"player": player_choise, "computer": computer_choise}
  return choises
def check_win(player,computer):
  print(f"You chose {player}, computer chose {computer}")
  if player == computer: 
    return "It is a tie!" 
  elif player == "rock" :
    if computer == "scissors":
      return "Rock smashes scissors! You win!"
  else:
    return "Paper covers rock! You lose."  
  elif player == "paper":
    if computer == "rock":
    return "Paper covers rock! Your win!"
  else:
    return "Scissors cuts paper! You lose."
  elif player == "scissors":
    if computer == "paper":
    return "Scissors cuts paper! Your win!"
  else:
    return "Rock smashes scissors! You lose."
choises = get_choises()
result = check_win(choises["player"], choises["computer"])
print(result)
```
