# Question-1. In the below elements which of them are values or an expression? eg:- values can be integer or string and expressions will be mathematical operators.
*
'hello'
-87.8
-
/
+
6

A.1 Values and expressions can be identified as follows:

Values:
*'hello'-string value
*-87.8 - float value
*6 - int value

Expressions:
- (subtraction operator)
/ (division operator)
+ (addition operator)

-> Values are actual data , such as strings or numbers, while expressions operator are used to perform mathematical and computational operations

# Question-2.What is the difference between string and variable?

A.2 So the difference between string and variable is as follows:

String: Represent textual data in programming.It's sequence of character enclosed within quotes. Eg. "Elephant"

Variable: It's a named storage location that holds a value in program. Storing and manipulating data during execution of program. Variables can hold different types of data including strings, numbers, boolean values & more.

Values are assigned using assignment operator(=)
Eg. age=55

# Question-3.Describe three different data types?

 A.3 So three different data types are :
 
 int(), str(), bool()
 
 Integer(int):Only contains integer data types like whole numbers without decimal points.It contains bot negative and positive number including zero.Eg. age=35
 
 string(str):It contains sequence of character enclosed within quotes.They allow operations like concatenation, slicing and searching for specific patterns.Eg. name= "Deepak"
 
 Boolean(bool):It represents logical values, indicating either true or false.Used in decision making and controlling flow structures.
 is_birthday = True
    

# Question-4.What is an expression made up of? What do all expressions do?

A.4 An expression is made up of one or more operands and operator.It combines values, variables and operators to give new value.
In an expression, operands can be literal values(such as numbers or strings)and variable holds the value.

Eg. of expression:
->Simple arithmetic expression
  c=2+5
->Complex arithmetic expression
  c=(2+5)/7*1
->Comparison expression
  is_lesser = 5>2
returns boolean value to the variable

# Question-5.This assignment statements, like spam = 10. What is the difference between an expression and a statement?

A.5 Some key differences between expression and statement.

Expressions evaluate to a value, while statements do not.

An expression is a combination of values, variables, operators, and function calls that produces a result when evaluated.
 
Examples of expressions include 2 + 3, x * y, or math.sqrt(16).Expressions can be used within statements.
 
A statement is a complete unit of code that performs a specific action or control flow operation. It represents a complete instruction in a program. They don't produce a value like expressions do.

Examples of statements include variable assignments (spam = 10), conditional statements (if, else, elif), loops (for, while), function definitions, and function calls.

We can use expression within statement to get the logic or value, while statement controls the flow of program.


# Question-6. After running the following code, what does the variable bacon contain?

bacon = 22
bacon + 1

A.6 Here the variable bacon contains the value 22.The expression bacon + 1 does not update the value of bacon itself; it only calculates the result of adding 1 to the current value of bacon. If you want to update the value of bacon, you would need to assign the result back to the variable, like this:

bacon = 22
bacon = bacon + 1

After executing this line bacon's value will be incremented to 23.

# Question-7. What should the values of the following two terms be?
'spam' + 'spamspam'
'spam' * 3

A.7 The value of 'spam'+''spamspam' should be ''spamspamspam'.This is because +operator is used to concatenate string.

Also the value of 'spam'*3 will be equal to 'spamspamspam'.This is because *operator is used to repeat a string a specified number of times.

# Question-8.Why is eggs a valid variable name while 100 is invalid?

A.8 In python variable follows few rules:
    *They must start with a letter or underscore(_) character.
    *They can only contain letters numbers and underscore character.
    *They cannot be same as keyword.
    
Hence since, eggs follow all the rules and fulfill all conditions,it's set to be a valid variable,while 100 is not and is invalid.

# Question-9.What three functions can be used to get the integer, floating-point number, or string version of a value?

A.9 The three functions that can be used to get the integer,floating point number or string version of a value are:
    *int():This function can be used to convert a value to integer.It returns whole number part of the value. Eg. 
        a=int(3.14)
        print(a)     #Output will be 3
    *float():This function is used to convert a value to a floating point number.It will add decimal places to represent the          value accurately.Eg.
        a=float(3)
        print(a)     #Output will be 3.0
    *str():This value converts a value to its string representation. It can be used to convert any value to string.Eg.
        a=str(3)
        b=str(3)
        c=a+b
        print(c)     #output  33


```python
a=str(3)
b=str(3)
c=a+b
print(c)
```

    33
    

# Question-10.Why does this expression cause an error? How can you fix it?

'I have eaten' + 99 +'burritos'

A.10 This expression is causing an error because, we are trying to concatenate a string with an integer which is not possible, until we convert the type of int to str.

For that we need to write the code as follows:


```python
a=' I have eaten '+ str(99) +' burritos '
print(a)
```

     I have eaten 99 burritos 
    

eg. using f-string formatting
    


```python
result= f'I have eaten {99} burritos.'
print(result)
```

    I have eaten 99 burritos.
    


```python

```
