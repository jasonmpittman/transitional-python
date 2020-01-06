---
title: Transitional Python  
subtitle: A Handbook for Students  
author: 
    - Jason M. Pittman
documentclass: scrartcl
rights: © 2007 Jason M. Pittman, CC BY-SA 4.0
---

\pagebreak

\tableofcontents

\pagebreak

# Preface

This book was born out of the need to help students transition from core programming coursework in another language, chiefly C++. In my opinion, when you’re coming from another language, you probably only need to be aware of where and how Python is different. That is, a long form text repeating in-common concepts, structures, and idioms is largely wasted trees.

Thus, you should think of this book as an organized collection of lecture notes. What I am providing here is not a complete treatment of how to program using Python. Rather, I am providing a synthesis or summary. Thus, I do not spend much time on common idioms you can find amongst languages. Instead, I attempt to draw attention to Python’s syntax and semantics which differ from C or C++.  However, you undoubtedly will need to fill in some gaps with external sources. My recommendations are as follows.

First, given that you have programming experience, try to leverage the concepts you know to draft what you think the same code may look like in Python. Then, look up the specific function in the Python documentation. As a last resort, use something like stackexchange.com or tutorialspoints.com to review specific examples.

Second, if for somereason you do not have programming experience, try to draft in English what you think the code ought to do. Then, look for examples by searching for the nouns or verbs in your English draft in conjunction with python. You can learn quite a bit about programming in general and Python in specific by looking at code examples.

Speaking of organization, this book has [n] chapters.

Lastly, one of the things I detest in programming books is the lengthy blocks of text, followed by formatted code example, followed by more blocky text. I don’t find such presentation of programming material compelling or conducive to learning. Accordingly, you will find code examples centrally located (just like this paragraph you’re reading now) with the explanation for the code over in the wide margin.

Regarding code example; yes, you should copy them. More so, you should read the code and make an educated guess as to what the code does.

A parting note about the margin text. Read it. Seriously, read it. Also, when a question appears you should answer it. Even better, read the question aloud and verbalize your answer. Trust me.

\pagebreak

# Chapter 1
## Tools
The place to start any programming course is with tools. In other words, what exactly do we need to get started? With Python, the answer is, very little. In fact, we only need two things regardless of what operating system we are using.

### Python interpreter
First, we need the Python language interpreter. I strongly recommend grabbing the latest stable version of Python 3. Pay attention here to what operating system you have as the interpreter needs to match. However, don’t worry about missing features or the like. One benefit of using a language like Python is the interpreter is operationally the same across all platforms.

Speaking of which, we should clarify how the interpreter works real quick. The Python interpreter compiles our source to bytecode and then executes the program in the Python virtual runtime environment. If you see a file with the “.pyc” extension, that is a compiled version of the source. With Python 3, these bytecode files are in the *__pycache__* directory.

The salient point here is the bytecode is not an equivalent to a compiled C or C++ binary. In fact, the bytecode is more similar to high-level languages such as Java or C# (.NET). That said, with Python, the compilation to bytecode has the benefit of speeding up subsequent runs of the program.

Further, the bytecode intermediary also has the benefit of making our Python programs truly cross platform. As long as a computing system has the interpreter installed, our program will execute exactly as intended.

### Text Editor

\pagebreak
# Chapter 2
## Syntax
Our second chapter is all about syntax.

### Whitespace

### Variables and Pointers

### Expressions

### Comprehensions

### Standard Library

\pagebreak
# Chapter 3
## Typing
You may have noticed something when we were examining variables in the previous chapter. Specifically, the *typing* of variables. While I think the concept of static versus dynamic types is easily grasped, there actually is a bit of technical depth here that warrants further discussion.

### Static and Dynamic

### Type Checking

\pagebreak
# Chapter 4
## Object-Orientation




