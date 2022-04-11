# 100 DAYS CODE
# Day 1 print
print('This is my first code')
# Day 2 print input
name = input("what is your name?\n")
print("Hi " + name)
# Day 3 Tip Calculator
print("welcome to tip calculator!")
total_bill = input("what was the total bill? $: ")
tip_percentage = input("how much the tip would you like to give? 10, 12, or 15? ")
total_people = input("how many people to split the bill? ")
result = ((float(total_bill)+float(total_bill)*int(tip_percentage)/100)/int(total_people))
print("Each person should pay:  "+ str(round(result,3)))
# Day 4 print
# Day 5 print
# Day 6 print
# Day 7 print
# Day 8 print
# DAY 9 LEARN STRINGS
print("Kevin Gao")
  switch line, add a backslash mark"\"
print("Kevin\n Gao")
  set string as a viable value
phrase = Kevin
print(phrase+ "Gao is cool")
print(phrase.lower())
print(phrase.isupper())
print(phrase.upper().isupper())
   count letter length
phrase = Kevin Gao
print(len.phrase)
  get the certain letter in strings by count number, start from 0
phrase = Kevin Gao
print(phrase[0])
print(phrase.index(0))
   replace
phrase = Kevin Gao
print(phrase.replace("Kevin", "Allen"))

# DAY 10 CALCULATOR
print("CALCULATOR")
print("1. ADD")
print("2. SUBTRCT")
print("3. Multiply")
print("4. DIVIDE")
num1 = input ("please input your first number: ")
print("please choose what type of fuction you want:1. ADD,2. SUBTRCT,3. Multiply or 4. DIVIDE:")
math = input()
num2 = input ("please input your second number: ")
if math == "1":
  result = (float(num1)+float(num2))  
elif math == "2":
  result = (float(num1)-float(num2))
elif math == "3":
   result = (float(num1)*float(num2))
elif math == "4":
    result = (float(num1)/float(num2))
else:
    print("invalid entry")
print("your result is: "+ str(result))


## DAY 11 NUMBERS
print(3+4)
print(3/4)
print(3*(4+5))
print(1 % 4)
num_hello = -5
print(num_hello)
print(str(num_hello))
print(str(num_hello)+" is my favorate number")
print(abs(num_hello))
print(pow(3,2))
print(max(2,3,6,8,10))
print(min(2,3,6,8,10))
print(round(2.3))
from math import *
print(floor(3.7))
print(ceil(3.9))
print(sqrt(36))

# Day 12 List fuction and 
lucky_number = [3,6,7,9,15]
friends = ["Kevin","Allen","Bobo","Lucy","Ergouzi"]
print(lucky_number)
print(friends)
 #extend
lucky_number = [3,6,7,9,15]
friends = ["Kevin","Allen","Bobo","Lucy","Ergouzi"]
friends.extend(lucky_number)
print(friends)
 #append
lucky_number = [3,6,7,9,15]
friends = ["Kevin","Allen","Bobo","Lucy","Ergouzi"]
friends.append("Shara")
print(friends)
 #insert
lucky_number = [3,6,7,9,15]
friends = ["Kevin","Allen","Bobo","Lucy","Ergouzi"]
friends.insert(1,"Shara")
print(friends)
 #remove
lucky_number = [3,6,7,9,15]
friends = ["Kevin","Allen","Bobo","Lucy","Ergouzi","Shara"]
friends.remove("Shara")
print(friends)
 #clear
lucky_number = [3,6,7,9,15]
friends = ["Kevin","Allen","Bobo","Lucy","Ergouzi","Shara"]
friends.clear()
print(friends)
#pop
lucky_number = [3,6,7,9,15]
friends = ["Kevin","Allen","Bobo","Lucy","Ergouzi","Shara"]
friends.pop(-1)
print(friends)
#index
lucky_number = [3,6,7,9,15]
friends = ["Kevin","Allen","Bobo","Lucy","Ergouzi","Shara"]
print(friends.index("Allen"))
#count
lucky_number = [3,6,7,9,15]
friends = ["Kevin","Allen","Bobo","Lucy","Ergouzi","Shara","Allen","allen"]
print(friends.count("Allen"))
#sort
lucky_number = [18,3,6,7,9,15]
friends = ["Kevin","Allen","Bobo","Lucy","Ergouzi","Shara","Allen","allen"]
friends.sort()
lucky_number.sort()
print(friends)
print(lucky_number)
#reversed
lucky_number = [18,3,6,7,9,15]
friends = ["Kevin","Allen","Bobo","Lucy","Ergouzi","Shara","Allen","allen"]
friends.reverse()
lucky_number.reverse()
print(friends)
print(lucky_number)
#copy
lucky_number = [18,3,6,7,9,15]
friends = ["Kevin","Allen","Bobo","Lucy","Ergouzi","Shara","Allen","allen","copy"]
friends2=friends.copy()
print(friends)
learn from https://www.youtube.com/watch?v=rfscVS0vtbw&t=4739s
#TUPLES
co = (3,6,34,32,21)
print(co[1])# 1 is a index unmber

# Day 13 DEF function
Questions
 QUESTION 1. Write a function called hello that prints Hello World!
