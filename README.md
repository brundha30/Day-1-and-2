# Day-1-and-2
# Statement and Input function
#a=float(input("Enter the number1:")
b=float(input("Enter the number2:")
c=a+b
print(c)
#x="red"
print("Apple is"+" "+x)
# Functions
print(pow(3,2)
print(abs(-67)

name1,name2,name3=input("Enter 3 Names:").split()
print("Name1:",name1)
print("Name2:",name2)
print("Name3:",name3)

a=(input("How are you?:"))
print(a.strip())
print(len(a))
print(a.lower())
print(a.upper())
print(a.replace("H","F"))
print(a.split())
print(a.title())
print(a.count('e'))
print(a.endswith('er'))
print("Is AlphaNumeric:",a.isalnum())
print("Is Alpha:",a.isalpha())


a="Palm \nTree,\nCoconut \ntree"
print(a.splitlines())

a="    NewYork    "
print(len(a.lstrip()))
print(len(a.rstrip()))
# 
import math
print(math.floor(32.9))
print(math.ceil(32.9))
print(math.sqrt(5))

#sentence = input("Sentence: ")
screen_width = 80
text_width = len(sentence)
box_width = text_width + 6
left_margin = (screen_width - box_width) // 2

print (' ' * left_margin + '+' + '-' * (box_width-2) + '+')
print (' ' * left_margin + '| ' + ' ' * text_width + "  " ' |')
print (' ' * left_margin + '| ' + sentence  + "  " ' |')
print (' ' * left_margin + '| ' + ' ' * text_width + "  " ' |')
print (' ' * left_margin + '+' + '-' * (box_width-2) + '+')

# circumference of a circle
a=float(input("Enter the value of A:"))
r=int(input("Enter the value of B:"))
c=2*a*r
print(c)

# slicing
a=[1,2,3,4]
print(a[1])
print(a[-1])
print(a[0:3])
print(a[2:])
print(a[:3])
print(a[:])

a=[10,25,35,45,25,4,25]
print(a.count(25))
print(a.index(25))
print(len(a))
print(max(a))
print(min(a))

#working with string
format = "Hello, %s."
values = ('world')
print (format % values)

names=["yellow"]
print(names)
names.append("blue")
names.append("orange")
names.append("green")
name1=["black"]
names.extend(name1)

# Dictionary
user={
    "name":"Kala",
    "age":30,
    }
for x in user.values():
    print(x)
for x in user.keys():
    print(x)
user.pop("age")
print(user)
user.clear()
print(user)    

# if
# leap year
year=int(input("Enter the year:"))
if year%4==0:
    print(year, "is","Leap year")
else:
    print(year, "is","not a leap year")


number=int(input("Enter the number:"))
if number>0:
    print(number,"is","positive")
    if number%2==0:
        print(number,"is even")
    elif number<0:
        print(number,"is negative")
    else:
        print(number,"is odd")
        print(number,"is not negative")
elif number==0:
    print(number,"is neutral")
else:
    print(number,"is","not positive")

# for loop
#adding even numbers
a=int(input("Enter the starting value:"))
b=int(input("Enter the ending value:"))
c=0
for i in range(a,b+1,1):
  if i%2==0:
     c=c+i
print(c)

#while loop(tables)
n=int(input("Enter the number:"))
i=1
while i<=10:
    print(n,"*",i,"=",n*i)
    i+=1
    
# function
def my_function(food):
 for x in food:
    print(x)
fruits=["apple","banana","cherry"]
my_function(fruits)

def function(country = "Norway"):
    print("I am from" + country)
function(" Sweden")
function(" India")
function( )
function(" Brazil")





