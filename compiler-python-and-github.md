# Computers and programming

## Compilers

Computers are electronic equipment that only understand instructions given to them in _o_ and _1_, also known as _binary_. So, any instruction that we want to give a computer is expressed in the form of what is called a _[low-level language](https://en.wikipedia.org/wiki/Low-level_programming_language)_.

It is not easy to understand _low-level language_. We humans use words and numbers that mean something and follow certain grammar rules. This type of language that we can read (aka human-readable language) is a _[high-level language](https://en.wikipedia.org/wiki/High-level_programming_language)_.

When we program something, we write some instructions for the computer to execute. For example, the "_Hello, World!_" example in Python was

    print("Hello, World!")

You can kind of read and understand that you are asking the computer to print the string "Hello, World!". So, this is _high-level language_. But computer cannot understand this, and only can understand _low-level language_. So, we need someone who can translage our high-level instruction into low-level language for the computer to understand. This is the job of a [compiler](https://en.wikipedia.org/wiki/Compiler). So the programming languages that we use, e.g., C, C++, Python, Java, Javascript - all need their language-specific compilers. When we installed Python or Anaconda, we actually installed the compiler for Python also. 

## Programing Language

Programming languages are specifically-designed language for writing instructions to a computer with set of rules for grammar and syntax. If the language is _low-level_ then, it will be called a _low-level programming language_ and will not need a compuler. If the structure of the language (i.e., grammar and syntax) is _high-level_ then it is called a _high-level programming language_ and will need a compiler before it can be used for executing programs.

Python is one of many many _high-level programming languages_. Other examples include C, C++, Java, Fortran, etc.

### How to use programming languages

#### Stand-alone compiler

In principle, you can use any text editor to write set of instructions in a specific programming language. For example, you could write 

    print("Hello, World!")

in a file using Notepad in your computer. The key is then to use the correct compiler on the file you just created. 

In Python, we use the file extension _.py_ to indicate that the file contains program written in Python. So you can save your hello world instructions in a file named "_helloworld.py_". Then ask the Python compiler of your computer to read this file. This will be done as

    python helloworld.py

Name of the Python compiler here is simply _python_. So, essentially in the command above you are sending the _helloworld.py_ file to the _python_ compiler explicitly. The compiler will then read your high-level instruction and convert to low-level instruction for the computer and ask the computer to follow the instruction, i.e., print the words: "Hello, World!"

#### Alternatively,

There are other ways to achive this without actually writing inside a .py file. In this case, you can use an _ineractive shell_. The shell looks like a command prompt and has the Python compiler running behind it. So when you type your high-level instruction, it will automatically convert it to low-level and ask the computer to do the operations. It wil look something like this

    >>> print("Hello, World!")  <--- This is your instruction
    Hello, World!               <---- This is printed by the computer

#### Third way (recommended here)

Yet another way to do automatic, interactive compilation and running is via an _interactive notebook_. A notebook file is like a notebook, you can write text and code. When you write code in it, the notebook can interactively and automatically compile and execute it for you. A notebook file has an extension of _.ipynb_, that stands for Interactive Python NoteBook.


# Then what about Git and Github?

_Git_ is a version control system that can help keep track of your progress. And _github.com_ is simply a website that provides the functionalities of _git_.

Think of git and github as a storage that preserves history. We will be using this to store our progress in learning Python each day. But you can use this to store and track anything.

We will not spend much time on _git_ or _github_ other than how to navigate it for our purpose. 

However, once this summer experience is over, you will have all the codes and all the notes (including this one) in your github repository for any future reference.