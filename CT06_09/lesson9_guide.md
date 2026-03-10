# Lesson 9 - Flowcharts

# Recap 1: Dice Roll Simulator
Generate and print 3 random numbers between 1 and 6, followed
by an output of 'True' if all 3 numbers are either even or odd.

Example:
1st number: 6
2nd number: 4
3rd number: 6
All numbers are even/odd: True

1. Import the 'random' library
2. Create 3 variables to hold a random number that is between
   1 and 6, generated using 'random.randint()'
3. Using string concatenation, print the generated number for
   each of the 3 numbers
4. Using the '%' and '==' operator, check if each number is
   divisible by 2 (remainder = 0)
5. Using multiple '==' operators, a new variable 'all_even_odd'
   should be assigned 'True' if all 3 numbers are either all
   even or all odd numbers.
6. Print if "All numbers are even/odd" is 'True' or 'False'

--------------------------------------------------------------

# Task 1: Flowchart for Library Reminder
Draw out the flowchart (on draw.io) of a program
to remind borrowers to return their books

1. Ask the user to input the number of days a book has been
   borrowed
2. If the book has been borrowed for more than 25 days:
    print "Remember to return your book!"

--------------------------------------------------------------

# Task 2: Converting Library Reminder flowchart
#         into code
Translate the flowchart that you have drawn (shown on screen)
into Python code.

1. Ask the user to input the number of days a book has been
   borrowed
2. If the book has been borrowed for more than 25 days:
    print "Remember to return your book!"

Hint: remember to typecast your variables!

--------------------------------------------------------------

# Task 4: Apple Shop
**Task 4a**:
Draw out the flowchart (on draw.io) of a program for
the user to buy apples and calculate the price.

Each apple costs $1

1. Ask the user how many apples they want to buy
2. If the user wants to buy more than 10 apples:
   print "You will get a 10% discount for buying that many
   apples!"
4. Print the price of the purchase

**Task 4b**:
Translate the flowchart that you have drawn (shown on screen)
into Python code.

--------------------------------------------------------------

# Task 5: Fruits Shop
**Task 5a**:
Draw out the flowchart (on a draw.io) of a program for
the fruit shop, "FruitiFresh". FruitiFresh sells 2 fruits,
Apple & Orange with the following pricing scheme:

Apple:
1 Apple = 60 cents
If buy more than 5 apples, get 10% discount for all apples

Orange:
1 Orange = 90 cents
If buy more than 5 oranges, get 10% discount for all oranges

You want to create a program that:
1. Asks the user for the number of apples and oranges they
   want to buy.
2. Print total price of the fruits

**Task 5b**:
Translate the flowchart that you have drawn (shown on screen)
into Python code.