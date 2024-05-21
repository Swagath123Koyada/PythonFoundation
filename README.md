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

- In this project, we have included 5 coding questions for each topic, providing a comprehensive coverage of fundamental Python concepts

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

**Code -**

my_list = [1, 2, 3, 4, 5]

third_element = my_list[2]

print("Third element:", third_element)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/9e5b7c88-e444-4481-afcd-4bb6228b47b9)

2. How would you add an element to the end of a list?

**Code -**

my_list = [1, 2, 3, 4, 5]

my_list.append(6)

print("Updated list:", my_list)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/6e779334-36e5-4d03-8578-969084abb5a0)

3. Given the list [10, 20, 30, 40, 50], how would you change the value of the third element to 35?

**Code -**

my_list = [10, 20, 30, 40, 50]

my_list[2] = 35

print("Updated list:", my_list)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/caa0b020-0994-4071-b655-4f46b859eb99)

4. How would you remove the last element from a list?

**Code -**

my_list = [10, 20, 30, 40, 50]

my_list.pop()

print("Updated list:", my_list)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/666458bf-d3dd-4340-9fb6-e31c70703077)

5. Given the lists [1, 2, 3] and [4, 5, 6], how would you concatenate them into a single list?

**Code -**

list1 = [1, 2, 3]

list2 = [4, 5, 6]

concatenated_list = [item for sublist in zip(list1, list2) for item in sublist]

print("Concatenated list:", concatenated_list)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/c4ede065-e918-4b58-b217-f31f1deb0551)

### Dictionary Operations:

1. Given the dictionary {'Name': 'John', 'Age': 30, 'City': 'New York'}, how would you access the value associated with the key 'age'?

**Code -**

- **Using square bracket notation:**

my_dict = {'Name': 'John', 'Age': 30, 'City': 'New York'}

age_value = my_dict['Age']

print("Value with the key 'Age':", age_value)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/5248e49b-e467-44ad-ba7c-aa3fe8475e8c)

- **Using the get() method:**

my_dict = {'Name': 'John', 'Age': 30, 'City': 'New York'}

Age_Value = my_dict.get('Age')

print("Value with the key 'Age':", Age_Value)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/d2865302-2671-4b8e-a3f4-e2bb2dd0363f)

2. How would you add a new key-value pair 'gender': 'Male' to the dictionary?

**Code -**

- **Using square bracket notation:**
     
my_dict = {'Name': 'John', 'Age': 30, 'City': 'New York'}

my_dict['Gender'] = 'Male'

print("Updated dictionary:", my_dict)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/aa7bbabc-540f-44f1-91e3-47b6b84b454f)

- **Using the update() method:**

my_dict = {'Name': 'John', 'Age': 30, 'City': 'New York'}

my_dict.update({'Gender': 'Male'})

print("Updated dictionary:", my_dict)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/04e15352-cb90-46d2-a043-1485ce14b6cb)

3. Given the dictionary {'a': 1, 'b': 2, 'c': 3}, how would you change the value associated with the key 'b' to 5?

**Code -**

my_dict = {'a': 1, 'b': 2, 'c': 3}

my_dict['b'] = 5

print("Updated dictionary:", my_dict)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/c8c858df-a4ae-4a5c-8098-46c350503ce5)

4. How would you remove a key-value pair from a dictionary?

**Code -**

- **Using the del keyword:**

my_dict = {'a': 1, 'b': 2, 'c': 3}

del my_dict['b']

print("Updated dictionary:", my_dict)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/37a23d38-27a0-4d86-9efe-50a71f972c83)

- **Using the pop() method:**

my_dict = {'a': 1, 'b': 2, 'c': 3}

my_dict.pop('b')

print("Updated dictionary:", my_dict)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/88c9124b-f1e5-41f2-a24c-8c5824058bfe)

5. How would you create a dictionary from two lists, one containing keys and the other containing values?

**Code -**

- **Using a dictionary comprehension:**
     
