Module 1: Variable: 

A variable a name that stores a value in memory.

Name="Vamshi"
age=20
a=30

The name on left --> Variable 
The value on right ----> Data 


Python stores data in RAM and varible is just a label pointing to the data.


Rules for creating variables 
----------------------------

Valid Example 
-------------
name="Hello"
age=30
salary_12334=50000
useName="dev"

Invalid examples 
----------------
2name="wrong" # Cannot start with number 
user-name="no" # hyphen not allowed 
class ="Python" # keywords not allowed 

Naming Rules 
------------

Letters 
Numbers 
Underscore _

3. Types of variables (based on Assingment)

    - Single Assignment :
        x=10 

    - Multiple Assignment 
        a,b,c=10,20,30

    - Same value 
        x=y=z=100

4. Dynamic Typing 

    Python does not require datatype decalaration 
        x=10 # int 
        y="hello" # string 
        x= 3.4 # float 

    Internally : Python changes refrences to new object : Dynamically Types language 


    file_path:"s3://bucket.data.txt"
    row_count=400


    x=10 
    a="data"

    user_age=
    file_name=
    total_records=

Q. How python variables work internally ?


Module 2 : Datatype:

    Dataype tells python what kind of value is stored and what operations are allowd.

       x=10 # int 
        y="hello" # string 
        x= 3.4 # float 

    Why Datatype Matters?
        - Python needs to know 
            - How much memory to allocate 
            - Which operations are allowd 
            - How to process interanlly 

1. Main cqtegories of datatypes:
    - Immutable Datatypes 
    - Mutable Datatypes 

    Immutable Datatypes  ( Cannot change after creation)

        - Once created, Object cannot be modified if you change value - Python creates new object.

        - int 
        - float
        - bool 
        - str 
        - tuple 
    
    Mutable Datatypes ( Can change without new object)

        - list 
        - dict 
        - set 

    All Core Datatypes:

        - INTEGER (int)

            Whole number :
                a=10
                b=-5
                c=100000

        Python stores integers as object : 
            Small number (-5 tp 256) are cached.
                x=100
                y=100
                print(id(x),id(y))\
                
        Output : 4352227008 4352227008 # Same Memory

        x=300
        y=300
        print(id(x),id(y))  

        output: 4398811728 4398811984. # Diffrent Memory 


    