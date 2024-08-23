# Python tasks

You can add your solutions in this repo by cloning it, and creating a pull request. If correct, I'll merge them.

### Python Questions by Level

#### **Beginner Level**

1. **Print Statement**
   - **Question**: Write a Python program that prints "Hello, World!" to the console.
   
   __Expected Output__
   ```bash
   "Hello, World!"
   ```

2. **Basic Arithmetic**
   - **Question**: Write a Python function that takes two numbers as input and returns their sum.
   
   __Expected Output__
   ```bash
   "add_numbers(3,5):- 8"
   ```

3. **String Manipulation**
   - **Question**: Write a Python program that takes a string as input and prints it in reverse.
   
   __Expected Output__
   ```bash
   "Python:- nohtyP"
   ```

4. **Lists**
   - **Question**: Write a Python function that takes a list of numbers and returns the maximum number in the list.
   
   __Expected Output__
   ```bash
   "[3, 1, 4, 1, 5, 9]:- 9"
   ```

5. **Conditionals**
   - **Question**: Write a Python program that checks if a given number is even or odd.
   
   __Expected Output__
   ```bash
   "check_even_odd(7):- Odd"
   ```


6. **Loops**
   - **Question**: Write a Python program that prints the first 10 natural numbers using a `for` loop.
   
   __Expected Output__
   ```bash
   "1,2,3,4,5,6,7,8,9,10"
   ```

7. **Dictionary**
   - **Question**: Write a Python program that counts the occurrences of each word in a given sentence and stores the result in a dictionary.
   
   __Expected Output__
   ```bash
   word_count("this is a test this is only a test"):- {'this': 2, 'is': 2, 'a': 2, 'test': 2, 'only': 1}
   ```

8. **List Comprehension**
   - **Question**: Write a Python program that creates a list of squares of numbers from 1 to 10 using list comprehension.
   
   __Expected Output__
   ```bash
   [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
   ```

9. **Function with Default Argument**
   - **Question**: Write a Python function that greets a user with their name. If no name is provided, it should greet "World".
   
   __Expected Output__
   ```bash
   greet():- Hello, World! 
   greet("Alice"):- Hello, Alice!
   ```

10. **Basic File I/O**
    - **Question**: Write a Python program that writes "Hello, World!" to a file named `hello.txt`.
    
    __Expected Output__
    ```bash
    Hello, World!
    ```

#### **Intermediate Level**

1. **List Manipulation**
   - **Question**: Write a Python program that takes a list of numbers and returns a new list with only the even numbers.
   
   __Expected Output__
   ```bash
   [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]:- [2, 4, 6, 8, 10]
   ```

2. **Lambda Functions**
   - **Question**: Write a Python program that uses a lambda function to sort a list of tuples based on the second element.
   
   __Expected Output__
   ```bash
   ; This is an example
   [(4, 1), (5, 2), (1, 3)]
   ```

3. **Memory Profiling**
   - **Question**: Write a Python program that profiles the memory usage of creating a large list of numbers (e.g., 1 to 1 million) using the `memory_profiler` module.
   
   __Expected Output__
   ```bash
   ; Just an example not the actual code
   Line #    Mem usage    Increment   Line Contents
    ================================================
     4     35.812 MiB     35.812 MiB   @profile
     5                             def create_large_list():
     6    311.562 MiB    275.750 MiB       large_list = [i for i in range(1, 1000001)]
     7    311.562 MiB      0.000 MiB       return large_list

   ```

4. **Code Execution Time Calculation**
   - **Question**: Write a Python program that calculates the time it takes to sum a list of 1 million numbers using the `time` module.
   
   __Expected Output__
   ```bash
   Sum: 500000500000, Time taken: 0.0xxx seconds
   ```

5. **Decorators**
   - **Question**: Write a Python decorator that prints "Function started" before a function runs and "Function ended" after it completes.
   
   __Expected Output__
   ```bash
   Function started
   Hello!
   Function ended
   ```

6. **List to Dictionary Conversion**
   - **Question**: Write a Python program that converts two lists into a dictionary, where one list contains the keys and the other contains the values.
   
   __Expected Output__
   ```bash
   {'name': 'Alice', 'age': 25, 'city': 'New York'}
   ```

7. **Exception Handling**
   - **Question**: Write a Python function that attempts to divide two numbers and handles the exception if the denominator is zero.
   
   __Expected Output__
   ```bash
   Error: Division by zero is not allowed
   ```

8. **List Flattening**
   - **Question**: Write a Python function that flattens a nested list (e.g., `[[1, 2], [3, 4], [5, 6]]` to `[1, 2, 3, 4, 5, 6]`).


9. **Class Inheritance**
   - **Question**: Write a Python program that creates a base class `Animal` with a method `speak` and a subclass `Dog` that overrides the `speak` method.
   
   __Expected Output__
   ```bash
   my_dog.speak():- Woof!
   ```

10. **Working with JSON**
    - **Question**: Write a Python program that reads a JSON file and prints its contents to the console.
   
    __Expected Output__
    ```bash
    {"name": "Alice", "age": 25, "city": "New York"}
    ```
    

#### **Advanced Level**

1. **Generators**
   - **Question**: Write a Python generator function that yields Fibonacci numbers up to a certain number.

   __Expected Output__
   ```bash
   for num in fibonacci(100): print(num):- 
    0
    1
    1
    2
    3
    5
    8
    13
    21
    34
    55
    89
   ```

2. **Multithreading**
   - **Question**: Write a Python program that demonstrates the use of multithreading to print numbers and letters simultaneously.

   __Expected Output__
   ```bash
    1
    A
    2
    B
    3
    C
    4
    D
    5
    E
   ```

3.  **Memory Managemen** 
    - **Question:** Write a Python program that demonstrates manual memory management by creating a large list and then using the gc module to force garbage collection. The program should display memory usage before and after the garbage collection process.

    __Expected Output__
    ```bash
    Memory usage at start: 25.5 MB
    Memory usage before deletion: 410.5 MB
    Memory usage after deletion and garbage collection: 25.7 MB
    ```

