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

# Day 12 List fuction
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

