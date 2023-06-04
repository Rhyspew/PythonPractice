#Love Calculator

This project is to create a love calculator.
It will find how many times the letters that make up the words "true love" occur in the first names of two people. 
The result will output a response. 

```py
print("Welcome to the Love Calculator!")
name1 = input("What is your name? \n")
name2 = input("What is their name? \n")

#Combine names and convert to lower case
combined_string = name1 + name2
lower_case_string = combined_string.lower()

#Count individual letters 
t = lower_case_string.count("t")
r = lower_case_string.count("r")
u = lower_case_string.count("u")
e = lower_case_string.count("e")

true = t + r + u + e

l = lower_case_string.count("l")
o = lower_case_string.count("o")
v = lower_case_string.count("v")
e = lower_case_string.count("e")

love = l + o + v + e

#Combine scores from each word and convert to integer for calculations
comb_score = str(true) + str(love) 
love_score = int(comb_score)

if (love_score < 10) or (love_score > 90):
    print(f"Your score is **{love_score}**, you go together like coke and mentos.")
elif (love_score > 40) and (love_score < 50):
    print(f"Your score is **{love_score}**, you are alright together.")
else:
    print(f"Your score is **{love_score}**.")
```

Try it yourself!
