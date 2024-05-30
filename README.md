# Python_individual_first
First individual work in Python
```python
print("Welcome to the bank!")
balance = 0
while True:
  user = input("Please insert amount you want deposit or write 'exit':  ")
  if user == 'exit':
    print(f"Depositing is finished. You entered exit. Your total balance amount is {balance}.")
    break
  try:
    user= int(user)
    balance += user
  except:
    print("Please enter a valid amount!")
    continue
  print(f"Your new balance is {balance}")

  user_1 = input("Do you want to input another deposit? If yes, proceed with the amount, if no, please insert 'exit'.\n")
  if user_1 == 'exit':
    print(f"Depositing is finished. You entered exit. Your total balance amount is {balance}.")
    break
  try:
    user_1 = int(user_1)
    balance += user_1
  except:
    print("Please enter a valid amount")
    continue
    break

  print(f"Your new balance is {balance}.")
```
