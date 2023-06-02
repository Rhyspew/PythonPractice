# Split the bill script

A basic script that splits the bill between a group of people.
Enter variables and values for number of people, tip value, and combined meal total.  
Format total each person plays using '{:.2f}'.format(value). Change value of '2f' based on the decimal numbers required. 

```py
#If the bill was $150.00, split between 5 people, with 12% tip. 

#Each person should pay (150.00 / 5) * 1.12 = 33.6
#Format the result to 2 decimal places = 33.60

#Write your code below this line 👇
bill_total = 150
people = 5
payment = bill_total / people
wtip = payment * 1.12
total = '{:.2f}'.format(wtip)
print(f"The total each person will have to pay is £{total}")
```
The outcome of the script will display:
The total each person will have to pay is £33.60

