### <div align="center"> <h1> Python Basics Project </h1> </div>

<p align="center">
  <img src="https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/eee03277-7726-4c39-ad77-135cc72cb9f2" alt="">
</p>

Welcome to **Python Basics Project**, your gateway to mastering the fundamentals of Python programming! This comprehensive base project provides a solid foundation for beginners and aspiring Python developers to explore the core concepts of the language in a structured and engaging manner. This Python Basics Project is a collection of coding questions and exercises designed to reinforce fundamental programming concepts in Python. It covers topics such as lists, tuples, dictionaries, object-oriented programming (OOP), class creation, and inheritance.

### Topics that covered in this project :

- String Indexing
- List Operations
- Dictionaries
- Built-in Functions(len, sum, max, sorted, abs)
- Class Creation
- Class Inheritance
- Looping Statements(For and While loop)
- Lambda Functions
- User Defined Functions(UDF's)

In this project, we have included 5 coding questions for each topic, providing a comprehensive coverage of fundamental Python concepts

### Definitions of each topic that has been covered in this project :

**String Indexing:** String indexing refers to the ability to access individual characters within a string by their position, or index, in the string. Indexing in Python starts from 0, with the first character at index 0, the second at index 1, and so on.

**List Operations:** List operations involve various actions that can be performed on lists in Python, such as adding or removing elements, accessing elements by index, slicing lists to extract sublists, and concatenating lists.

**Dictionaries:** Dictionaries in Python are unordered collections of key-value pairs. Each key is unique within a dictionary, and it is associated with a corresponding value. Dictionaries are commonly used for data storage and retrieval based on keys.

**Built-in Functions:**

**len:** Returns the number of items in an object, such as the number of elements in a list, the number of characters in a string, or the number of key-value pairs in a dictionary.

**sum:** Calculates the sum of all elements in an iterable, such as a list or tuple.

**max:** Returns the largest element in an iterable, such as the largest number in a list or the highest character in a string.

**sorted:** Returns a new sorted list from the elements of any iterable. It can also sort dictionaries by key or value.

**abs:** Returns the absolute value of a number, which is the distance of the number from zero on the number line, without considering its sign.

**Class Creation:** Class creation refers to the process of defining a new class in Python. A class serves as a blueprint for creating objects, encapsulating data (attributes) and behaviors (methods) that describe the objects' characteristics and actions.

**Class Inheritance:** Class inheritance is a feature of object-oriented programming (OOP) that allows a new class (subclass) to inherit attributes and methods from an existing class (superclass). This enables code reuse and promotes a hierarchical structure among classes.

**Looping Statements:** Looping statements are used to execute a block of code repeatedly based on a specified condition. Python provides two main looping constructs: the for loop, which iterates over a sequence (such as a list or string), and the while loop, which continues iterating as long as a condition remains true.

**Lambda Functions:** Lambda functions, also known as anonymous functions, are small, anonymous functions defined using the lambda keyword. They are typically used when a simple function is needed for a short period and does not require a formal definition.

**User Defined Functions (UDF's):** User-defined functions (UDFs) are functions defined by the user to perform a specific task. They allow you to encapsulate a block of code that can be reused multiple times throughout a program, promoting code organization and reusability.

#### <div align="center"> <h1> BASIC PYTHON DATA MANIPULATION OBJECTIVES </h1> </div>

### String Indexing:

1. What is the index of the first occurrence of the letter 'o' in the string "Hello, world!"?

**Code -**

string = "Hello, world!"

index = string.find('o')

print("Index of the first occurrence of 'o':", index)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/18fd830d-965d-4486-b257-13c742168898)

2. How would you extract the substring "world" from the string "Hello, world!" using string indexing?

  **Code -**

string = "Hello, world!"

substring = string[7:12]

print("Extracted substring:", substring)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/8ad188b6-2c96-468e-8761-8bc3143cf269)

3. Given the string "racecar", how would you check if it is a palindrome using string indexing?

**Code -**

string = "racecar"

is_palindrome = string == string[::-1]

if is_palindrome:
    
    print("The string is a palindrome.")

else:
    
    print("The string is not a palindrome.")

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/8c12e8a9-13a6-4077-bfcd-6ac8f1ccf677)

