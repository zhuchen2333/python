# python
# guess number game

from random import randint
print("welcome to GUESS")
print("enter 'q' to quit")
i = 1
while i != 0 :
    a = randint(0,9)
    guess = input("plz enter num.0-9:")
    if guess != "q":
        if guess == a:
            print("yes!")
        else:
            print("wrong~\ntry again")
    else:
        break
print("See you next time.")
