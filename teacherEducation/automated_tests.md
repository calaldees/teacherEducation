Automated Tests (1 hour)
---------------

* Hello World [Self-marking Python resources](https://web.archive.org/web/20230127052824/https://helloworld.raspberrypi.org/articles/hw19-self-marking-python-resources)
    * By CAS Assessment Working Group. 
    * Hello World Issue 19: Sustainability and Computing June 2022
    * [Create your own self-marking python tests](https://blog.withcode.uk/create-with-code-getting-started/create-your-own-self-marking-python-tests/)
        * Powerful because it looks for statements in the code - this is required for crediting beginners with partial solutions (e.g. using the correct relational operator `>=` in their solution even if their solution does not run)

* A super power for our subject discipline with code.

* `assert` statement
    * A shortcut to say "I expect this to be true - or break/error/stop now with a text description"
    * python `assert my_value == 3, f"I wanted my_value to be 3 but I got {my_value}"`
    * csharp `Debug.Assert(val != 2, " Value should not be 2.");` [example assert-in-csharp](https://www.educba.com/assert-in-c-sharp/)

* https://replit.com/@AllanCallaghan/DoctestMarkdownTest
    * An example of using different types of automated test in python.
        * Tests via Main method and assertions
            * (no real test framework)
        * Doctests
            * `python example_assertions.py`
        * Doctests inline with code
            * `python -m doctest --fail-fast example_doctest_inline.py`
        * Doctest in separate MarkDown file
            * `python -m doctest --fail-fast example_markdown.md`
        * Other options `-v` `--fail-fast`
    * TASKS
        1. Complete the tests that fail when you hit the run button
        2. Using the shell command-line run the (total of) 3 other methods for writing/running tests in python
            * see `.replit` for the commands for each type of test
        3. Attempt to use replit's built in unit-tests
            * I don't like the idea of vendor lock-in. We can't move between providers. Let's investigate what these tools do
            * (Since writing, replit tests are now behind paywall from August 2023) 
            * (original task) Add a repl.it unit test for subtract (the _tick_ icon on the left)
            * https://docs.replit.com/teams-edu/unit-testing
            * https://docs.replit.com/teams-edu/input-output-testing video/demo on this page

* https://github.com/calaldees/TeachProgramming/blob/master/teachprogramming/static/projects/data/crypto.md
* An example of use semi-professionally - inline doctest
    * https://github.com/calaldees/libs/blob/71a86ada8d641b49215893c53b92c31190254e13/python3/calaldees/music.py#L27


### Professional systems

There are integrated all-in-one auto-mark solutions for Computer Science problems.

* [CodingRooms](https://www.codingrooms.com/)
    * See video
* [Isaac Computer science: GCSE Workbooks](https://isaaccomputerscience.org/pages/gcse_workbooks?examBoard=all&stage=all)
    * Online workbooks and theory aligned to specifications with teacher progress
    * Apparently has auto marking tests
* [mimirhq.com](https://www.mimirhq.com/classroom/demo_video) mimir classroom (university)
    * Video
        * Coding assignment - see animation of how student solved problem
    * Designed for significantly scaling courses


### Pedagogy

* What are the advantages of automated tests?
* What are the problems with automated tests?

<details>

* Fast feedback on performance
* Specification (know what you're aiming for)
* If students build tests - You are more likely to understand what you want the task is, if you construct tests before starting a task.
    * How can you get somewhere if you don't know where you are going?

* Students are bad at writing tests ... so they will be even worse at writing code ...
* [The Peanut Butter and Jelly Sandwich Challenge as an Approach to Improve Students Abilities in Test Case Writing](https://dl.acm.org/doi/10.1145/3304221.3325582) 2019
    * > Test cases are a set of test inputs, execution conditions, and expected results developed for a particular objective, such as to exercise a particular program path or to verify compliance with a specific requirement. 
    * > Test cases that are written by students typically have recurring errors that make difficult to find hidden bugs or lack essential details about the data to be used and the instructions that must be followed. 
    * > As an attempt to improve the quality of students test cases, we used a "Peanut butter and jelly sandwich challenge", typically used to teach algorithmic thinking, to show students the difficulties one may have repeating a simple set of instructions when they are not precisely described. That activity was adapted to cover contents focused on test case writing.
* Concept: Spend a lesson beforehand writing the tests!

</details>