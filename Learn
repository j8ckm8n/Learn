#Simple rules in python are that you should always use a colon at the end of a statement and use indentation to show the code block
#You shoud always use lowercase on things like while in a while loop and use uppercase on things like True or False

#Importing Modules
import random #This will import an external library called random which you can download in terminal this will allow u to use stuff like random.choice and random.range to generate a random number from a list froma  list for example


#Data types

#int
a = 5 #5 is the integer
a = 10 #10 is also an integer

#float
a = 5.5 #5.5 is the float as it has a decimal point
b = 5.0 #5.0 is also a float

#bool
True #This is a boolean considered as 1
False #This is also a boolean considered as 0

#string
"Hello World" #This is a string
'Hello World'#This is also a string

#Output and Printing
print("Hello World") #This will print Hello World. Needs strings unless its a variable or a float!
print(5, "Hello World") #This will print 5 Hello World. Needs strings unless its a variable or a float!
print("Hello World", end='\n') #This will print Hello World then goes to the next line.
print("Hello World", end='') #This will print Hello World then stays on the same line.  

#Variables
Name = "jack" #Capitals are allowed in variables
a = 5 #This is a variable
text = "Hello World" #This is also a variable
numbers = [1, 2, 3, 4, 5] #This is a list of numbers stored in a variable
print(numbers, a, text) #This will print all our variables as they are defined above
hello_world = "Hello World" #This is a variable with an underscore any other character is not allowed including spaces
#5hello = 5 This is not allowed as it starts with a number
hello5 = 5 #This is allowed as it starts with a letter

#Input
input("test: ") or input('name: ') #This will ask the user to type something or enter their name and will store the input in a variable
name = input("name: ") #This will ask the user to enter their name and store it in the variable name
print(name) #This will print the name that was stored in the variable
age = input("age: ") #Will ask for persons age and store it
print("Your name is ", name, "and you are", age, "years old!") #This will take all data and create a sentence that describes states your name and age

#Maths in python
x = 5 #Variable
y = 5.0 #Variable
result = x * y or x + y or x - y or x / y#Sets a variable that means the two variables above x by each other or the sum of the above or minus or division etc etc
print(result) #This prints out the result
test = int(x * y) #This switches the result to an int(integer) if u want
print(test)
x ** y #X the power of Y
#BODMAS also works in python
number = input("Enter a number: ") #Simple input
#print(number - 5) This will not work as the python sees number as a string and doesnt know what to do with the - 5
print(int(number) - 5) #This will work as it converts it from a string to an integer or u could use float

#String Methods
hello = 'hello'.upper() #Writes out hello in upper case which is a method called "only on strings" u can also use .lower() or .capitalize() or use .count(w) which will count how many w's are in the string
print(type(hello.upper())) #This will print its data type. This will respond with 'class str' because it is a string and it will also put it in uppercase if we didnt use type

#Conditional Operators
x = 'hello'.lower()
y = 5
print(x * y) #This will repeat the string 'hello' by 3 time eg: hellohellohello
a = 'hello'
b = 'hello'
print(a + b) #Simply adds them together "hellohello"

#Conditions
print(y != x) #Checks if its equal or not equal and will return in a boolean values eg. True or False
print(y == x) #Same thing applys and if x was set to heLLo with uppercase it would return in false because they are not even
print('a' > 'z') #every character has a ordinal code so for example this will be true as a = 97 and z = 90. If we replace z with b then we will get false as b = 98
print(5.5 > 5) #True

#Chained Conditionals
result1 = x == y 
result2 = y + 3 == x
result3 = y - 2 == x
result4 = result1 or result2 # these will al print out true or false and the "or" in line 78 means that it'll check both and if even 1 is true it'll print true
print(result4)
result5 = result2 or not result3 #This not will flip the value from false to true
print(not True) #This will print false
print(result1 and result2) #simple joining

#If and elif and else statements
y = "hi" #Sets the variable

if y == "hi": #If statement has to be closed with a colon and has to use ==
    print("nice") #Prints if the if statement is true
else: #if the variable = something else then...
    print("cool") #print

x = 1

if x == 1: #Pretty shit if statement but u get the gist
    print("x = 1")
elif x != 1: #State another condition
    print("x doesn't = 1")
else: #Anything else but 1
    print(" i dont know what x =")


#Collections
x = [1, 2, 3] #This is a list (holds many elements and can store alot of datat) as it holds three integers but this would also work
y = [1, "hello", True]

print(x) #Will print out the list but not what its used for
print(len(y)) #Len means Length so if I had a txt file with an essay in it I could count the chars (characters) by using len
y.append("hello")# Append will add stuff to the list so now y should include hello
x.extend([5, 5, 5]) #extends list adding on 5 5 5
print(x.pop(0)) #pop will remove one of the elements in the list and the 0 indicates which 1 because in a list you count starting from 0 so in the list x there is 0 1 and 2 as u count from 0 if that makes sense

#Tuples
x = (5,5,5) #Just like a list but cannot be change with pop or append etc
print(x[0]) #This will work the same as a list but tuples are used for data that shouldnt be changed

#for loops
for x in range(2): #This will loop through the code twice which is similar but different to a while loop which will come later
    print("Hello World") #This will print Hello World twice
