Q1. Why do we call Python as a general purpose and high-level programming language?
sol: Python is applicable in various domains and not specialised for particular domains. Python is user oriented and designed to make it straightforward for a programmer to convert an algorithm into program code. It resembles natural language and mathematical notations.

Q2. Why is Python called a dynamically typed language?
sol: Python doesn't have any problem even if we don't declare the type of variable. It states the kind of variable in the runtime of the program. Python also takes care of the memory management which is crucial in programming. So, Python is a dynamically typed language.

Q3. List some pros and cons of Python programming language?
sol: Pros:
Extensive libraries
Python is extremely flexible and can be extended to other languages. Developers can write code in C  and C++ and build new features in the dynamically-typed language
Large Community
Portable 
IOT and ML applications.

      Cons:
Slower than compiled languages
Not 100% secure
High memory usage

Q4. In what all domains can we use Python?
sol: Machine Learning
IOT
Web Development
Robotics


Q5. What are variable and how can we declare them?
sol: Variables are containers to store data values. Python has no command for declaring a variable. A variable is created the moment you assign a value to it.

Q6. How can we take an input from the user in Python?
sol: input (): This function first takes the input from the user and converts it into a string. The type of the returned object always will be <type ‘str’>. It does not evaluate the expression, it just returns the complete statement as String. For example, Python provides a built-in function called input which takes the input from the user. When the input function is called it stops the program and waits for the user’s input. When the user presses enter, the program resumes and returns what the user typed.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
sol: The type of the returned object always will be <type ‘str’>.

Q8. What is type casting?
sol: We have five built-in (general) data types in python namely - numeric, sequence type, boolean, set, and dictionary. The conversion of one data type into the other data type is known as type casting in python or type conversion in python. Python supports a wide variety of functions or methods like: int(), float(), str(), ord(), hex(), oct(), tuple(), set(), list(), dict(), etc. for the type casting in python. There are two varieties of typecasting in python namely - Explicit Conversion(Explicit type casting in python), and Implicit Conversion(Implicit type casting in python). The conversion of one data type into another, done via user intervention or manually as per the requirement, is known as explicit type conversion. On the other hand, in Implicit type conversion, Python automatically converts one data type to another data type without any user's need.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
sol: Python provides two methods to get multiple inputs. 
split()
List comprehension
        
       First method,
a, b, c = input("Enter three values: ").split()  
print("Enter Your First Name: ", a)  
print("Enter Your Last Name: ", b)  
print("Enter Your Class: ", c)  
print()  
      Second method,
            x = list(map(int, input("Enter multiple values: ").split()))  
print("List of students: ", x)

Q10. What are keywords?
sol: Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.
sol: We cannot use keywords as variables which will lead to ambiguity for the compiler.

Q12. What is indentation? What's the use of indentaion in Python?
sol: Indentation refers to the spaces at the beginning of the code line. In python it's for readability and it's compulsory. It uses indentation to identify the block of code.

Q13. How can we throw some output in Python?
sol: To throw output, print() is used.

Q14. What are operators in Python?
sol: Operators are used to perform operations on variables and values. 
         Arithmetic, assignment, logical, bitwise, comparison, identity, membership operators.

Q15. What is difference between / and // operators?
sol: / gives float division value and // gives floor division.

Q16. Write a code that gives following as an output.

iNeuroniNeuroniNeuroniNeuron

sol: for i in range(3):
            print(‘iNeuron’, end=””)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
sol: num=int(input())
         If num%2==0:
            print(“Even number”)
           else:
                print(“Odd number”)

Q18. What are boolean operator?
sol: Boolean operators are True and False, Not, And and OR in Python.

Q19. What will the output of the following?

1 or 0

0 and 0

True and False and True

1 or 0 or 0
sol: 1
         0
         FALSE
         1

Q20. What are conditional statements in Python?
sol: If, If else, if elif are conditional statements in Python

Q21. What is use of 'if', 'elif' and 'else' keywords?
sol:  If else is used to run the code on required condition. If there are multiple conditions, use elif. 
Ex:
num=10
If num>5:
   print(“greater than 5”)
elif num>3:
   print(“greater than 3 but smaller than 5”)
else:
   print(“smaller than 3”)

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
sol: If age>18:
  print(“I can vote”)
else:
 print(“I can’t vote”)

Q23. Write a code that displays the sum of all the even numbers from the given list.
numbers = [12, 75, 150, 180, 145, 525, 50]
sol: sum=0
         for i numbers:
              sum+=i

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
sol: a,b,c=int(input()).split()
        If a>b and a>c:
            print(a)
         elif b>a and b>c:
            print(b)
        else:
           print(c)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

The number must be divisible by five

If the number is greater than 150, then skip it and move to the next number

If the number is greater than 500, then stop the loop

numbers = [12, 75, 150, 180, 145, 525, 50]
Solution:
for i in numbers:
   if i>150:
     continue
   if i>500:
     break
   if i%5==0:
     print(i)