4. How would you reverse a string using string indexing?

**Code -**

string = "Hello, world!"

reversed_string = string[::-1]

print("Reversed string:", reversed_string)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/408c1fbb-d749-4799-addc-b2b45c572c8f)

5. Given the string "banana", how would you access the last character using negative indexing?

**Code -**

string = "banana"

last_character = string[-1]

print("Last character:", last_character)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/a0a49b04-254b-481d-804c-29703a41418f)

### List Operations:

1. Given the list [1, 2, 3, 4, 5], how would you access the third element?

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/eb1d1133-2d87-4a77-8426-68912411bbc6)

2. How would you add an element to the end of a list?

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/9f1f3d0b-dc1d-421b-99aa-77c62adc2cc6)

3. Given the list [10, 20, 30, 40, 50], how would you change the value of the third element to 35?
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/0db164aa-e0f5-489b-bf55-fc505f0fa78b)

4. How would you remove the last element from a list?

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/306c84c2-4886-4dcb-944a-0a578f22a0a3)

5. Given the lists [1, 2, 3] and [4, 5, 6], how would you concatenate them into a single list?
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/4326a080-24e9-452a-9b0c-3ae8006a8c7a)

### Dictionary Operations:

1. Given the dictionary {'Name': 'John', 'Age': 30, 'City': 'New York'}, how would you access the value associated with the key 'age'?

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/c060ac41-7dea-47c1-bec6-b37c7bb0921f)
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/e879e487-88af-4a62-9cb9-99cbb9253b5a)

3. How would you add a new key-value pair 'gender': 'Male' to the dictionary?
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/b770dd1e-61e2-4e9a-8a54-93b694acfa49)
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/3b8599d9-3205-4098-8cf7-06f5700c7ff8)

4. Given the dictionary {'a': 1, 'b': 2, 'c': 3}, how would you change the value associated with the key 'b' to 5?
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/d1f1fc70-a981-47ea-9837-f7273cd6e9f1)

5. How would you remove a key-value pair from a dictionary?

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/5ffc0192-dff5-48a5-bee1-79a8fdc5bfaa)
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/be84e38b-8dec-4cc9-80b0-63fb2a886e50)

6. How would you create a dictionary from two lists, one containing keys and the other containing values?
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/21fdb6ae-621a-4a8a-a563-db4d478e0ddb)

### Built-in Functions (len, sum, max, sorted, abs):

1. How would you use the len() function to find the number of elements in a list?
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/367f7599-f5bc-433f-a376-feb65369de35)

2. How would you use the sum() function to find the sum of elements in a list of numbers?
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/af69fb32-d1e3-4b71-be20-f779f6824f69)

3. How would you use the max() function to find the largest element in a list of numbers?
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/6799ce23-eb4e-43e5-8f52-64b4b25e04ec)

4. How would you use the abs() function to find the absolute value of -10?
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/58c4f19b-8916-498e-a858-a8ec0b006e79)

5. How would you use the sorted() function to sort a list of numbers in ascending order?
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/d4e8d526-ca4a-4fa9-8d46-0326af9a7754)

### Class Creation:

1. Define a class Car with attributes make, model, and year. Implement a method display_info() that prints out the car's make, model,and year.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/e330bd73-219b-4145-9f93-cb83d64a0081)

2 Create a class Book with attributes title, author, and pages. Implement a method display_info() that prints out the book's title, author, and number of pages.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/ed54b69d-ce00-4ad6-8832-f6995a6ab0d9)

3. Create a class Dog with attributes name, breed, and age. Implement a method speak() that prints out the dog's name and says "Woof!".

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/d75a55fa-27ce-4d02-a0da-e31f750bd30a)

4. Create a class Employee with attributes name, salary, and department. Implement a method get_bonus() that returns 10% of the employee's salary as a bonus.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/a306702d-cabd-48f0-860c-ddf4a3822194)

5. Define a class Student with attributes name and age. Implement a method is_adult() that returns True if the student is 18 years or older, otherwise False.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/9ba6811d-0040-41b2-923c-970dab4e82cb)

### Class Inheritance:

1. Define a class Animal with attributes name and species. Create a subclass Dog that inherits from Animal and adds an attribute breed. Implement a method speak() in both classes to print out the sound the animal makes.
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/685d5da8-30fa-47cd-ba9f-e2c5238a6ff8)

