# INTERVIEW PREPARE

Brief project description.

## Table of Contents

- [Fundamentals of Data Types in Programming with Python](#fundamentals-of-data-types-in-programming-with-python)
  - [Mutable and Inmutable Data Types](#mutable-and-inmutable-data-types)
- [Python Core Fundamentals](#python-core-fundamentals)
- [Object Oriented Programming Concepts](#object-oriented-programming-concepts)
- [Memory Management in Python](#memory-management-in-python)
- [Python Design Patterns](#python-design-patterns)
- [Network Concepts](#network-concepts)
  - [REST and RESTful](#rest-and-restful)
  - [HTTP, HTTPS](#http-https)
  - [UTP, UDP, TCP](#utp-udp-tcp)
- [Databases](#databases)
  - [Relational Databases](#relational-databases)
  - [Non-Relational Databases](#non-relational-databases)
- [SQL Principles](#sql-principles)
- [Database Normalization](#database-normalization)
- [Improving Queries](#improving-queries)
- [SOLID Principles](#solid-principles)
- [CAP Theorem](#cap-theorem)
- [ACID Principles](#acid-principles)

## Fundamentals of Data Types in Programming with Python

Data types are an essential concept in programming as they determine the kind of data that can be stored in a variable, how that data is stored in memory, and what operations can be performed on that data. In Python, a dynamically typed language, data types are assigned automatically based on the value assigned to a variable. Here are some fundamental data types in Python:

    1. Numeric Types:
        int: Represents integer numbers, e.g., 5, -10, 1000.
        float: Represents floating-point numbers (decimal numbers), e.g., 3.14, -0.25, 1.0.

    2. Text Type:
        str: Represents strings of characters, e.g., "Hello, World!", "Python".

    3. Boolean Type:
        bool: Represents boolean values, either True or False. Used for logical operations.

    4. Sequence Types:
        list: Represents ordered, mutable (changeable) sequences of elements, e.g., [1, 2, 3].
        tuple: Represents ordered, immutable (unchangeable) sequences of elements, e.g., (1, 2, 3).

    5. Mapping Type:
        dict: Represents key-value pairs, where keys are unique identifiers associated with values, e.g., {"name": "Alice", "age": 30}.

    6. Set Types:
        set: Represents an unordered collection of unique elements, e.g., {1, 2, 3}.
        frozenset: Similar to sets, but immutable.

    7. None Type:
        None: Represents the absence of a value or a null value.

Python provides ways to convert between different data types, allowing for flexibility in how data is manipulated and processed.

Here are some examples of using these data types:

```

# Numeric Types
num_integer = 5
num_float = 3.14

# Text Type
text_string = "Hello, Python!"

# Boolean Type
is_true = True
is_false = False

# Sequence Types
my_list = [1, 2, 3]
my_tuple = (4, 5, 6)

# Mapping Type
my_dict = {"name": "Alice", "age": 30}

# Set Types
my_set = {1, 2, 3}
my_frozenset = frozenset([4, 5, 6])

# None Type
no_value = None

```

Understanding these fundamental data types is crucial for effective programming in Python. They determine how data is stored, processed, and interacted with in your programs.

### Mutable and Inmutable Data Types

Mutable Data Types:

    list: Lists are ordered and can hold elements of different data types. They are mutable, which means you can change their content (add, remove, modify elements) after they are created.

Immutable Data Types:

    int: Integers are immutable, meaning their value cannot be changed after creation.
    float: Floating-point numbers are also immutable.
    str: Strings are immutable. Once a string is created, you cannot modify its characters directly.
    tuple: Tuples are immutable sequences, and their elements cannot be modified after creation.
    frozenset: Frozensets are similar to sets, but they are immutable.
    bool: Booleans are immutable; their values are either True or False.
    None: None is a special constant representing the absence of a value. It is immutable.

Note: The mutability or immutability of a data type affects how you can manipulate it. For mutable data types like lists and dictionaries, changes can be made directly to the object. For immutable types like strings, tuples, and integers, any change results in the creation of a new object rather than modifying the existing one.

Here's a small example to illustrate the difference between mutable and immutable types:

python

# Mutable Example
my_list = [1, 2, 3]
my_list[0] = 10
print(my_list)  # Output: [10, 2, 3]

# Immutable Example
my_string = "hello"
my_string[0] = 'H'  # This will result in an error since strings are immutable

Understanding the mutability and immutability of data types is crucial for managing data efficiently and avoiding unexpected behavior in your programs.

## Python Core Fundamentals

Exploring core concepts of the Python programming language.

## Object Oriented Programming Concepts

Understanding the principles of Object-Oriented Programming (OOP) and their implementation in Python.

## Memory Management in Python

An overview of memory management in Python, including garbage collection and memory optimization techniques.

## Python Design Patterns

Exploring common design patterns used in Python programming.

## Network Concepts

Explaining network concepts like REST, RESTful, HTTP, HTTPS, UTP, UDP, TCP, and more.

### REST and RESTful

Introduction to the concepts of REST and building RESTful APIs.

### HTTP, HTTPS

Understanding the HTTP and HTTPS protocols for communication over the web.

### UTP, UDP, TCP

Exploring different transport layer protocols: UTP, UDP, and TCP.

## Databases

An overview of different types of databases and their characteristics.

### Relational Databases

Exploring relational database concepts, SQL, and relational data modeling.

### Non-Relational Databases

Introduction to non-relational databases, their types, and use cases.

## SQL Principles

Understanding SQL principles for querying and manipulating databases.

## Database Normalization

Explaining the importance of database normalization and different normalization forms.

## Improving Queries

Techniques to optimize and improve database queries for better performance.

## SOLID Principles

Understanding the SOLID principles of object-oriented design and their application.

## CAP Theorem

Exploring the CAP theorem in distributed systems and its implications on system design.

## ACID Principles

Understanding the ACID principles for ensuring database transaction integrity.