keys = ['a', 'b', 'c']

values = [1, 2, 3]

my_dict = {k: v for k, v in zip(keys, values)}

print("Created dictionary:", my_dict)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/d5e219c2-8ad4-4a15-9ac3-ef80d4457b60)

### Built-in Functions (len, sum, max, sorted, abs):

1. How would you use the len() function to find the number of elements in a list?

**Code -**

my_list = [1, 2, 3, 4, 5]

list_length = len(my_list)

print("Number of elements in the list:", list_length)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/503fee9b-2484-47d4-a68c-d222b1b37d12)

2. How would you use the sum() function to find the sum of elements in a list of numbers?

**Code -**

numbers = [1, 2, 3, 4, 5]

sum_of_numbers = sum(numbers)

print("Sum of elements in the list:", sum_of_numbers)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/af534db3-0288-4f9f-ad2a-61725480e439)

3. How would you use the max() function to find the largest element in a list of numbers?

**Code -**

numbers = [10, 20, 30, 40, 50]

largest_number = max(numbers)

print("Largest element in the list:", largest_number)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/3d9eb022-7681-41e0-ba99-c42ff45833a6)

4. How would you use the abs() function to find the absolute value of -10?

**Code -**

absolute_value = abs(-10)

print("Absolute value of -10:", absolute_value)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/66720208-e199-4ecc-9ca4-70aa5c0660eb)

5. How would you use the sorted() function to sort a list of numbers in ascending order?

**Code -**

numbers = [5, 2, 8, 1, 10]

sorted_numbers = sorted(numbers)

print("Sorted list of numbers:", sorted_numbers)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/2e104b20-6c90-4bc5-96e9-3dd4116c8972)

### Class Creation:

1. Define a class Car with attributes make, model, and year. Implement a method display_info() that prints out the car's make, model,and year.

**Code -**

class Car:
    
    def __init__(self, make, model, year):
        self.make = make
        self.model = model
        self.year = year

    def display_info(self):
        print("Car Make:", self.make)
        print("Car Model:", self.model)
        print("Car Year:", self.year)

car1 = Car("Toyota", "Corolla", 2020)

car1.display_info()

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/03f58bfe-bb35-406a-8020-c7aceb0966db)

2 Create a class Book with attributes title, author, and pages. Implement a method display_info() that prints out the book's title, author, and number of pages.

**Code -**

class Book:
    
    def __init__(self, title, author, pages):
        self.title = title
        self.author = author
        self.pages = pages

    def display_info(self):
        print("Title:", self.title)
        print("Author:", self.author)
        print("Number of Pages:", self.pages)

book = Book("The Great Gatsby", "F. Scott Fitzgerald", 180)

book.display_info()

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/5d1559a4-5f6d-4a27-afe3-75ab3efb8e04)

3. Create a class Dog with attributes name, breed, and age. Implement a method speak() that prints out the dog's name and says "Woof!".

**Code -**

class Dog:
    
    def __init__(self, name, breed, age):
        self.name = name
        self.breed = breed
        self.age = age

    def speak(self):
        print(f"{self.name} says 'Woof!'")

my_dog = Dog("Buddy", "Labrador Retriever", 3)

my_dog.speak() 

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/b62d9179-62bb-4f19-84e4-ebc0f0525d34)

4. Create a class Employee with attributes name, salary, and department. Implement a method get_bonus() that returns 10% of the employee's salary as a bonus.

**Code -**

class Employee:
    
    def __init__(self, name, salary, department):
        self.name = name
        self.salary = salary
        self.department = department

    def get_bonus(self):
        return 0.1 * self.salary  # 10% of the employee's salary

emp = Employee("John Doe", 50000, "Engineering")

bonus_amount = emp.get_bonus()

print(f"{emp.name} earned a bonus of ${bonus_amount}")

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/4d9e1e98-2894-421e-b18a-769edf075184)