for i in range(10): #This will loop the code 10 times. the "i" is a variable called the iterator. The in means in the range of 10 and range is a function that generates a list of numbers
    print(i) #This will print the numbers 0 - 9

for i in range(1, 10, -4): #This will print 1, 5, 9 as its using the stop start and step method which is quite self explanatory
    print(i) #This will print the numbers 1, 5, 9

for i in [1, 2, 3, 4, 5]: #This will loop through the list of numbers
    print(i) #This will print the numbers 1, 2, 3, 4, 5

x = [1, 2, 3] #list
for i, element in enumerate(x): #This will loop through the list and print the index and the element. Enumerate is a function that returns the index and the element
    print(i, element) #This will print the index and the element in the list

#While Loops
x = 5
while x == 5: #This will loop through the code until x is not equal to 5
    print("Hello World") #This will print Hello World until x is not equal to 5
    break #This will break the loop

i = 0
while i < 3:
    int(input("Enter a number: "))
    i += 1 #This will loop through the code 3 times and will ask the user to enter. The i += 1 is the same as i = i + 1

#Slice Operator

x = [0, 1, 2, 3, 4]
sliced = x[0:4:2] #This will slice the list from 0 to 4 and will skip every 2nd element. This is using the start stop step method again
reverse = x[::-1] #This will reverse the list

print(sliced) #This will print 0 and 2.This will also work with tuples so replace x with a tuple

#Functions
def function(): #This is a function and inside the brackets is where you would put the parameters which are not needed as of now
    print("Hello World") #This will print Hello World

function() #This will call the function so basically run the code inside the function and thats pretty much it for functions you can put anything in it and then run at the end pretty self explanatory once you get used to them

def function2(a, b): #This uses parameters which can be any letter or something like param1 and param2 but numbers can not go before a letter
    print(a + b) #This will print the sum of a and b

function2(100, 100) #This will call the function and print the sum of 100 and 100 which are our two parameters

def function3(a, b): #This is a function with parameters
    print("Hello World", a / b, a * b) #This will print Hello World and the division and multiplication of a and b
    return a + b #The return is quite self explanatory it will return the sum of a and b
print(function3(5, 5))


#Sets
x = set()
s = {5,5,5,5,5,5,5,5,5} #This is a set and it will only store unique values so if you put 5 in it 5 times it will only store it once
s2 = {5, 6, 7, 8} #Another set
s.remove(5) #This will remove 5 from the set
s.add(5) #This will add 5 to the set
print(s) #This will print the set
print(5 in s) #This will check to see if 5 is in s and return with a boolean value
print(s.union(s2)) #This will combine the two sets and remove any duplicates
print(s.intersection(s2)) #This will return the values that are in both sets. U can also use .difference() which will return the values that are not in both sets

#Dictionaries
x = {"name": "jack"} #sets different meanings to strings
print(x["name"]) #This will print the value of the key name in the dictionary
x["name"] = "gabriel" #This will change the value of the key name to gabriel
print("name" in x) #This will check to see if the key name is in the dictionary and return a boolean value

#Comprehensions
x = [x for x in range(10)] #List using a for loop
print(x) #This will print the list 0,1,2,3 etc etc
x = [x + 2 for x in range(10)]#This will add 2 to each element in the list
print(x) #This will print the list 2,3,4,5 etc etc
x  = [[x for x in range(5)]for x in range(5)] #This will create a 2d list
print(x) #This will print the 2d list which will count 5 then times that by 5 in simple terms


#Unpack Operator & *args and **kwargs
def func(x):
    def func2(): #This is a nested function ( a function inside a function)
        print(x)

    return func2
 
func(5)() #This will assign the function to x


#Now we will use "*args" and "**kwargs" args is short for arguments and kwargs is short for keyword arguments
def func(*args, **kwargs): #This will allow us to pass in any number of arguments and any number of keyword arguments
    pass
x = [1, 2, 3] 
print(*x) #This will unpack the list and print the elements separated by a space and no square brackets
print(x) #This will print the list with the square brackets

#**kwargs are used in dictionaries and args are used in lists or tuples

#Scope and Global
x = "jack"  #This is a global variable

def func(name):
    #global x This will make x a global variable
    x = name
    print(name) 
    #func('gabriel') This will print gabriel so many times as the function is calling itself

func(x) #This will print jack

#Raise Exception
#raise Exception("cool") #This wil print exception: cool
#raise FileExistsError("cool") #This will print FileExistsError: cool

#Handling Exceptions
try:
    x = 5 / 0
except ZeroDivisionError: #This will catch the error and print the error
    print("You can't divide by zero")

#Lambdas
x = lambda x: x + 5 
print(x(2))

x = lambda x, y: x + y
print(x(2, 32)) 

#Map Filter
x = [1,2,1,1,12,5,5,6,78,8,65,5,7,656,5]
mp = map(lambda i: i + 5, x) #This will add 5 to every element. Ovbiously u can multiply by two and divide etc
print(list(mp)) #Then it will print out all the elements + 5

y = [1,5,67,4,5,58,67,8]
mp2 = filter(lambda i: i % 2 == 0, y) #This will now only return the numbers that are even
print(mp(list))

#F strings
x = f"hello {5 + 5}" #Like normal strings but wuth f strings u can use curly brackets to implement elements like variables and integers etc


