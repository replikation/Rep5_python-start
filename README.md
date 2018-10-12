python3 help from shell pov
===
Tutorial from here:
https://www.tutorialspoint.com/python3/python_overview.htm

# Basics
* in shell do `python3` to open the command line
* `python3 skript.py` to execute .py skript

## Special rules
* you can split a command line like this into multiple lines

```python
total = item_one + \
   item_two + \
   item_three
```

## Commands
```python
#!/usr/bin/python3
print("test") #basically like echo, includes \n
input("\n\nPress the enter key to exit.") #creates a user prompt, has two empty lines before
; #like shell to get more commands in one line
```

## Variables in python3
Usually
* Class names start with an uppercase letter
* All other identifiers start with a lowercase letter
* Starting an identifier with a single leading underscore indicates that the identifier is private
* don't use words like `for` etc for it
A few examples:

```python
#!/usr/bin/python3

counter = 100          # An integer assignment
miles   = 1000.0       # A floating point
name    = "John"       # A string

print (counter)
print (miles)
print (name)
# also possible to add one input to multiple variables
a = b = c = 1
#or like an oneliner array (so a get 1 b 2 etc.)
a, b, c = 1, 2, "john"
```
* you have variable out put options for variables

```python
#!/usr/bin/python3

str = 'Hello World!'

print (str)          # Prints complete string, starts at 0
print (str[0])       # Prints first character of the string
print (str[2:5])     # Prints characters starting from 3rd to 5th
print (str[2:])      # Prints string starting from 3rd character
print (str * 2)      # Prints string two times
print (str + "TEST") # works only on strings i think
```


## Loops
* are without braces, spacing and lines depends if it works
* exampleS
```python
for i in [1,2,3]:
    print(i) #only shows the variable
    print('%sbp' % i) #this is how to put variables and text together
    print("____")
print("loop is ended, wow")

#first line with : is called header, all of it is called suite
if expression :
   suite
elif expression :
   suite
else :
   suite
```
