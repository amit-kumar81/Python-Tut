# What is a variable?
  Variable is like a container that holds data.For EX:-

  ```
  a = 1
  b = True
  c = "Harry"
  d = None
  ```
  These are four variables of different data types.

  # What is a Data Type?
  Data type specifies the type of value a variable holds.In python, we can print the type of any operator using type function:-

  ```
  a = 1
  print(type(a))
  b = "1"
  print(type(b))
  ```
  # There are two types of data types:-
   1. Primitive data types
   2. Non-primitive data types

  # Primitive data types:-
  1. __Numeric data types__: 
     * int: 3, -8, 0
     * float: 7.349, -9.0, 0.0000001
     * complex: 6 + 2i
       
  2. __Text data types__:
     * str: "Hello World!!!", "Python Programming"

  3. __Boolean data types__:
     * Boolean data consists of values True or False.

  4. __Sequenced data types__:
     * __List__: A list is an ordered collection of data with elements separated by a comma and enclosed within square brackets. Lists are mutable and can be modified after creation.For Ex:-
       ```
       list1 = [8, 2.3, [-4, 5], ["apple", "banana"]]
       print(list1)
       ```
       Output:-
       `[8, 2.3, [-4, 5], ['apple', 'banana']]`

     * __Tuple__: A tuple is an ordered collection of data with elements separated by a comma and enclosed within parentheses. Tuples are immutable and can not be modified after creation.For Ex:-
        ```
        tuple1 = (("parrot", "sparrow"), ("Lion", "Tiger"))
        print(tuple1)
        ```
        Output:-
       `(('parrot', 'sparrow'), ('Lion', 'Tiger'))`

  5. __Mapped data types__:
      * __dict__: A dictionary is an unordered collection of data containing a 
key:value pair. The key:value pairs are enclosed within curly brackets. For ex:-
       ```
     dict1 = {"name":"Sakshi", "age":20, "canVote":True}
     print(dict1)
     ```
     Output:- `{'name': 'Sakshi', 'age': 20, 'canVote': True}`
