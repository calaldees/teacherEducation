AI syntax error
===============

* To improve students awareness of AI tools, we need to model using them and critique the output
* Use AI in front of students - and together critique it's output
    * Show them how misleading and bad it is

```
I am learning python

Here is my program
a = 3
print("enter a number to add to 3")
b = input()
answer = a + b
print("the answer is " + answer)

Here is my error
enter a number to add to 35
Traceback (most recent call last):
  File "/mnt/c/Users/ac954/code/temp/test.py", line 4, in <module>
    answer = a + b
TypeError: unsupported operand type(s) for +: 'int' and 'str'

What does this mean?
```

```
The error you're encountering is a "TypeError," which means that there is a problem with the data types you are trying to use together in an operation. In this case, you are trying to add an integer (a) to a string (b), and Python doesn't allow direct addition between these two different data types.

Here's a step-by-step explanation of the issue and how to fix it:

    You have defined a as an integer with the value 3.
    You are using the input function to get user input, which is always received as a string. So, b is a string representing the number the user enters.

To fix the error and add the number entered by the user to a, you need to convert b from a string to an integer using the int() function. Here's the corrected code:

python

a = 3
b = input("Enter a number to add to 3: ")
# Convert the user input (which is a string) to an integer
b = int(b)
answer = a + b
print("The answer is " + str(answer))

With this modification, your code will first convert the user input to an integer before performing the addition, and then it converts the result back to a string for the print statement to work correctly.
```

```
I am 13 and new at this
in simple language - what should I remember in future
```

```
Absolutely, I'll simplify it for you:

    Data Types: Pay attention to the types of data you're working with. In Python, you have different types like numbers, strings, and more. Make sure you're using the right type for the task.

    Conversion: If you have a number as a string (like what input() gives you), and you want to do math with it, convert it to a number using int() or float().

    Errors: When you see an error message, read it carefully. It often tells you exactly what's wrong, like the "unsupported operand type(s) for +."

    Testing: Don't be afraid to experiment and try things out. Learning to code involves making mistakes, and that's perfectly fine. Mistakes help you learn.

    Ask for Help: If you get stuck, ask for help. You're never alone in your coding journey. There are lots of resources and people out there who can assist you.

Remember, coding is like learning a new language or a musical instrument. It takes time and practice, so don't get discouraged. Keep trying, keep learning, and you'll get better and better!
```


<details>

The answer chatGPT gave to the 13 year old is in no way useful to the level of learner.
* I might have ultra boiled it down to
    * "You can't do maths with letters"
        * problem is this sows the seeds of a "Deliberate [[misconceptions]]" because algebra is maths with letters/words
    * "You can't do maths with _words_"
        * See above
    * "You can't do maths with _strings_"
        * This is much better, but this only works if the learner knows the vocabulary correctly without any misconceptions
        * A string is an array/sequence of characters
        
</details>


* MetaCognition:
    * Pre Task
        * Overall goal "learning python"
        * The code (in full if small enough)
        * The error (in full)
        * What is this error Happening? how would I fix it?
    * Post Task
        * Left to their own devices - most students will move on to the next task (and probably get stuck again)
        * 


Students using this as part of normal use in class - e.g. like spell checker is used now.

---

Ask students
```
Int, Float or String
1
3
3.0
3.3333
10
01
23a
CT2 1CT (or the schools postcode)
2023
07980123456
3/12/2023
```

Related
-------

* [Investigating Novice Programmers' Interaction with Programming Environments](https://dl.acm.org/doi/10.1145/3304221.3325596) 2019
    * the feedback students receive from programming environments such as compiler error messages can be problematic. This work is aimed at better understanding the impact of these feedback mechanisms and working towards designing improved "novice-friendly" programming feedback 


[//begin]: # "Autogenerated link references for markdown compatibility"
[misconceptions]: misconceptions.md "Misconceptions"
[//end]: # "Autogenerated link references"