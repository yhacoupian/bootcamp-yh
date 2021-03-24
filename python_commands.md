## User Input
```python
run = input("To run again enter 'y'")
if run: 
	print("RUN")
```

## Functions
```python
# Create a function to calculate percentage 
def percentage(part, whole):
  return 100 * float(part)/float(whole)
```

## Conditional Statement (If-Elif-Else)
```python
# If statement
# The else keyword catches anything which isn't caught by the preceding conditions.
a = 200
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")

# Demonstrate conditional statement
if True:
    # Do something
else:
    # Do something else

# Demonstrate conditional with print statement
is_raining = True
if is_raining:
    print("Bring an umbrella!")
else:
    print("Leave the umbrella at home!")

# Demonstrate equality
x = 5
if x == 1:
    print("x is equal to 1")

# Demonstrate using variables to store conditions
x = 5
y = 10
if x == y:
    print("x is equal to y")

# Check inequality
y = 9
if y != 1:
    print("y is not equal to 1")

# Declare variables and values for evaluation
x = 1
y = 10

# Checks if one value is equal to another
if x == 1:
    print("x is equal to 1")

# Checks if one value is NOT equal to another
if y != 1:
    print("y is not equal to 1")

# Checks if one value is less than another
if x < y:
    print("x is less than y")

# Checks if one value is greater than another
if y > x:
    print("y is greater than x")

# Checks if a value is less than or equal to another
if x >= 1:
    print("x is greater than or equal to 1")

# Checks for two conditions to be met using "and"
if x == 1 and y == 10:
    print("Both values returned True")

# Checks for two conditions to be met using and
if x == 1 and y < 10:
    print("Both values returned True")

# Checks if either of two conditions is met
if x < 45 or y < 5:
    print("One or more of the statements were True")

# Nested if statements
if x < 10:
    if y < 5:
        print("x is less than 10 and y is less than 5")
    elif y == 5:
        print("x is less than 10 and y is equal to 5")
    else:
        print("x is less than 10 and y is greater than 5")

# Nested if statements with insurance premium predictor
accident = True
at_fault = False
accident_forgiveness = True
elite_status = True

increase_insurance_premium = True

print("Insurance premium will increase. True or False?")

# Nested Conditional Statements
if accident:
    if at_fault and accident_forgiveness:
        increase_insurance_premium = False
    elif at_fault and not accident_forgiveness and not elite_status:
        increase_insurance_premium = True
    else:
        increase_insurance_premium = False
elif not accident and elite_status:
    increase_insurance_premium = False
else:
    increase_insurance_premium = True

print(f"Prediction: {increase_insurance_premium}")

```

## Variables 
```python
# Creates a variable with a string "Frankfurter"
title = "Frankfurter"
years = 23
hourly_wage = 65.40
expert_status = True

# Print the variables
print(title)
print(years)
print(hourly_wage)
print(expert_status)

# Prints the data type of each declared variable
print("The data type of variable title is", type(title))
print("The data type of variable years is", type(years))
print("The data type of variable hourly_wage is", type(hourly_wage))
print("The data type of variable expert_status is", type(expert_status))

# Using variable names in calculations
total_miles = 257
gallons_gas = 7.2
miles_per_gallon = total_miles / gallons_gas

# Updating variables using assignment
miles = 48
kilometers = miles / 0.621371

# Substituting/formatting variable
message = f"The total kilometers driven was: {kilometers}"
print(message)

# Variable naming conventions
# Bad Example
mpg = 24
# Better Example
miles_per_gallon = 24

```

## Loops
```python
# For loops
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
  if x == "banana":
    break
	
# Loop through a range of numbers (0 through 4)
for x in range(5):
    print(x)

print("-----------------------------------------")

# Loop through a range of numbers (2 through 6 - yes 6! Up to, but not including, 7)
for x in range(2, 7):
    print(x)

print("----------------------------------------")

# Iterate through letters in a string
word = "Peace"
for letters in word:
    print(letters)

print("----------------------------------------")

# Loop while a condition is being met
run = "y"

while run == "y":
    print("Hi!")
    run = input("To run again. Enter 'y'")

```