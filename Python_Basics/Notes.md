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


Module : 3
-----------

Type Casting :

Type casting means converting one datatype into another datatype.

x=10 
x='10'

    - Input comes as string 
    - API gives string numbers 
    - CSV filescontains text value 
    - Databse return diffrent type 


- Type of type casting 

    - Implicit type casting 
        - Python automatically converts smaller datatype ---> Larger datatype 

        spark_count=100
        avg=5.5 
        result=spark_count*avg 


    - Explicit type casting 
        - You convert datatype using functions.

        casting function 

        - int() 
        - float() 
        - str()
        - list()
        - tuple()
        - set()
        - dict()
        - bool()

    x="100" # str 
    y=int(x) # int 

    price="99.9"
    y=float(price)

    age=30
    text=str(age)

    name="Hello"
    print(list(name)) - ['h','e','l','l','o']


    Boolean casting 
    --------------

    Value                           bool() result 

    0                               False 
    ""                              False 
    []                              False 
    {}                              False 
    None                            False 
    Anything                        True 

    bool-->int---> float---> complex 


    print(True+2.5) # 3.5

    print(5+2.0) # float 

    "10" +5 # Error 


Module 4: Operator :

Operator: Symbole used to perform operations on values (Operands)

a=10
b=5
print(a+b)

Types of operators :

    - Aithmatic operator 
        - operators             Meaning 
            +                   Addition 
            -                   Substraction 
            *   
            /                   Division 
            //                  Floor Division # Divide two numbers . It removes the        decimal part rounding downward(towards negative infinity)

            %                   Modulus # Return remainder after division 
            **                  Power 

        a=10 
        b=3 
        print(a+b)
        print(a-b)
        print(a*b)
        print(a//b)
        print(a%b)
        print(a**b)
    - Comparsion operator 
        - operators             Meaning 
            ==                  equal 
            !=                  not equal
            >                   Greter 
            <                   Less
            >=                  Greater equals 
            <=                  Less Equals 

            age=30 
            print(age>18) # true 

            if row_count>0
                print("file loaded")

    - Assingment opertor 

        - x=10 Assign the value 

        += 
        -=
        *=
        /= 

        x=10
        x+=5
        print(x)
    - Logical Operator 

        - Operator              Meaning 
            and                 Both true 
            or                  any true
            not                  reverse 


    - Bitwise operator 
         Operator              Meaning 
            &                   AND 
            |                   or 
                                XOR 
            ~                   NOT 
            <<                  Left shift
            >>                  Rigjt shift 


    - Membership operator 
        Operator              Meaning 
            in                  exists 
            not in              not exists 

            tech =["python","spark"]
            print("python" in tech)



    - Identity Operators 
    Identity opertors are used to check whether two varibales refer to the same object in memeory, NOT whether thrie values are equal 

         Operator              Meaning 
            is                  same object # Both variables points to same memeory location
            is not              diffrent object  # Variables points to diffrent memory location



    Quick Comparision :
                                            Use cases 
        ==      Value Equality               Comapre data 
        is      Memory identity             Compare identity 
        is not  Diffrent object             Refrence validation 



    