# python
This is a python project

import random  # For random number

num = random.randint(1, 10)  # Pick number
tries = 0

while True:
    guess = int(input("Guess 1-10: "))
    tries += 1
    if guess == num:
        print(f"Correct! {tries} tries.")
        break
    print("Too low!" if guess < num else "Too high!")
