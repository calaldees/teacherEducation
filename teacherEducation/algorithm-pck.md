Algorithm PCK
-------------

* [Teaching algorithms in upper secondary education: a study of teachers’ pedagogical content knowledge](https://www.tandfonline.com/doi/full/10.1080/08993408.2021.1935554) 2020 - Jacqueline Nijenhuis-Voogt, Durdane Bayram-Jacobs, Paulien C. Meijer, Erik Barendsen
    * > Computing education is expanding, while the teaching of algorithms is less well studied.
    * > teachers consider class discussions to play a significant role as an instructional method for provoking reflection.
    * Do we study algorithms form Object/Abstract level (no syntax required) or the program level (psudo code to real code)?
    * > introducing computing concepts without the use of a computer may keep “learners from the crucial computational experiences involved in CT’s common practice”
    * > Denning (2017) distinguished between “traditional CT” and “new CT”, describing one of the characteristics of “new CT” as follows: “it is completely optional whether an algorithm will ever be translated into a program”
        * See [[computational_thinking]]
    * Goals (GO), Student Understanding (SU), Instructional Strategies (IS), Assessment (AS), Interconnections (e.g. SU-IS)
        * [csv coding scheme](https://www.tandfonline.com/action/downloadTable?id=t0003&doi=10.1080/08993408.2021.1935554&downloadType=CSV)
    * ![Figure 2. Interconnection between PCK components (Adapted from Bayram-Jacobs et al., 2019)](https://www.tandfonline.com/na101/home/literatum/publisher/tandf/journals/content/ncse20/0/ncse20.ahead-of-print/08993408.2021.1935554/20210615/images/large/ncse_a_1935554_f0002_b.jpeg)
    * Conflicting approaches
        * "Thinking" (just the concept) or "Thinking and Making" (doing it in code)
        * > Transcribing to real code is not carried out by my students. [After writing the algorithm in pseudo-code], it does not add any value … at that time, they are at the level of understanding where they should be
        * > I want my students to be able to specify a logical solution for a problem on the level of elementary building blocks so you can make a one-on-one translation to a programming language
        * > Students will make something so they really get an idea what it involves rather than remaining theoretical
    * > prior programming experience does not help in thinking about solutions as students may be inclined to use a “trial-and-error” method
    * > teachers observed that students have difficulty with how to start solving problems. Teachers also described that students have difficulty with abstract problems, generalizing, analyzing and optimizing algorithms, 
    * > Algorithms may be described in natural language, in pseudo-code, or in programming language.
    * > lecturing or instructing, coaching or scaffolding, and discussing solutions with the class.
    * > There are usually alternative solutions for an algorithmic problem and teachers mentioned to encourage students to evaluate the different solutions and reflect on them.
    * > "What we miss in secondary education is to first think about what is needed, what is the goal, how we get there, and what steps can be distinguished."
    * > "We assess the implementation too much and I think we assess conceptual knowledge insufficiently. How do you assess whether students really understand a concept?"
* Coding scheme
    * GO - "Goals","Goals for teaching algorithms
        * learning to analyze algorithmic problems (e.g. decomposition)
        * learning to solve algorithmic problems
        * learning to code an algorithm
        * learning to analyze quality aspects of algorithms
        * being able to apply problem-solving skills outside CS
        * learning transversal skills while solving algorithmic problems
        * Motivations for objectives
            * preparing for a role in society
            * working with computers as tools
    * SU Students’ understanding","Variation in student approaches to learning because of:
        * different abilities
        * different interests
        * other reasons (e.g. different levels, motivation, gender)
        * Prior knowledge and skills with respect to:
            * programming experience
            * mathematical knowledge
            * analytical skills
    * Activities that are difficult or easy to learn
        * difficult: how to start solving problems
        * difficult: abstract problems, generalizing
        * difficult: analyzing and optimizing an algorithm
        * difficult: describing the analysis of algorithms, asymptotic notation
        * easy: concrete problems, puzzles
    * Elements students get (dis)engaged by
        * engaged by satisfaction, gratification of finding a solution
        * engaged by solving puzzles, “unplugged”
        * engaged by understanding “how it works”
        * disengaged by specifying algorithm (e.g. flowchart)
    * IS Instructional strategies","Representations for algorithms
        * describe algorithm in different languages (natural or programming)
        * express algorithms in schematic diagrams (e.g. flowchart)
        * use illustrations, examples (e.g. puzzles)
        * Teacher activities to help students comprehend specific concepts
            * coaching or scaffolding
            * discussing solutions with the class
            * lecturing or instructing a class
        * Class activities to help a class comprehend specific concepts
            * where students are active in practical work
            * where students think, reflect, evaluate
            * where students cooperate
    * AS Assessment","Aspects of students’ learning that are important to assess
        * developing an algorithm
        * implementation of an algorithm
        * Specific instruments of assessment
            * observing students during class
            * asking questions to students
            * giving students a test or a practical assignment"
    * Interconnections
        * Connection GO–SU
            * focus regarding goals is related to the appreciation of prior programming experience
            * students like to find the solution of an algorithmic problem
            * students are interested in relevant algorithmic problems
        * Connection SU–IS
            * adapting instructional strategies to meet student differences
            * scaffolding for topics that are difficult to learn
        * Connection GO–IS
            * specific instructional strategies for reaching certain goals
            * use of representations that are dependent on goals
        * Connection GO–AS
            * specific types of assessment for tracking certain goals

* [In the classroom: Teaching by algorithm](https://www.sec-ed.co.uk/best-practice/in-the-classroom-teaching-by-algorithm/)
    * TODO: unread

* [NCCE: Programming and algorithms within the computing curriculum](https://blog.teachcomputing.org/programming-and-algorithms-within-the-computing-curriculum/)
    * TODO: notes


* [Code Reading Club](https://www.felienne.com/archives/6472)
    * Reading code is harder than writing code
    * We are VERY bad at teaching learners to read code
    * a strong focus on creating code, very often ‘green-field’ code, starting from a specification or a set of tests. 
        * This leads to the fact that programmers in generally are really poorly equipped to read code, even their own code, but especially code written by others.
    * novices read code more linearly than expert programmers.
        * Learning to follow the call stack it a thing that comes with experience
    * Deliberate Reading
        * Reading Questions:
            * What is the first thing that jumps out at me? Why?
            * What’s the next thing I notice? Are these two things connected? How?
            * Do they seem to be saying different things?
        * These sentences encourage and train ‘scanning’ behaviour, which we know is a thing programmers do. 
        * The beautiful thing about this technique is that is gives me a thing “to do” when reading code. Rather than mindlessly scrolling thought the code,
    * Relational-Text
        * Link each occurrence of a variable with it's declaration
        * Identify the scope of a variable
        * Identify where a particular function is called
        * Verify if all expressions correctly typed
        * Clarify if every potential flow path of a function body ends with a return statement

* [ziglings](https://github.com/ratfactor/ziglings)
    * Interesting concept
    * This project contains a series of tiny broken programs. By fixing them, you'll learn how to read and write Zig code!
    * [/exercises](https://github.com/ratfactor/ziglings/tree/main/exercises)
        * Each program is broken and the task is described with comments


[//begin]: # "Autogenerated link references for markdown compatibility"
[computational_thinking]: computational_thinking.md "Computational Thinking"
[//end]: # "Autogenerated link references"