# Heads or Tails?

This is an easy script that incorporates random number generation to simulate and decide the winner of a coin toss.

```py
# Use the random module via import to generate a random value. 
import random

# Logic and if rule to decide between heads and tails.
side = random.randint(0, 1)

if side == 1:
    coin_flip = "Heads"
else:
    coin_flip = "Tails"

# Remove comment below to view winning side before user decides:
# print(coin_flip)

# User input
choice = input("What side of the coin will land face up, Heads or Tails?")

# Script output
if choice == coin_flip:
    print("You are correct!")
else:
    print("You are wrong")
```    