5. Define a class Student with attributes name and age. Implement a method is_adult() that returns True if the student is 18 years or older, otherwise False.

**Code -**

class Student:
    
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def is_adult(self):
        return self.age >= 18


student1 = Student("Alice", 20)

student2 = Student("Bob", 17)

print(f"{student1.name} is an adult: {student1.is_adult()}")

print(f"{student2.name} is an adult: {student2.is_adult()}")

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/0248002a-2eba-4401-8159-7249844f3a48)

### Class Inheritance:

1. Define a class Animal with attributes name and species. Create a subclass Dog that inherits from Animal and adds an attribute breed. Implement a method speak() in both classes to print out the sound the animal makes.

**Code -**

class Animal:
    
    def __init__(self, name, species):
        
        self.name = name
        
        self.species = species

    def speak(self):
        
        pass  # This method will be overridden in subclasses

class Dog(Animal):
    
    def __init__(self, name, species, breed):
        
        super().__init__(name, species)
        
        self.breed = breed

    def speak(self):
        
        print(f"{self.name} says 'Woof!'")


animal = Animal("Kitty", "Cat")

animal.speak()

dog = Dog("Buddy", "Dog", "Labrador Retriever")

dog.speak()

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/9cb3f51e-ba1c-4fbe-a0db-69190c863451)

2. Create a class Employee with attributes name and salary. Define a subclass Manager that inherits from Employee and adds an attribute bonus. Implement a method calculate_total_salary in both classes to calculate the total salary including bonus for a manager.

**Code -**

class Employee:
    
    def __init__(self, name, salary):
        
        self.name = name
        
        self.salary = salary

    def calculate_total_salary(self):
        
        return self.salary

class Manager(Employee):
    
    def __init__(self, name, salary, bonus):
        
        super().__init__(name, salary)
        
        self.bonus = bonus

    def calculate_total_salary(self):
        
        return self.salary + self.bonus

emp1 = Employee("John", 50000)

print(emp1.calculate_total_salary())

manager1 = Manager("Alice", 60000, 10000)

print(manager1.calculate_total_salary())

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/9d1b4f08-dbfd-4be6-99c3-6ca461ae7aa5)

3. Define a class Person with attributes name and age. Create a subclass Student that inherits from Person and adds an attribute grade. Implement a method is_passing in the Student class that returns True if the student's grade is above or equal to 'C', otherwise False.

**Code -**

class Person:
    
    def __init__(self, name, age):
        
        self.name = name
        
        self.age = age

class Student(Person):
    
    def __init__(self, name, age, grade):
        
        super().__init__(name, age)
        
        self.grade = grade

    def is_passing(self):
        
        return self.grade <= 'C'

student1 = Student("Alice", 20, 'B')

print(student1.is_passing())

student2 = Student("Bob", 21, 'D')

print(student2.is_passing())

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/47959148-286e-41bf-92a6-a16ff81a11c4)

4. Define a class Employee with attributes name and salary. Create subclasses Manager and Developer that inherit from Employee. Implement methods calculate_bonus in each subclass to calculate the bonus based on the salary.

**Code -**

class Employee:
    
    def __init__(self, name, salary):
        
        self.name = name
        
        self.salary = salary

class Manager(Employee):
    
    def calculate_bonus(self):
        
        return self.salary * 0.15  # Manager gets 15% bonus

class Developer(Employee):
    
    def calculate_bonus(self):
        
        return self.salary * 0.10  # Developer gets 10% bonus

manager = Manager("John", 10000)

developer = Developer("Alice", 8000)

print(f"Manager bonus: {manager.calculate_bonus()}")

print(f"Developer bonus: {developer.calculate_bonus()}")

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/4c79cf65-0d36-423b-848b-76a5c6a818bf)

5. Create a class Fruit with attributes name and color. Define a subclass Apple that inherits from Fruit and adds attributes taste and size. Implement a method is_delicious() in both classes to determine if the fruit is delicious based on its taste.