2. Create a class Employee with attributes name and salary. Define a subclass Manager that inherits from Employee and adds an attribute bonus. Implement a method calculate_total_salary in both classes to calculate the total salary including bonus for a manager.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/19dd8b05-4025-4ab2-88c9-39012b0b60c1)

3. Define a class Person with attributes name and age. Create a subclass Student that inherits from Person and adds an attribute grade. Implement a method is_passing in the Student class that returns True if the student's grade is above or equal to 'C', otherwise False.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/1c1818db-40cb-42a4-b3f7-81e2775a403d)

4. Define a class Employee with attributes name and salary. Create subclasses Manager and Developer that inherit from Employee. Implement methods calculate_bonus in each subclass to calculate the bonus based on the salary.
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/2252c046-905f-4bfa-8e2d-92ac768d34d8)

5. Create a class Fruit with attributes name and color. Define a subclass Apple that inherits from Fruit and adds attributes taste and size. Implement a method is_delicious() in both classes to determine if the fruit is delicious based on its taste.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/42cbb5a7-2fbd-412d-ae7a-602a415abfcf)

### Looping Statements
**For Loop**

1. Write a program to print the numbers from 1 to 5 using a for loop.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/bc68d383-65e1-49ff-a6ac-c27f84a7ab62)

2. Write a program to print the even numbers between 1 and 10 using a for loop.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/dae65282-e2c4-4709-a3ab-57afccb4ca7e)

3. Write a program to calculate the sum of all numbers from 1 to 100 using a for loop.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/2bf13514-07a8-44ba-93c9-cb70fa232ebc)

4. Write a program to find the factorial of a given number using a for loop.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/297d8341-f61f-4c61-a925-be0cdca9029f)

5. Write a program to print the Fibonacci series up to a certain limit using a for loop.
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/c6329f3a-9c00-475a-aa73-06a725433f58)

**While Loop**

1. Write a program to print the numbers from 1 to 5 using a while loop.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/ff5afbe0-e00d-4476-b6fb-81af198bd48f)

2. Write a program to print the even numbers between 1 and 10 using a while loop.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/43330fae-a1e2-4da5-ad13-d4405f6e3e8d)

3. Write a program to calculate the sum of all numbers from 1 to 100 using a while loop.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/d7cc9d55-5ab2-42c8-8ee3-44aa4d18a0b1)

4. Write a program to find the factorial of a given number using a while loop.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/257e313c-2239-424a-a5c2-8db51c40527b)

5. Write a program to print the Fibonacci series up to a certain limit using a while loop.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/2e1d7de6-8016-4f8a-956d-60787573ad00)

### Lambda Functions:

1. Write a lambda function to calculate the square of a number.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/3a7f080a-8244-4ebc-8c4c-48801cbc10ba)

2. Create a list of numbers and use a lambda function to filter out the even numbers.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/83b7d0c8-917e-4702-a57b-25b868deb359)

3. Write a lambda function to find the sum of two numbers.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/d88cccb7-690e-404a-bc89-c62997057650)

4. Create a list of tuples containing student names and their corresponding scores. Use a lambda function to sort the list by scores.
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/e89809fb-2083-4a80-a461-82cf665b1b0c)

5. Create a list of strings and use a lambda function to sort them alphabetically.
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/98f66765-20ff-43d0-b3d7-f1455c36070c)

### UDF: Arguments and Parameters

1. Write a function called add_numbers that takes two numbers as input and returns their sum.
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/27386098-25ad-4d8a-919a-a2a5c09504de)

2. Create a function called is_even that takes a single number as input and returns True if it's even, otherwise False.
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/6f2b7402-b683-407a-be27-f53505f43faf)

3. Define a function called calculate_area that calculates the area of a rectangle given its length and width as input parameters.
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/b97de5e1-9ebd-4b86-809d-084cbd198f15)

4. Write a function called reverse_string that takes a string as input and returns its reverse.
   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/1186566d-1340-4b6f-a324-bafad99220d4)

5. Create a function called is_prime that takes a positive integer as input and returns True if it's prime, otherwise False.

   ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/71e08795-362c-4ccb-8e79-5ff8595059e4)