Q26. What is a string? How can we declare string in Python?
solution:
String is a sequence of characters. Python has builtin string class called str. Python strings are "immutable".

Q27. How can we access the string using its index?
solution:
s='iNeuron'
s[1] will print N

Q28. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "iNeuron"

sol:
desired=string[9:]
print(desired)

Q29. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "norueNi"
sol:
tem=string[-1:-8]
print(tem)

Q30. Resverse the string given in the above question.
sol: print(tem[::-1])

Q31. How can you delete entire string at once?
sol: Using del. del string_name

Q32. What is escape sequence?
sol: An escape sequence is a sequence of characters that, when used inside a character or string, does not represent itself but is converted into another character or series of characters that may be difficult or impossible to express directly, like newline (\n), tab (\t), and so on.

Q33. How can you print the below string?

'iNeuron's Big Data Course'
sol: print("iNeuron's Big Data Course")

Q34. What is a list in Python?
sol: Lists are used to store multiple items in a single variable.
     List items are ordered, changeable, and allow duplicate values.
     List items are indexed, the first item has index [0], the second item has index [1] etc.

Q35. How can you create a list in Python?
sol: list=[] or list() constructor

Q36. How can we access the elements in a list?
sol: List items are indexed and you can access them by referring to the index number

Q37. Write a code to access the word "iNeuron" from the given list.

lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
sol: lst[4][2]

Q38. Take a list as an input from the user and find the length of the list.
sol: 
n = int(input("Enter number of elements : "))
a = list(map(int,input("\nEnter the numbers : ").strip().split()))[:n]
print(len(a))

Q39. Add the word "Big" in the 3rd index of the given list.

lst = ["Welcome", "to", "Data", "course"]
sol: 
lst.insert(2,"Big")

Q40. What is a tuple? How is it different from list?
sol: A tuple is a collection which is ordered and unchangeable.Tuples are written with round brackets.
     Tuple items are ordered, unchangeable, and allow duplicate values.Tuple items are indexed, the first item has index [0], the second item has index [1] etc.

Q41. How can you create a tuple in Python?
sol: t=(1,2,3)

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
sol: tuple=(1,2)
     Once a tuple is created, you cannot change its values. Tuples are unchangeable, or immutable as it also is called.

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
sol: Yes!
     tuple1=(1,2,3)
     tuple2=(4,5,6)
     tuple3=tuple1+tuple2

Q44. Take a tuple as an input and print the count of elements in it.
sol: inp=input("Enter a value").split()
     t=tuple(inp)
     print(len(t))

Q45. What are sets in Python?
sol: Sets are written with curly brackets. Sets are used to store multiple items in a single variable.Set items are unordered, unchangeable, and do not allow duplicate values. Once a set is created, you cannot change its items, but you can remove items and add new items.

Q46. How can you create a set?
sol: set={}
     or set()

Q47. Create a set and add "iNeuron" in your set.
sol: set1={}
     set1.add("iNeuron")

Q48. Try to add multiple values using add() function.
sol. set1={}
     set2={a,b}
     set1.update(set2)
     OR
     lst=[1,2,3]
     set1.add(lst)

Q49. How is update() different from add()?
sol: We use add() method to add single value to a set. We use update() method to add sequence values to a set.

Q50. What is clear() in sets?
sol: it removes all the elements from the set.

Q51. What is frozen set?
sol: Python has an inbuilt function called frozenset() that takes an iterable object as input and makes it immutable. 

Q52. How is frozen set different from set?
sol: Frozenset is similar to set in Python, except that frozensets are immutable, which implies that once generated, elements from the frozenset cannot be added or removed. This function accepts any iterable object as input and transforms it into an immutable object. It is not assured that the order of the elements will be retained.

Q53. What is union() in sets? Explain via code.
sol: Return a set that contains all items from both sets, duplicates are excluded.
     x = {"apple", "banana", "cherry"}
     y = {"google", "microsoft", "apple"}
     z = x.union(y)
     print(z)
     >> {'cherry', 'banana', 'microsoft', 'apple', 'google'}

Q54. What is intersection() in sets? Explain via code.
sol: Return a set that contains the items that exist in both set x, and set y.
     x = {"apple", "banana", "cherry"}
     y = {"google", "microsoft", "apple"}
     z = x.intersection(y)
     print(z)
    >> {'apple'}

Q55. What is dictionary in Python?
sol: Dictionaries are used to store data values in key:value pairs. A dictionary is a collection which is ordered*, changeable and do not allow duplicates.

Q56. How is dictionary different from all other data structures.
sol: Dictionary is one of the important Data Structures that is usually used to store data in the key-value format. Each element presents in a dictionary data structure compulsorily have a key and some value is associated with that particular key. In other words, we can also say that Dictionary data structure is used to store the data in key-value pairs. Other names for the Dictionary data structure are associative array, map, symbol table but broadly it is referred to as Dictionary.
The various operations that are performed on a Dictionary or associative array are:
Add or Insert: In the Add or Insert operation, a new pair of keys and values is added in the Dictionary or associative array object.
Replace or reassign: In the Replace or reassign operation, the already existing value that is associated with a key is changed or modified. In other words, a new value is mapped to an already existing key.
Delete or remove: In the Delete or remove operation, the already present element is unmapped from the Dictionary or associative array object.
Find or Lookup: In the Find or Lookup operation, the value associated with a key is searched by passing the key as a search argument.

