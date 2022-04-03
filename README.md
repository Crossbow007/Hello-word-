# Hello-word-
print('This is my first code')

# DAY 9 LEARN STRINGS
print("Kevin Gao")
# switch line, add a backslash mark"\"
print("Kevin\n Gao")
# set string as a viable value
phrase = Kevin
print(phrase+ "Gao is cool")
print(phrase.lower())
print(phrase.isupper())
print(phrase.upper().isupper())
# count letter length
phrase = Kevin Gao
print(len.phrase)
# get the certain letter in strings by count number, start from 0
phrase = Kevin Gao
print(phrase[0])
print(phrase.index(0))
# replace
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
