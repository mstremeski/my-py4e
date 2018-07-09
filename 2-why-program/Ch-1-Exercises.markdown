# Chapter 1 Exercises ([Source](https://www.py4e.com/html3/01-intro))

**Exercise 1: What is the function of the secondary memory in a computer?**

- [ ] a) Execute all of the computation and logic of the program
- [ ] b) Retrieve web pages over the Internet
- [x] c) Store information for the long term, even beyond a power cycle
- [ ] d) Take input from the user


**Exercise 2: What is a program?**

A program is a sequence of instructions (in this case, using the Python language), that tell a computer how to do something.


**Exercise 3: What is the difference between a compiler and an interpreter?**

Both compilers and interpreters take code and translate them into machine language for a computer to understand. But a compiler will take the entire code and translate it all together, usually creating an output file like a .dll or .exe file. On the other hand, an interpreter will parse one line of code at a time, allowing the computer to complete the instructions in that piece of code immediately. This makes the interpreter useful for quickly testing a section of code to make sure the computer parses it correctly.


**Exercise 4: Which of the following contains "machine code"?**

- [x] a) The Python interpreter
- [ ] b) The keyboard
- [ ] c) Python source file
- [ ] d) A word processing document


**Exercise 5: What is wrong with the following code:**
```python
>>> primt 'Hello world!'
  File "<stdin>", line 1
    primt 'Hello world!'
                       ^
SyntaxError: invalid syntax
>>>
```

`primt` was entered incorrectly. It should be `print` instead. Additionally, the text `'Hello world!'` needs to be inside parentheses for the `print()` function to work. The code should be:
```python
>>> print('Hello world!')
```


**Exercise 6: Where in the computer is a variable such as "x" stored after the following Python line finishes?**
```python
x = 123
```
- [ ] a) Central processing unit
- [x] b) Main Memory
- [ ] c) Secondary Memory
- [ ] d) Input Devices
- [ ] e) Output Devices


**Exercise 7: What will the following program print out:**
```python
x = 43
x = x + 1
print(x)
```
- [ ] a) 43
- [x] b) 44
- [ ] c) x + 1
- [ ] d) Error because x = x + 1 is not possible mathematically


**Exercise 8: Explain each of the following using an example of a human capability: (1) Central processing unit, (2) Main Memory, (3) Secondary Memory, (4) Input Device, and (5) Output Device. For example, "What is the human equivalent to a Central Processing Unit"?**

The central processing unit, main memory and secondary memory can all be compared to the human brain. Our brains can perform calculations and respond to instructions like the CPU. We have short-term memory, which is analogous to a computer's main memory, which temporarily holds information in order to perform some activity. Then we have long-term memory, which is like a computer's secondary memory. Those memories do not get discarded as soon as the brain activity (program) is performed. Rather, it can be retrieved even after we "reset" (go to sleep). As another example, secondary memory can be compared to humans' ability to record data. We can always retrieve a phone number if we have written it down, but we may forget it if it's only in our short-term memory.

Human senses are equivalent to input devices. The sensations of touch, smell, taste, sound and sight all send input information to our brains. As for output devices, any action we make with our bodies is an output from our brains. An obvious example would be words or sounds we make after our brains perform an action and send signals to the relevant muscles.


**Exercise 9: How do you fix a "Syntax Error"?**

The syntax error message will give some clues about how to solve the problem. There will be a line number, and the error will be either on the same line or earlier. This is the place to search for typos or missed syntax. Using a text editor that can parse Python, like Atom, can also make it easier to spot a syntax error as it will have colour-coded markup and possibly red underlined words that can show where unexpected text was encountered.
