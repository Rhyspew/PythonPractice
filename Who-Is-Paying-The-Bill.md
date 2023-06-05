# Who is paying the bill?

This script will determine who will be paying the bill. 
It uses random, len and lists to randomise the bill payer. 

```py
import random

# Split string method - Input names into a single string then split into a list.
names_string = input("Give me everybody's names, separated by a comma. ")
names = names_string.split(", ")

# Count the names in the list then choose a random number from the counted value. 
people = len(names)
buyer_number = random.randint(0, people)

# Print the name in the list
print(f"{names[buyer_number]} is going to buy the meal today!")
```
