[Back to Syllabus](/README.md#course-syllabus)

## 2.0.1 Iota - Why Should I Take this Module?

- Hi! Me again. I hope you are excited about programming, but if you aren’t, I get it. Programming can seem daunting, but in fact, it’s easy to learn the foundations and I’m here to help. Because when you know some simple programming, you can get Things in the IoT do what you want them to do. This module lays out some of the basics, but trust me, you will not have to become an expert programmer to make things happen in the IoT

## 2.0.2 What Will I Learn in this Module?

- Use Blockly and Python to create simple programs

![image](https://user-images.githubusercontent.com/29455975/186407324-bd05a218-c78c-465e-883e-264da521f430.png)

## 2.1.1 Check Your Understanding - Follow the Flowchart

- Look closely at this flowchart. Use it to answer the three questions below. Click the pin icon in the upper right corner of the flowchart to see a smaller version

## 2.1.2 Flowcharts

- Flowcharts are used in many industries including engineering, physical sciences, and computer programming where a complete understanding of processes or workflows is required. Flowcharts are diagrams that are used to represent these processes or workflows
- Flowcharts illustrate how a process should work. Flowcharts should not require complex, industry-specific terminology or symbols. A flowchart should be easy to understand without having to be an expert in the chosen field
- Flowcharts should show input states, any decisions made, and the results of those decisions. It is important to show the steps that should be taken when the result of a decision is either yes or no
- It is common for programmers to create a first draft of a program in no specific programming language. These language-independent programs are focused on the logic rather than in the syntax and are often called algorithms. A flowchart is a common way to represent an algorithm. An example of a flowchart is shown in the figure

## 2.1.3 System Software, Application Software, and Computer Languages

- There are two common types of computer software: system software and application software
- Application software programs are created to accomplish a certain task or collection of tasks. For example, Cisco Packet Tracer is a network simulation program that allows users to model complex networks and ask “what if” questions about network behavior
- System software works between the computer hardware and the application program. It is the system software that controls the computer hardware and allows the application programs to function. Common examples of system software include Linux, Apple OSX, and Microsoft Windows
- Both system software and application software are created using a programming language. A programming language is a formal language designed to create programs that communicate instructions to computer hardware. These programs implement algorithms which are self-contained, step-by-step sets of operations to be performed
- Some computer languages compile their programs into a set of machine-language instructions. C++ is an example of a compiled computer language. Others interpret these instructions directly without first compiling them into machine language. Python is an example of an interpreted programming language. An example of Python code is shown in the figure
- When the programming language is determined and the process is diagrammed in a flowchart, program creation can begin. Most computer languages use similar program structures

```
year = int(input("Enter a year to check if it is a leap year\n"))
if (year % 4) == 0:
    if (year % 100) == 0:
        if (year % 400) == 0:
            print("{0} is a leap year".format(year))
        else:
            print("{0} is not a leap year".format(year))
    else:
        print("{0} is a leap year".format(year))
else:
    print("{0} is not a leap year".format(year))
```

## 2.1.4 Programming Variables

- Programming languages utilize variables as dynamic buckets to hold phrases, numbers, or other important information that can be used in coding. Instead of repeating specific values in numerous places throughout the code, a variable can be used. Variables can hold the result of a calculation, the result of a database query, or some other value. This means that the same code will function using different pieces of data without having to be rewritten
- For instance “x + y = z” is an example of a programming expression. In this expression, x, y and z are variables which can represent characters, character strings, numeric values or memory addresses
- A variable can refer to a value. For instance the expression “a = 10” associates the value 10 to variable a
- A variable can also represent a memory location. The expression “a = 10” represents that the value 10 is stored in some location of the computer memory, which is referred to as ‘a’

- Variables can be classified into two categories:
    - Local Variables -These are variables that are within the scope of a program / function / procedure
    - Global Variables -These are variables that are in the scope for the time of the program’s execution. They can be retrieved by any part of the program

- Variables allow programmers to quickly create a wide range of simple or complex programs which tell the computer to behave in a pre-defined fashion


## 2.1.5 Basic Program Structures
- People impart logic to computers through programs. Using specific logic structures, a programmer can prepare a computer to make decisions. The most common logic structures are:

- IF – THEN - This logic structure allows the computer to make a decision based on the result of an expression. An example of an expression is myVar > 0. This expression is true if the value stored in the myVar variable is greater than zero. When an IF-THEN structure is encountered, it evaluates the provided expression. If the expression is false, the computer moves on to the next structure, ignoring the contents of the IF-THEN block. If the expression is true, the computer executes the associated action before moving on to the next instruction in the program

- This example code prints "Value1 is greater than Value2" on the screen, if the expression value1 > value2 is true
```
if (value1 > value2):
    print("Value1 is greater than Value2.")
```

- FOR Loops - These are used to execute a specific set of instructions a specific number of times, based on an expression. The term loop comes from the fact that the set of instructions is executed repeatedly. While the syntax of FOR loops varies from language to language, the concept remains the same. A variable acts as a counter inside a range of values identified by a minimum and a maximum. Every time the loop is executed, the counter variable is incremented. When the counter is equal to the defined maximum value, the loop is abandoned and the execution moves on to the next instruction

- This example code prints "counter = N" (where N is the value of the counter variable "i"
```
i=0
for i in range(0, 100):
    print("counter =",i)
    i = i + 1
```
- The message is printed 100 times on the screen

- WHILE Loops –These are used to execute a specific set of instructions while an expression is true. Notice that often the instructions inside the loop will eventually make the expression evaluate as false

- This example code prints "Value is still less than 10" on the screen while value < 10. Notice that the program also increments value every time the WHILE loop is executed
```
while value < 10:
    print("Value is still less than 10")
    value = value + 1
```

## 2.1.6 Check your Understanding - Programming Language Concepts

- Check your understanding of programming language concepts by choosing the correct answer to the following questions

- 7 Quiz

## 2.1.7 Check your Understanding - Identify Programming Terms

- Matching. Select from lists and then submit
- Look closely at the flowchart and select the appropriate term in each dropdown menu. Then click Submit

## 2.1.8 Lab - Create a Process Flowchart

- Flowcharts are normally used to diagrammatically illustrate the process flow before a computer program is created. In this lab you will create a simple flowchart showing the process used to find a predetermined integer value

![image](https://user-images.githubusercontent.com/29455975/186410461-d1b8f11f-d49a-48b0-9c65-8d23ced306fc.png)

## 2.2.1 What is Blockly?

- Blockly is a visual programming tool created to help beginners understand the concepts of programming. By using a number of block types, Blockly allows a user to create a program without entering any lines of code

- A Blockly Program

![image](https://user-images.githubusercontent.com/29455975/186410859-e2de39fb-55fb-455d-8de1-3bc9ae460d30.png)


- Blockly implements visual programming by assigning different programming structures to colored blocks. The blocks also contain slots and spaces to allow programmers to enter values required by the structure. Programmers can connect programming structures together by dragging and attaching the appropriate blocks. Programming structures such as conditionals, loops, and variables are all available for use

- Creating a new variable in Blockly is a simple matter of dragging the variable block onto the work space and filling in the value slot. It is also possible to change the contents of a variable as the program is being executed

- VAR1, a Blockly variable created and assigned the value of 5

- A Blockly Variable
    - Blockly also supports functions. Similar to the variables, Blockly has specific blocks to represent functions. Also similar to variables, programmers simply select and drag function blocks to the work space and fill in the required slots
    - Notice that the variable block and the print block both have a bevel tab on the bottom and a slot on the top. This means that the two blocks can be snapped together to create a program sequence. Blockly will execute the block on top first, then move on to the block below it
    - Other blocks are available such as an IF THEN block, a WHILE block and a FOR block. There are also blocks specifically for sensors and actuators
    - Blockly can translate its block-based code into Python or JavaScript. This is very useful to beginner programmers

## 2.2.2 Blockly Games

- This is an animations player component
    - Google provides a series of free and open source educational games that can help you learn programming. The series is called Blockly Games
    - To learn more about Blockly Games, or to try it yourself, go to https://blockly.games
    - There are a number of levels to complete to help you get started. Blockly may look like a toy, but it is a great tool to improve your logical thinking skills, which is one of the building blocks of computer programming

## 2.2.3 Packet Tracer - Blinking an LED Using Blockly

- Cisco Packet Tracer has incorporated Blockly as one of the programming languages available in its IoT functionality. In this lab you will do the following:

    - Part 1: Open Packet Tracer and Examine Blockly Program for LED Blinking
    - Part 2: Control a RGB LED using Blockly

## 2.3.1 What is Python?

- Python is a very popular language that is designed to be easy to read and write. Python’s developer community adds value to the language by creating all types of modules and making them available to other programmers

- The core philosophy of the language is summarized by the document The Zen of Python:

*Beautiful is better than ugly<br>
Explicit is better than implicit<br>
Simple is better than complex<br>
Complex is better than complicated<br>
Readability counts*<br>

- Despite the fact Python is designed to be easy, there is still a learning curve. To make it easier to learn Python, a beginner can use Blockly to enhance his or her Python understanding
- Beginners can use Blockly to easily create a language-independent program, export it as Python code and use this newly created code to learn about Python syntax, structure and semantics

- Guessing Game in Python
```
import random

guess = None
picked_num = None

guess = 1
print("I will think of a number between 1 and 10 and you should guess it.")
picked_num = random.randint(1, 10)
while guess != picked_num:
         guess = int(input("guess what number I just picked? "))
print("Congrats, you just guessed my number!")
```

## 2.3.2 The Python Interpreter

- Python is an interpreted language; therefore, an interpreter is required to parse and execute Python code. The Python interpreter understands and executes Python code. Python code can be created in any text editor and Python interpreters are available for many operating systems. Python developers can create and deploy Python programs in practically any operating system
- On Linux machines, the Python interpreter is usually installed in /usr/bin/python3. With the Windows Python installer, Python is installed by default into the user’s home directory. In older Windows machines, Python is often placed in C:\PythonXX (where XX is the version of Python). After the Python interpreter has been installed, it operates somewhat like the Linux shell. This means that when called with no arguments, it reads and executes commands interactively. When called with a file name argument or with a file as standard input, it reads and executes a script from that file
- To start the interpreter, simply type python3 at the shell prompt
- Some legacy systems are still running Python 2. However, the final version of Python 2 was released in October of 2000. Python 3 should be considered the current standard. This course is built on Python 3 code. The Python version is printed on the first line when the interpreter is launched

- Python Interpreter Welcome Message
```
Python 3.6.5 (default, Apr 16 2018, 15:31:49)
[ GCC 4.8.5 20150623 (RED Hat 4.8.5-16) ] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

- When the Python interpreter is called with no arguments, and commands are entered via the keyboard, the interpreter is said to be in interactive mode. In this mode, the interpreter waits for commands. The primary prompt is represented by three greater-than signs (>>>). Continuation lines are represented by three dots (...). Continuation is the default secondary prompt
- The >>> prompt indicates the interpreter is ready and waiting commands

- IF-THEN Block
    - Continuation lines are needed when entering multi-line code.

- IF-THEN Block
```
>>> the_world_is_flat = True
>>> if the_world_is_flat:
...     print ("Be careful! not to fall!")
...
Be careful! not to fall!
```

- Another way of using the interpreter is python3 -c command [arg] ... which executes the statement(s) in the command. Because Python statements often contain spaces or other characters that are particular to the shell, it is suggested to enclose the entire command between single quotes

## 2.3.3 Variables and Basic Statements in Python
- The interpreter receives and executes statements interactively
- The interpreter acts as a simple calculator. You can type an expression on it and it will write the value. Expression syntax is straightforward. The operators +, -, * and / work just as they do in most other languages (for example, Pascal or C). Parentheses (()) can be used for grouping
- Grouping with Parentheses
```
>>>
>>> 25+ 25
50
>>> 70 + 7*6
112
>>> (50 - 5.0*6) / 4
5.0
```

- Python’s interactive mode implements the special variable “_” to hold the result of the last expression issued
- Use of a Special Variable
```
>>> tax = 12.5 / 100
>>> price = 100.50
>>> price * tax
12.5625
>>> price + _
113.0625
>>> round(_, 2)
113.06
```

- Variables are labeled memory areas that are used to store runtime program data. To assign values to variables in Python, use the equal to (=) sign. No result is displayed before the next interactive prompt
- Variable Assignment and Usage
```
>>> birth_year = 1941
>>> curr_year = 2016
>>> curr_year - birth_year
75
```

- Attempts to use a not defined variable (no assigned value), will result in an error.
- Undefined Variable Error
```
>>>
>>> my_new_variable
Traceback (most recent call last):
        File "<stdin>", line 1, in
NameError: name 'my_new_variable' is not defined
>>>
```

- Strings, which are defined as a sequence of characters, can also be handled by interactive mode. Use the backslash character (\) to escape characters. As an example, a string value uses double quotes but also contains double quotes within the string. If the string is entered as follows: "I really "need" this.". Python will get confused and think that the first double quote within the string actually ends the string. If you place a backslash (\) before the double quotes as follows: "I really \"need\" this", the backslash (\) causes Python to escape or ignore the character that follows
- Single quotes or double quotes can be used to wrap strings
- Use of Quotes to Wrap Strings
```
>>>
>>>'spam eggs' # single quotes
'spam eggs'
>>> 'doesn\'t' # use \' to escape the single quote...
"doesn't"
>>> "doesn't" # ...or use double quotes instead
"doesn't"
>>> '"Yes," he said.'
'"Yes," he said.'
>>> "\"Yes,\" he said."
'"Yes," he said.'
```

- The print statement prints the result of the expression it was given. It differs from just writing the expression you want to write (as we did earlier in the calculator examples) in the way it handles multiple expressions and strings. Strings are printed without quotes, and a space is inserted between items, so you can format things nicely
- String Output Formatting
```
>>>
>>> i = 256*256
>>> print ('The value of i is', i)
The value of i is 65536
```

- Functions are an important part of many programming languages. Functions allow for a block of code to be given a name and re-used as needed. The example code below defines a function that adds two numbers and prints the result
- A Function to Add Two Numbers and Print the Result

```
>>> # Function to add two numbers:
>>> def add_nums():
...      a = 5
...      b = 11
...      return a+b
...
>>> print (add_nums())
16
```

## 2.3.4 Useful Functions and Data Types in Python

- Python supports many useful functions and datatypes. Some of the more important ones are as follows:
- Range()
    - The range() function generates a list of numbers usually used to iterate with FOR loops. The example code shows use of the range() function
    - range(stop) - This is the number of integers (whole numbers) to generate, starting from zero
    - range([start], stop, [step]) – This is the starting number of the sequence, the ending number in the sequence, and the difference between each number in the sequence
- Range() Function Examples
```
>>> # One parameter
>>> for i in range(3):
...      print(i)
...
0
1
2
>>> # Two parameters
>>> for i in range(3,6):
...      print(i)
...
3
4
5
>>> # Three parameters
>>> for i in range(4, 10, 2):
...      print(i)
...
4
6
8
```

- Tuples
    - A tuple is a sequence of unchangeable Python objects. Tuples are sequences, separated by parentheses. The example shows the use of tuples
- Python Tuples Example
```
>>>
>>> tup1 = ('dancing', 'singing', 400, 1842);
>>> tup2 = (1, 2, 3, 4, 5, 6, 7 );
>>> print ('tup1[0]: ', tup1[0])
>>> print ('tup2[1:5]: ', tup2[1:5])

When the above code is executed, it produces the following result -
tup1[0]: dancing
tup2[1:5]: (2, 3, 4, 5)
```

- Lists
    - Lists are a sequence of changeable Python objects. Lists can be created by putting different comma-separated values between square brackets. The example code shows lists and how they can be updated
- Python List Examples
```
>>>
>>> list1 = ['car', 'train', 47, 2016];
>>> list2 = [1, 2, 3, 4, 5, 6, 7 ];
>>> print ('list1[0]: ', list1[0])
>>> print ('list2[1:5]: ', list2[1:5])

When the above code is executed, it produces the following result -
   list1[0]: car
   list2[1:5]: [2, 3, 4, 5]
```

```
>>>
>>> list = ['car', 'train', 47, 2016];
>>> print ('Value available at index 2 : ')
>>> print (list[2])
>>> list[2] = 2017;
>>> print ('New value available at index 2 : ')
>>> print (list[2])

When the above code is executed, it produces the following result -
   Value available at index 2 :
   47
   New value available at index 2 :
   2017
```

- Sets
    - Sets are unordered collections of unique elements. Common uses include membership testing, removing duplicates from a sequence, and computing standard set operations such as intersection, union, difference, and symmetric difference. The examples show the use of sets
- Python Sets Examples
```
>>>
>>> x = [1,2,3,1,2,3,1,2,3]
>>> set(x)
{1, 2, 3}
>>> y = [1, 1, 6, 6, 6, 6, 6, 8, 8]
>>> set(y)
{1, 6, 8}
>>> z = [("Bird", "Cat", "Dog", "Dog", "Bird", "Bird")]
>>> set(z)
{('Bird', 'Cat', 'Dog', 'Dog', 'Bird', 'Bird')}
```

```
>>> animals = set(["Cow", "Fish", "Pig", "Horse"])
>>> animals.add ("Cat")
>>> print (animals)
{'Pig', 'Cow', 'Cat', 'Fish', 'Horse'}
>>>
>>> for group in [animals]:
...    group.discard ("Fish")
...    print(group)
...
{'Pig', 'Cow', 'Cat', 'Horse'}
```

- Dictionaries
- A dictionary is a list of elements that are separated by commas. Each element is a combination of a value and a unique key. Each key is separated from its value by a colon. The entire dictionary is written within braces. Dictionary elements can be accessed, updated, and deleted. There are also many built-in dictionary functions such as a function that compares elements within different dictionaries and another that provides a count of the total number of elements within a dictionary. The examples show various dictionary operations
- Example Dictionary with Four Elements
```
>>> dict = {'Age' : 34, 'City' : 'Rome', 'Year' : 2016, 'Month' : 'March' }
>>> print ("dict['City']: ", dict['City'])
dict['City']: Rome
>>> print ("dict['Year']: ", dict['Year'])
dict['Year']: 2016
```

```
>>> dict['Year'] = 2015
>>> print ("dict['Year']: ", dict['Year'])
dict['Year']: 2015
```

- Add a New Element and Display the Number of Elements in a Dictionary Example

```
>>>
>>> dict['Sport'] = "Swimming"
>>> len(dict)
5
```

## 2.3.5 Programming Structures in Python

- Python includes a number of programming structures like other languages. Programming structures form the backbone of program logic

- IF-THEN Structures
- Similar to other languages, Python implements an IF-THEN structure. IF-THEN blocks can be used to allow the code to make decisions based upon the result of an expression, as shown in the example

- IF-THEN, ELSE, ELIF
```
>>> x = int(input("Please enter an integer: "))
Please enter an integer: 42
>>> if x < 0:
...      x = 0
...      print('Negative changed to zero')
...  elif x == 0:
...      print ('Zero')
...  elif x == 1:
...      print('Single')
...  else:
...      print('More')
...
More
```

- The example code performs a few tests and prints a message in accordance with the results of the test. Notice that Python also implements two sub-structures named ELSE and ELIF. ELSE allows the programmer to specify instructions to be executed if the expression is false. Short for ELSE IF, ELIF is used to perform a second test in case the first expression is false and another test is required. There can be zero or more ELIFs, and the ELSE part is optional

- FOR Loop Structure
- The FOR loop in Python iterates the items of any sequence (a list or a string), in the order that they appear in the sequence, as shown in the example
- FOR Loop
```
>>> # Measure some strings:
>>> words = ['cat', 'window', 'defenestrate']
>>> for w in words:
...     print (w, len(w))
...
cat 3
window 6
defenestrate 12
```

- WHILE Loop
- The WHILE loop executes a block of code if the expression is true. The example program uses a WHILE loop to calculate and print an initial sub-sequence of a Fibonacci series in which each number in the series is the sum of the previous two
- WHILE Loop
```
>>> # Fibonacci series:
>>> # the sum of two elements defines the next
>>> a, b = 0, 1
>>> while b < 10:
...     print (b)
...     a, b = b, a+b
...
1
1
2
3
5
```

- The third line contains a multiple assignment operator. The variables a and b get the new values of 0 and 1 in a single statement
- The WHILE loop calculates the next term in the Fibonacci series while the condition b < 10 is true. As in C, Python assumes any non-zero integer value as true and zero as false. The test used in the figure is a simple comparison
- Notice that the body of the loop is indented. This is also true of the statements within IF-THEN and FOR loop structures. Indentation is Python’s way of grouping statements. At the interactive prompt, you must type a tab or space(s) for each indented line or your code will not function properly and may encounter errors. More complicated input for Python should be done with a text editor. When a compound statement is entered interactively, it must be followed by a blank line to indicate completion (because the parser cannot guess which line will be the last line). Note that each line within a block must be indented by the same amount

## 2.3.6 Lab – Basic Python Programming

- In this lab you will use a virtual environment and the IDLE IDE to explore basic Python programming

## 2.3.7 Lab - Create a Simple Game with Python

- In this lab you will create a simple number guessing game using Python. This game is based on the flowchart created earlier

## 2.4.1 Defining Prototyping

- For prototyping in the IoT, it helps to have design skills, electronics skills, and physical/mechanical skills (working with your hands to put things together). Networking and programming skills are also extremely valuable. In addition, IoT developers also benefit from knowledge of cloud computing and network and device security
- Because the IoT is still developing, there are still unknown tasks to discover. This is a great time to invent something that is part of the IoT. Because the IoT combines people, process, data, and things, there is no end to the inventions that the IoT can help create and then incorporate

- Prototyping
    - Is fully functional, but not fault-proof
    Is an actual, working version of the product
    Is used for performance evaluation and further improvement of product
    Has a complete interior and exterior
    May be relatively expensive to produce
    In the IoT, is often used as a technology demonstrator

## 2.4.2 How to Prototype

- This is an animations player component
- How do you prototype? There are a few ways to get started. A team at Google used the “Rapid Prototyping Method” to create the Google Glass. Search the internet for “google glass rapid prototype ted talk” to view a video about the Google approach to prototyping
- Of course, Google has many resources to pay for the people and materials that go into prototyping. Most of us need some financial help to get our ideas out of our heads and into a prototype. For us, there is crowd funding. Kickstarter, Indiegogo, and Crowdfunder are just three of the many online crowd funding programs. Search the internet for “Pebble Time Kickstarter Video.” This online video was used to generate donations to help this group of inventors create the Pebble Time smartwatch
- What IoT invention will you create?

## 2.5.1 Physical Materials

- A good place to start is the internet, of course. People have exchanged ideas for ages, but the internet allows for idea exchanges on a whole new level. People who have never physically met can now collaborate and work together. There are several web sites you can visit to connect with other makers
- Maker Media is a global platform for connecting makers with each other to exchange projects and ideas. The platform also provides a place where makers can find and buy products for their projects. For more information, search the internet for Makezine
- It is helpful to have practical skills when working with certain materials. For example, wood and metal are common prototyping materials, but they may be too difficult for a beginner to use. You might be surprised with what you can do with plastic, clay, paper, and wires. Search Google for more information or ideas on how to work with the different prototyping materials
- Meccano, or Erector Set, is a model construction system that consists of reusable metal strips, plates, angle girders, wheels, axles, and gears, with nuts and bolts to connect the pieces. It lets you build working prototypes and mechanical devices. Search the internet for Mecanno to learn more
- 3D printing is the process of making a solid object based on a 3D model computer file. A machine, called a 3D printer, is connected to the computer. Many companies now build and sell 3D printers. Go to Makerbot on the internet to learn more about one 3D printer manufacturer

## 2.5.2 Electronic Toolkits

- Computer programs cannot run without a computer. While you can create programs for almost any computer, some platforms are designed for the beginner. Below you will find some of the most popular platforms
- Arduino is an open-source physical computing platform based on a simple microcontroller board, and a development environment for writing software for the board. You can develop interactive objects that take input from a variety of switches or sensors to control lights, motors, and other physical objects. Go to Arduino at http://arduino.cc
- While the Arduino is not suitable for use as a computer, its low power requirement makes it capable of controlling other devices efficiently
- The Raspberry Pi is a low cost, credit-card-sized computer that plugs into a computer monitor or TV. You operate it using a standard keyboard and mouse. It is capable of doing everything a computer can do, from browsing the internet and playing high-definition video, to making spreadsheets, word-processing, and playing games. Go to Raspberry Pi at http://www.raspberrypi.org
- The Beaglebone is very similar to the Raspberry Pi in size, power requirements, and application. The Beaglebone has more processing power than the Raspberry Pi; therefore, it is a better choice for applications with higher processing requirements. Go to Beaglebone at http://beagleboard.org
-  Finally, Adafruit is a fantastic resource for your IoT projects. They offer a wide variety of electronics components and kits. In addition, the Adafruit website includes many guides on electronic project development that are relevant to students learning about the IoT

## 2.5.3 Programming Resources

- Programming is critical to the IoT. Creating custom code is very useful when developing an IoT solution. You have already learned about Blockly and Python. There are many other free resources that can help you develop your programming skills
- The MIT OpenCourseWare (OCW) is a web-based publication of almost all MIT course content. Open and available to the world, OCW is a great place to get familiar with computer programming for free. OCW programming related courses can be found at http://ocw.mit.edu/courses/intro-programming
- Khan Academy is a non-profit educational website created in 2006 to provide “a free, world-class education for anyone, anywhere”. The lectures related to computer programming can be found at https://www.khanacademy.org/computing/cs
- Code Academy is another excellent resource. It relies on interactivity to help people learn how to write computer programs. You can find them at http://www.codeacademy.com

## 2.5.4 Community Inventor and Entrepreneurship Workshops

- So, perhaps you have just created something really great. What now? There are a number of places where you can get help exposing your idea or prototype to others
- Investigate what is available in your community. Check with your local government, schools, and chamber of commerce for information about workshops, classes, and expert advice
- The internet has many resources to help your idea get exposure. A good example is Quirky. Quirky allows users to share their ideas. When an idea is submitted, other Quirky users can vote and choose whether or not they want to support your idea. If an idea is good, it may become a real product. You can learn more about Quirky at https://quirky.com/about-quirky/

## 2.5.5 Iota - Reflection

- See? I told you! Basic programming doesn’t have to be difficult. It can actually be fun! I didn’t know that until I took this module. Now that you have created a process flowchart, and used Blockly and Python, you have some pretty powerful starting tools. What could you imagine making for the IoT? How could you get started with a simple prototype? It can be fun, like programming a remote-controlled toy that plays with your cat when you are not there. Or it could be lifesaving, like programming a thermal sensor for a newborn’s bed. I bet that once you have had just a little success with prototyping in the IoT, you will start to look at your world very differently

## 2.6.1 Everything Becomes Programmable Summary

- This module began by discussing how to apply basic programming to support IoT devices. Flowcharts are diagrams that are used to represent processes. There are two common types of computer software: system software and application software. Application software programs are created to accomplish a certain task. System software works between the computer hardware and the application program. Programming variables can be classified into two categories:
- Local Variables- These are variables that are within the scope of a program / function / procedure.
- Global Variables- These are variables that are in the scope for the time of the program’s execution. They can be retrieved by any part of the program

- The most common logic structures are IF – THEN, FOR Loops, and WHILE Loops
Blockly is a visual programming tool created to help beginners understand the concepts of programming. Blockly implements visual programming by assigning different programming structures to colored blocks
- Python is a very popular language that is designed to be easy to read and write. Python is an interpreted language; therefore, an interpreter is required to parse and execute Python code. Variables are labeled memory areas that are used to store runtime program data. Python supports many useful functions and datatypes including Range(), Tuples, Lists, Sets, Dictionary. Python also implements two sub-structures named ELSE and ELIF
- Next, the module detailed prototyping. Prototyping is the process of creating a rudimentary working model of a product or system. A team at Google used the “Rapid Prototyping Method” to create the Google Glass. The internet allows for idea exchanges on a whole new level 

- There are several web sites you can visit to connect with other makers:
    - http://makezine.com
    - https://www.makerbot.com
    - http://arduino.cc
    - http://www.raspberrypi.org
    - http://beagleboard.org
    - https://blockly-games.appspot.com/
    - http://ocw.mit.edu/courses/intro-programming
    - https://www.khanacademy.org/computing/cs
    - http://www.codeacademy.com
    - https://www.quirky.com

## 2.6.2 Everything Becomes Programmable Quiz

- 14 Quiz

[Go to Next Module](./3_Everything_Generates_Data.md)
