Misconceptions
==============

* See also
    * [[notional-machine]]
    * [[mental_models]]
    * [[knowledge_organisers]]

* TS 3.1 
    * > have a secure knowledge of the relevant subject(s) and curriculum areas, foster and maintain pupils’ interest in the subject, and address misunderstandings
* ITT CCF 3.3
    * > Anticipating common misconceptions within particular subjects is also an important aspect of curricular knowledge; working closely with colleagues to develop an understanding of likely misconceptions is valuable


* Hello World Issue 17: [Managing misconceptions](https://web.archive.org/web/20221210053521/https://helloworld.raspberrypi.org/articles/hw17-managing-misconceptions)
    * Types
        * Vernacular misconceptions
            * same words and phrases are associated with multiple concepts
            * e.g. belief that "the internet" and the "World Wide Web" are the same thing
        * Accidental misconceptions
            * accidentally introduced, simply by using common language or phrasing
            * e.g. use of the word ‘cloud’ is in this instance a paradox
        * Deliberate misconceptions
            * teachers sometimes introduce misconceptions deliberately, to make concepts more accessible
            * We simplify things for younger learners and have to refine/undo
    * Plan specific questions to expose and challenge misconceptions
        * Q: The internet was invented in the 1960s. When was the World Wide Web invented?
        * Q: When photos are saved to the cloud, where do they actually go?
        * Q: When you cannot access the internet, does that mean your WiFi is down?
    * Explore a range of pedagogies that focus on understanding as well as skills 
    * Use diagnostic questions, such as multiple-choice questions, and deliberately introduce the misconception as a possible answer

* The biggest Misconception of all ...
    * Using Google and as "Answer engine" not a "Search engine"
        * They are not the answers
    * Using AI to solve you're problem - you don't if it's right or not



Greg Wilson
* Novice misconception categories
    * Factual Errors
        * like believing that Vancouver is the capital of British Columbia (it’s Victoria). 
        * These are usually simple to correct.
    * Broken Models
        * like believing that motion and acceleration must be in the same direction.
        * We can address these by having novices reason through examples where their models give the wrong answer.
    * Fundamental beliefs
        * such as “the world is only a few thousand years old” or “some kinds of people are just naturally better at programming than others”.
        * These errors are often deeply connected to the learner’s social identity, so they resist evidence and rationalize contradictions.
        * Using Google and as "Answer engine" not a "Search engine"
            * They are not the answers
        * There is only one network that all devices connect to. It's called the internet. 
            * My desktop (via ethernet) and my mobile phone are on the same network
* > [Brow2017] also compared the mistakes novices actually make with what their teachers thought they made. They found that, 
    * > educators formed only a weak consensus about which mistakes are most frequent, that their rankings bore only a moderate correspondence to the students in the data, and that educators’ experience had no effect on this level of agreement
        * For example, mistaking = (assignment) and == (equality) wasn’t nearly as common as most teachers believed
    * Computing teachers SUCK at this



### TASK1: list misconceptions in computing (25min)
* Look at the GCSE spec and the NC
* Think (7min) - Generate your own list
* Pair (7min) - Combine with pair
* Share (12min) - Create omega list

(maybe skip to list below)



Research
--------

* [Exploring Programming Misconceptions: An Analysis of Student Mistakes in Visual Program Simulation Exercises](https://dl.acm.org/doi/10.1145/2401796.2401799) [dropbox pdf](https://www.dropbox.com/s/bar756coeuyn3b2/p19-sirkia.pdf?dl=0)
    * Teemu Sirkiä, Juha Sorva
    * Look at this % tables for the different categories of misconceptions
    * Misc1: Inverted assignment 38% `first = second` The student assigns the value of the left-hand variable to the right-hand side variable, rather than the other way around
    * UUhistle.org



CAS Misconceptions List
-----------------------

* CAS [Computing Misconceptions - Any Key Stage](https://www.computingatschool.org.uk/resources/2016/october/computing-misconceptions-any-key-stage)
    * This is just a first attempt at trying to categorise the misconceptions we see in our classrooms.

Copy&Paste from CAS article above
(notice how the teachers article has hunches and the research article has data)

### Variables

* writing code for statements like ‘x is equal to 3 or 4’ literally as ‘x == 3 or 4’ which causes headaches if using a language where the expression to the right of the Boolean operator has a Boolean interpretation.
* Value and variable are often swapped too eg 7 = x.
* the perennial problem of confusing assignment (=) with a test for equality (==). x=x+1 is utterly confusing in the mathematical terms children are familiar with.
* Assignment
    * foo="A"
    * bar="B"
    * foo=bar
    * //gives foo="B" and bar="B"
* Slicing a string removes characters from the original string.
* Lists and arrays are the same thing.
* Variables remain linked after assignment. a := 7; b := a; a := 13; What’s the value of b? Students with this misconception would answer 13. (This might be worse in languages that use an equals sign for assignment. After all, b = a seems to suggest these semantics…)
* Inverted assignment (first = second) - wrong way round
    * 5 = tries

### Logic
* thinking the inverse of x < y is x > y.
* Loops, functions, variables, classes don’t really exist. CPUs have no clue about any of these things, they exist only in the language translator and debugging.

### Sequence
* ‘sequence’ in Maths meaning a pattern and ‘sequence’ in Computing meaning an order
* Every line in Java / C / C# / C++ must have a semi colon at the end of it.
* if x == y: (execute then part even if false)

### Selection
* ELSE in selection needs a Boolean test of its own
* ELSE is always needed in a selection statement
* 1=="1" is True (not helped by the fact in some languages it is!)
* IF(A > 6 AND < 8) instead of IF(A > 6 AND A < 8)
* Language dependent IF (A = B) is the same as IF (A == B)
* Students insist on using: `If test=True Then`, rather than: `If test Then`

### Repetition
* where the student thinks that the `while CONDITION` will break when ever the condition stops being true, rather than at the boundary where it is checked.
* loops always exit from the bottom of the loop instead of where the loop control condition is evaluated.

### Subprograms

* Confusing a function call with a GOTO (this is terrible because it often kind of works with a few weird side effects)
* Returning False from function even though condition does not hold
* All subprograms must have a return statement
* not storing return value of function
* mixing up the direction in which data flows between subprograms that ask for user input or carry out some output. Data from the user should go out from the subprogram to the rest of the program not in. Data to the user should go in to the subprogram not out of it.
* Lots of my students (despite careful teaching to the contrary…) confuse a function returning a value with a procedure that outputs (i.e. prints) a value.

### Data Representation
* The length of a string is the number of chars in it, but string indexing is zero based. The length of CAT is 3, but the T is at index 2. (Some languages have settable origin 0 or 1)
* Assuming that all two’s complement numbers are going to be negative.
* assuming all hexadecimal numbers MUST have letters

### Technology
* That the best way to type a capital letter is the Caps Lock key :/
* Clock speed More cycles per second doesn’t automatically mean faster. Some CPUs do more in each clock cycle, or memory may not be able to keep up.
* USB == Memory Stick
* Input devices being something you put into the computer (i.e. anything that you can plug in, especially power).

### Networking
* pupils learn about a logical star network topology and assume this is how it is physically configured (i.e. a server sits in the middle and all nodes are directly connected to it).
* Peer-to-peer networks are believed to be a network topology, rather than a virtual network implemented at software layers
* WiFi connects you directly to the Internet…
* …and this connection is available anywhere you go.
* The class of an IP address dictates the subnet mask that must be used.
* servers are big computers
* Absolute misunderstanding of what Wifi is altogether, using it as a general term for their router at home.

### Web
* The title tag in HTML produces a title on the webpage itself.
* The HTML head element describes what appears at the top of a webpage.
* Conflating the Internet and World Wide Web.
* Confusing Web browser and search engine. Google being a browser
* Referring to HTML as a programming language/writing a program.

### Spreadsheet
* SUM in a spreadsheet means ‘add’ (as in maths) not ‘do a calculation’ [also =SUM(A1+A2) is a pet hate!]
* =SUM() being needed for any calculation in Excel.

### Computer Systems
* Processor cores execute multiple instructions at the same time (multitasking).
* Having more processor cores directly improves the runtime of a (single threaded) application
* Logic gates are discrete components not made of anything else (no knowledge of transistors)

### Security
* Hackers are magic
    * audio analysis of keypress's
    * RSA private key extracted from CPU high pitch whistle
* Computer Virus can be transmitted by touching usb drives together

### Other
* Compilers produce assembly code which is then converted to machine code
* Detecting errors is the same as correcting errors


TASK: Attempt to categorise some of th above with Greg Willsons categories of error
* Think - Pair - Share


My Hodge Podge Misconception list
---------------------------------

Parameter variable names and position - students don't understand they do not need to match
e.g.
```python
def thing(c, d):  # These do not have be called `i` and `j`
    print(f'{d}-{c}')
i = 3
j = 2
thing(i, j)
```

> are the characters you type the same as copy and paste?

* Wrong branch
    * Getting the `if (condition) {false bit} else {true bit}`
*execution function instead of defining it
* mismatched brackets - Brackets MUST match
* Wrong type of brackets (there are 4 different types of brackets - it's hard to even know where they are on the keyboard)
* Cannot comprehend 'i'ndentation' of blocks ... just can't .. can't even follow instructions. Simply does not understand what is even being said, or why it is being said. (TODO Stride? The Michal Koling Frame based editing)

```python
# use of if and else-if
score = 77
if score > 70:
  print("you rock")
if score > 50:
  print("you did ok .. I guess")
if score < 40:
  print("you fail")
```

* Case of strings
* > explicitly teach novices how to debug
    * > It is surprising how little page space is devoted to bugs and debugging in most introductory programming textbooks.
    * Develop Mental model of the steps
* BIGGEST PROBLEM!!!!!
* Compiler error pointing to 'misdirecting line' (it's actually caused by a problem a few lines up)
* Mass copy paste without understanding context (removing main method). Simply does not know enough about language to access the resources.

```python
a = [1,2,3]
b = [4,5,6]
c = a
print(c)
b = c
a.append(99)  # Does not need to be 'append'. Could be modify an index
print(c)
print(b)
# Where is [4,5,6]??? can we ever get it back?
b[:] = a
a.append(88)
print(b)
# Mutability!
# Params by reference
```

```
["fish", "hoarse", "shark", "polar bear"]
   [5] is "bear"
```


How do we detect misconceptions?
--------------------------------

If we suck so much at identifying misconceptions ...
Question/Discussion: How do we identify the misconceptions our students have?


<details>

* See [[notional-machine]] - describe how the internet works get them to write it
* [[mental_models]] [[knowledge_organisers]] linking concepts and summering
</details>



[//begin]: # "Autogenerated link references for markdown compatibility"
[notional-machine]: notional-machine.md "Notional Machine"
[mental_models]: mental_models.md "mental_models"
[knowledge_organisers]: knowledge_organisers.md "knowledge_organisers"
[//end]: # "Autogenerated link references"