Q57. How can we delare a dictionary in Python?
sol: players=dict()  
Q58. What will the output of the following?

var = {}
print(type(var))
sol: <class 'dict'>

Q59. How can we add an element in a dictionary?
sol: CountryCodeDict = {"India": 91, "UK" : 44 , "USA" : 1}
     print(CountryCodeDict)
     CountryCodeDict["Spain"]= 34
     print "After adding"
     print(CountryCodeDict)

Q60. Create a dictionary and access all the values in that dictionary.
sol: mydict={"Name": "Rohit","Age":24}
     x=mydict["Name"]
     or
     y=mydict.get("Name")

Q61. Create a nested dictionary and access all the element in the inner dictionary.
sol: myfamily = {
  "child1" : {
    "name" : "Emil",
    "year" : 2004
  },
  "child2" : {
    "name" : "Tobias",
    "year" : 2007
  },
  "child3" : {
    "name" : "Linus",
    "year" : 2011
  }
}
Q62. What is the use of get() function?
sol: get() gives the value for the key we pass.

Q63. What is the use of items() function?
sol: It gives the key value pairs as a list.

Q64. What is the use of pop() function?
sol: The pop() method removes the specified item from the dictionary.The value of the removed item is the return value of the pop() method.
car = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
x = car.pop("model")
print(x)
>> "Mustang"

Q65. What is the use of popitems() function?
sol: Remove the last item from the dictionary.

Q66. What is the use of keys() function?
sol: you get the keys of the dict as a list. 

Q67. What is the use of values() function?
sol: you get the values as a list.

Q68. What are loops in Python?
sol: Python programming language provides the following types of loops to handle looping requirements. Python provides three ways for executing the loops. While all the ways provide similar basic functionality, they differ in their syntax and condition checking time.

Q69. How many type of loop are there in Python?
sol: Python provides three ways for executing the loops.

Q70. What is the difference between for and while loops?
sol: A for loop is a control flow statement that executes code for a predefined number of iterations. The keyword used in this control flow statement is “for”. When the number of iterations is already known, the for loop is used.
A loop that runs a single statement or a set of statements for a given true condition. This loop is represented by the keyword "while." When the number of iterations is unknown, a "while" loop is used. The statement is repeated until the boolean value is false. Because the condition is tested at the beginning of a while loop, it is also known as the pre-test loop.

Q71. What is the use of continue statement?
sol: The continue keyword is used to end the current iteration in a for loop (or a while loop), and continues to the next iteration.

Q72. What is the use of break statement?
sol: 'Break' in Python is a loop control statement. It is used to control the sequence of the loop. Suppose you want to terminate a loop and skip to the next code after the loop; break will help you do that. 

Q73. What is the use of pass statement?
sol: The pass statement is used as a placeholder for future code. When the pass statement is executed, nothing happens, but you avoid getting an error when empty code is not allowed. Empty code is not allowed in loops, function definitions, class definitions, or in if statements.

Q74. What is the use of range() function?
sol: The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.

Q75. How can you loop over a dictionary?
sol: a_dict = {'color': 'blue', 'fruit': 'apple', 'pet': 'dog'}
>>> for key in a_dict:
...     print(key, '->', a_dict[key]) 


Coding problems
Q76. Write a Python program to find the factorial of a given number.

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

Q79. Write a Python program to check if a number is prime or not.

Q80. Write a Python program to check Armstrong Number.

Q81. Write a Python program to find the n-th Fibonacci Number.

Q82. Write a Python program to interchange the first and last element in a list.

Q83. Write a Python program to swap two elements in a list.

Q84. Write a Python program to find N largest element from a list.

Q85. Write a Python program to find cumulative sum of a list.

Q86. Write a Python program to check if a string is palindrome or not.

Q87. Write a Python program to remove i'th element from a string.

Q88. Write a Python program to check if a substring is present in a given string.

Q89. Write a Python program to find words which are greater than given length k.

Q90. Write a Python program to extract unquire dictionary values.

Q91. Write a Python program to merge two dictionary.

Q92. Write a Python program to convert a list of tuples into dictionary.

Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.

Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
Q94. Write a Python program to get all combinations of 2 tuples.

Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
Q95. Write a Python program to sort a list of tuples by second item.

Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
Q96. Write a python program to print below pattern.

* 
* * 
* * * 
* * * * 
* * * * * 
Q97. Write a python program to print below pattern.

    *
   **
  ***
 ****
*****
Q98. Write a python program to print below pattern.

    * 
   * * 
  * * * 
 * * * * 
* * * * * 
Q99. Write a python program to print below pattern.

1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
Q100. Write a python program to print below pattern.

A 
B B 
C C C 
D D D D 
E E E E E 
