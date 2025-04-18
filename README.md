# Python Print Function

print('Md Abdul Aouwal')
#. If you want to use separators 
print('Abdul','Aouwal', sep="***")
#. newline = \n
#. i'm = i\'m
#. tab or 4 space = \t

# Python Variable
variable store data
Must start with character or underscore (name, _name )
Can't start with number
A-z, 0-9, _ allowed
age , Age, AGE all are different


# Python data types
Text types --> String
Number --> integer(5,6,7), float(5.0, 6.3), complex (2+3j)
Boolean -- True, False
Sequence --> List, tuple , Range
Mapping Type - Dictionary
Set
None

# Data Casting
Convert one type to another type

int() --> Convert string or float to integer
str() --> Convert to String
float() --- > Convert to float

# Python Operators
Arthmetic Operators : +, -, *, /, %(Modulus Operators), **(Exponent), //(Floor Division)
Assignment Operators: =, y += 3 ( y = y + 3)
Comparison Operators: == (equal), != (Not equal), > (Greater than), < (less than), >=(Greater than Equal), <= (Less than Equal)
Logical Operators: and , or , not
Identity Operators : is, is not
Membership Operators: in , not in

# Python list
List is sequence of data, mulitple value or data can be stored
access: listname[indexnumber]
fruits = ['Banana', 'Mango', 'Apple]
fruits[1]
List element can be changed
fruits = ['Banana', 'Mango', 'Apple]
fruits[1]='Orange'
print(fruits)
#. output: ['Banana', 'Orange', 'Apple]
Adding Element to the list: Listname.append(Data) - at the end of the list, list.insert(index, data) at index position
List element remove: list.pop()-- last element will removed, list.pop(2)-- index item 2 will be removed
remove by value: list.remove(data), list.clear -- empty list

# Dictionary
used to store data values in key:value pairs.
Access:
mobile = {'model':'I phone 16', 'price': 380000}
mobile['price'] # 380000
mobile.getitem('model')
Change or add
mobile = {'model':'I phone 16', 'price': 380000}
mobile['price'] = 50000 
mobile.getitem({'model':'I phone 16'})
remove
mobile = {'model':'I phone 16', 'price': 380000}
mobile.pop('price')
Keys or values list
mobile = {'model':'I phone 16', 'price': 380000}
mobile.keys()
mobile.values()

# Python If Else
Python conditon:
# syntax  
#  if condtion(true)
        # Code
a = 200
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")

# While loop
i = 1
while i < 6:
  print(i)
  i += 1
