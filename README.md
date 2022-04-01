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
r=str(result)
print("your result is: "+r)
#else:
#print("Inviad entry")