**Code -**

class Fruit:
    
    def __init__(self, name, color):
        
        self.name = name
        
        self.color = color

    def is_delicious(self):
        
        return True  

class Apple(Fruit):
    
    def __init__(self, name, color, taste, size):
        
        super().__init__(name, color)
        
        self.taste = taste
        
        self.size = size

    def is_delicious(self):
        
        return self.taste == "sweet"

fruit = Fruit("Banana", "Yellow")

print("Is banana delicious?", fruit.is_delicious())

apple = Apple("Apple", "Red", "sweet", "medium")

print("Is apple delicious?", apple.is_delicious())

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/a4b4391d-6570-47ee-ae9a-255f29bb22da)

### Looping Statements
**For Loop**

1. Write a program to print the numbers from 1 to 5 using a for loop.

**Code -**

for number in range(1, 6):
    
    print(number, end=' ')

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/a8facb34-b2a8-42a8-8dab-f21e70e375b4)

2. Write a program to print the even numbers between 1 and 10 using a for loop.

**Code -**

for number in range(2, 11, 2):
    
    print(number, end=' ')

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/ad559eaf-e860-4634-b407-4578a83e8f4f)

3. Write a program to calculate the sum of all numbers from 1 to 100 using a for loop.

**Code -**

total_sum = 0

for number in range(1, 101):
    
    total_sum += number

print("The sum of all numbers from 1 to 100 is:", total_sum)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/17e1734a-35af-4bc6-a6f0-75d09704e729)

4. Write a program to find the factorial of a given number using a for loop.

**Code -**

def factorial(n):
    
    result = 1
    
    for i in range(1, n + 1):
        
        result *= i
    
    return result

number = 5

print("Factorial of", number, "is:", factorial(number))

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/164f5fc9-f69d-4542-9556-64693aff458c)

5. Write a program to print the Fibonacci series up to a certain limit using a for loop.

**Code -**

def fibonacci(limit):
    
    first_num = 0
    
    second_num = 1

    print(first_num, end=" ")
    
    print(second_num, end=" ")

    for _ in range(2, limit):
        
        next_num = first_num + second_num
        
        if next_num > limit:
            
            break
       
        print(next_num, end=" ")
        
        first_num, second_num = second_num, next_num

fibonacci(50)

**Output**

  ![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/c6a81035-c65e-4315-806b-4d5167f321b4)

**While Loop**

1. Write a program to print the numbers from 1 to 5 using a while loop.

**Code -**

number = 1

while number <= 5:
    
    print(number)
    
    number += 1

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/092b4333-1d6a-42c3-bb8d-7aaf2c8a4ba0)

2. Write a program to print the even numbers between 1 and 10 using a while loop.

**Code -**

number = 2

while number <= 10:
    
    print(number, end=' ')
    
    number += 2

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/ab905c8a-cb36-4990-8e11-c200ee338418)

3. Write a program to calculate the sum of all numbers from 1 to 100 using a while loop.

**Code -**

total_sum = 0

number = 1

while number <= 100:
    
    total_sum += number
    
    number += 1

print("The sum of all numbers from 1 to 100 is:", total_sum)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/d02242f8-fdc3-4184-98f8-2ce329ce57b2)

4. Write a program to find the factorial of a given number using a while loop.

**Code -**

def factorial(n):
    
    result = 1
    
    while n > 0:
        
        result *= n
        
        n -= 1
    
    return result

number = 5

print("Factorial of", number, "is:", factorial(number))

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/1d0eb7e9-627c-4169-bfa6-bad6c434dd3a)

5. Write a program to print the Fibonacci series up to a certain limit using a while loop.

def fibonacci(limit):
   
    first_num, second_num = 0, 1

    print(first_num, end=" ")
    
    print(second_num, end=" ")

    while True:
        
        next_num = first_num + second_num
        
        if next_num > limit:
            
            break
        
        print(next_num, end=" ")
        
        first_num, second_num = second_num, next_num

