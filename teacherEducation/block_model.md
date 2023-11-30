The Block Model
---------------

plan your (I)nvestigate questions

* [Block Model: an educational model of program comprehension as a tool for a scholarly approach to teaching](https://doi.org/10.1145/1404520.1404535) Schulte 2008
    * [The I in PRIMM](https://web.archive.org/web/20230322045228/https://helloworld.raspberrypi.org/articles/hw14-the-i-in-primm) Sue Sentence 2020
        * https://helloworld.raspberrypi.org/issues/14 Page 50

| | (T) Text Surface | (P) Program execution | (F) Function (relevance/intention) |
|-|-|-|-|
| (M) Macro structure | Understand the overall structure of the program text | Understand the algorithm underlying a program | Understand the goal/purpose the program in the current context |
| (R) Relationships | Relationships between blocks | Sequence of function calls, object sequence diagrams | Understand how sub-goals are related to goals |
| (B) Blocks | Regions of interest that build a unit (systematically or semantically) | Operation of a block or function | Understanding of the function of a block of code |
| (A) Atoms | Language elements | Operation of a statement | function of a statement |

Example
* (MF) "What would happen if the input to the program was ___"
* (RT) "Ask students to identify the scope of a variable"
* (RP) "Draw the flow of control on the program"
* (BT) "Ask students to draw on the program to identify blocks of code or types of construct"
* (BP) Ask: "What would happen if those two lines were the other way around?"
* (BP) Draw the flow of control
* (AF) Identify the purpose of a single statement

```python {.line-numbers}
answer = input("What is the best subject?")

if answer == "Computing":
    print("Correct! Well done!")
else:
    print("I'm afraid you must be mistaken.")
```
* (MF) What input would produce the output "Correct"
* (BT) What line does selection start on?
* (BP) Which line runs after line 3 when the input is "Music"?
* (AT) What is the condition in the code?
* (AF) What is the purpose of line 1 in the code

```python {.line-numbers}
print("Hi What's your name?")

name = "Turnip"

print("Hi " + name + "! How are you today?")
```


* TASK: Can you attempt to write 3 questions targeted at this following code:
    * https://github.com/calaldees/TeachProgramming/blob/master/teachprogramming/static/projects/data/elavation.py
    * Try to categorise the questions using the model above
    * Try to aim your questions at a range of these categories (e.g. not 3 questions about Atoms)

Higher Level Practical Example
--------------------

* https://github.com/calaldees/KaraKara/blob/master/docs/getting-started.md
* Possible use in professional engineering - pointing new developers at new code bases
    * An engaging pedagogy to allow new developers to explore the codebase and for seniors to point out interesting concepts/aspects of them, but in a super engaging way
    * (Friend that is a Senior dev at Facebook really likes the concept and may use the strategy with future projects at facebook)


Discussion
----------

* What is the purpose of the Block Model?