QUESTION 2. Write a function called addition that accepts two parameters num1, and, num2. Print the addition of the two numbers. 
QUESTION 3. Write a function called MinutesToSeconds that converts minutes into seconds. The parameter is an integer called minutes.  Print the seconds.
4. In this challenge, a farmer is asking you to tell him how many legs can be counted among all his animals. The farmer breeds three species:
 chickens = 2 legs
 cows = 4 legs
 pigs = 4 legs
The farmer has counted his animals and he gives you a subtotal for each species. You have to implement a function that prints the total number of legs of all the animals.

 Examples:
 animals(2, 3, 5) ➞ 36
animals(1, 2, 3) ➞ 22
 animals(5, 2, 8) ➞ 50

Hint: there are 3 parameters —> chickens, cows, pigs.


#Question 1
def Hello(hi):
    print( hi )
Hello("Hello, word!")

#Question 2
def addtion(num1,num2):
   print(float(num1)+float(num2))
addtion(3,5)

#Question 3
def MinutesToSeconds(minutes):
   seconds = float(minutes)*60
   print(float(seconds))
MinutesToSeconds(3)

#Question 4
def animals(a,b,c):
    total_legs = (int(a)*2 +int(b)*4+int(c)*4)
    print("Hi, Allen, this farm hast total "+ str(total_legs)+" legs.")
chicken = input("how many chickens does farm have: ")
pig = input("how many pig does farm have: ")
cow = input("how many cow does farm have: ")
animals(int(chicken),int(pig),int(cow))

#def math
def cube(num):
  return  num * num * num

print(float(cube(3.2)))

# DAY 14 IF STATEMENT
is_male = False
is_tall = False

if is_male and is_tall:
 print("you are a tall male ")
elif is_male and not(is_tall):
 print ("you are a sort male")
elif not(is_male) and is_tall:
 print("you are not male, but tall")
else:
  print(" you are either male and tall")
  
# Day 15 Another calculator
num1 = float(input("Enter the first number: "))
op = input("Enter the operator : ")
num2 = float(input("Enter the second number: "))
if op == "+" :
  print (num1+num2)
elif op == "-":
  print (num1-num2)
elif op == "*":
  print (num1*num2)
elif op == "/":
  print (num1/num2)
else:
  print("INVALID NUMBER")

#Day 16 WHILE LOOP
i = 1
while i <=10:
  print(i)
  i = i + 1
print("done with loop")

#17 GUESS NAME
secret_name = "gao pengbo"
guess = ""
guess_count=0
guess_limit=3
out_of_guess=False
while guess != secret_name and not(out_of_guess):
  if guess_count < guess_limit:
      guess = input("Entre a guess: ")
      guess_count = guess_count + 1
  else:
    out_of_guess = True
if out_of_guess:
  print("you lose the game!")
else:
  print("you WIN!")
  
# DAY 18 QUESTION 1. Create a function called makesTen that has 2 parameters, a and b. Print True if one of them is 10 or if their sum is 10.
  Examples:
  makesTen(9, 10) ➞ True
  makesTen(9, 9) ➞ False
  makesTen(1, 9) ➞ True
a=input("please entry the first number: ")
b=input("please entry the second number: ")
def makesten(a,b):
  if a + b < 10:
    check = False
    print(check)
  elif a == 10 or b == 10 or a + b == 10:
    check = True
    print(check)
print(makesten(float(a),float(b)))
# DAY 19 DEF FUNCTION
. You are counting points for a basketball game, 
 given the amount of 2-pointers scored and 3-pointers scored, 
#find the final points for the team and return that value.
EX: 
 points(1, 1) ➞ 5
 points(7, 5) ➞ 29
points(38, 8) ➞ 100

two_pointers = input("input 2 pointers: ")
three_pointers = input("input 3 pointers: ")
def final_points(two_pointers,three_pointers):
    result = (two_pointers)*2 + (three_pointers)*3

    print(result)

final_points(int(two_pointers),int(three_pointers))
#final_points(7,5)
#final_points(38,8)

# QUESTION 4. Create a function that prints True if a string is empty and False otherwise.

#Examples:
#isEmpty("") ➞ true
#isEmpty(" ") ➞ false
#isEmpty("a") ➞ false
isEmpty= input()
length = len(isEmpty)
if length == 0:
  print("True")
else:
  print("Flase")
  
  # QUESTION 5. Write a function called, watchMovie, that checks whether a person can watch an 13+ rated movie. One of the following two conditions is required for admittance:

#The person is at least 13 years old.
#They have parental supervision.
#The function accepts two parameters, age and isSupervised. Print either True or False
a = input("Please input your age: ")
b = input("Do you have panrental supervisor? Y or N: ")
def watchMovie(a,b):
   if int(a) >= 13 and b =="Y" :
     print("True")
   else:
     print("Flase")
     
watchMovie(a,b)

# QUESTION 6. Given a string, print True if its length is even or False if the length is odd.
# Examples:
# oddOrEven("apples") ➞ true
# The word "apples" has 6 characters.
# 6 is an even number, so the program outputs true.

# oddOrEven("pears") ➞ false
# "pears" has 5 letters, and 5 is odd.
# Therefore the program outputs false.

# oddOrEven("cherry") ➞ true
import math
a = input ("please input your letter: ")
b=len(a)

if b%2 == 0:
  #print("True")
  print("This letter has " + str(b)+ " letters, it is a Even number!")
elif b%2 == 1:
   print("This letter has " + str(b)+ " letters, it is a Odd number!")