limit = 50

print("Fibonacci series up to", limit, "is:")

fibonacci(limit)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/09196b69-b64f-4983-8ca6-ae6706277871)

### Lambda Functions:

1. Write a lambda function to calculate the square of a number.

**Code -**

square = lambda x: x ** 2

number = 5

print("Square of", number, "is:", square(number))

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/720235bd-2d32-400e-8c6d-dc1bd0e4ae01)

2. Create a list of numbers and use a lambda function to filter out the even numbers.

**Code -**

numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

even_numbers = list(filter(lambda x: x % 2 == 0, numbers))

print("Original list of numbers:", numbers)

print("Even numbers:", even_numbers)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/7ea3a0ca-b4e1-4ee6-86d9-e9199d7e80c7)

3. Write a lambda function to find the sum of two numbers.

**Code -**

addition = lambda x, y: x + y

num1 = 5

num2 = 3

print("Sum of", num1, "and", num2, "is:", addition(num1, num2))

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/71f02040-69d3-44a7-9bb5-336f12343a7f)

4. Create a list of tuples containing student names and their corresponding scores. Use a lambda function to sort the list by scores.

**Code -**

students = [("Alice", 85), ("Bob", 90), ("Charlie", 75), ("David", 80)]

sorted_students = sorted(students, key=lambda x: x[1])

print("Sorted list of students by scores:")

for student in sorted_students:
    
    print(student)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/505ff84e-9bc0-4daa-a154-e8b2fcd01e31)

5. Create a list of strings and use a lambda function to sort them alphabetically.

**Code -**

strings = ["banana", "apple", "orange", "grape", "kiwi"]

sorted_strings = sorted(strings, key=lambda x: x.lower())

print("Sorted list of strings alphabetically:")

for string in sorted_strings:
    
    print(string)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/99fb7ab3-2b1f-4bd0-86b3-ac7308cbe8ba)

### UDF: Arguments and Parameters

1. Write a function called add_numbers that takes two numbers as input and returns their sum.

**Code -**

def add_numbers(num1, num2):
    
    return num1 + num2

result = add_numbers(5, 3)

print("The sum of 5 and 3 is:", result)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/f7dcd935-160d-4148-99e0-71fe04311fd2)

2. Create a function called is_even that takes a single number as input and returns True if it's even, otherwise False.

**Code -**

def is_even(number):
    
    return number % 2 == 0

number = 2

print("Is", number, "even?", is_even(number))

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/6f21eec4-88ec-42d0-8600-c90d6e978bd1)

3. Define a function called calculate_area that calculates the area of a rectangle given its length and width as input parameters.

**Code -**

def calculate_area(length, width):
   
    return length * width

length = 5

width = 3

area = calculate_area(length, width)

print("The area of the rectangle with length", length, "and width", width, "is:", area)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/9fb3657f-0ca0-4b0d-9cfb-6c8037f101a8)

4. Write a function called reverse_string that takes a string as input and returns its reverse.

**Code -**

def reverse_string(input_string):
   
    return input_string[::-1]

input_string = "hello"

reversed_string = reverse_string(input_string)

print("The reverse of", input_string, "is:", reversed_string)

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/7b1a566a-00f3-4cce-bd48-a7e19b1bf278)

5. Create a function called is_prime that takes a positive integer as input and returns True if it's prime, otherwise False.

**Code -**

def is_prime(number):
    
    if number <= 1:
        
        return False
    
    elif number == 2:
        
        return True
    
    elif number % 2 == 0:
       
        return False
    
    else:
        
        for i in range(3, int(number ** 0.5) + 1, 2):
           
            if number % i == 0:
                
                return False
        
        return True

number = 17

print("Is", number, "prime?", is_prime(number))

**Output**

![image](https://github.com/Swagath123Koyada/PythonFoundation/assets/164196153/ba958daf-18a1-459c-8064-b4247837cd6d)

