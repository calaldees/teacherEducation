Assessment Mark-scheme (1.5 hours)
-----------------------

TS 6 - Make accurate and productive use of assessment  
* know and understand how to assess the relevant subject and curriculum areas, including statutory assessment requirements  
#6/b-Assessment-LearnHow-external_resources

### Exam Boards

Each exam board publish's sample assessment material.

* [AQA - 8525 from 2020](https://www.aqa.org.uk/subjects/computer-science-and-it/gcse/computer-science-8525)
    * [Computer Science (8525) Assessment resources](https://www.aqa.org.uk/subjects/computer-science-and-it/gcse/computer-science-8525/assessment-resources)
* [OCR - Computer Science (9-1) - J277 Teaching from 2020](https://www.ocr.org.uk/qualifications/gcse/computer-science-j277-from-2020/)
    * Spec [pdf](https://www.ocr.org.uk/Images/558027-specification-gcse-computer-science-j277.pdf)
    * [Assessment](https://www.ocr.org.uk/qualifications/gcse/computer-science-j277-from-2020/assessment/)
* [Pearson Edexcel GCSE Computer Science (2020)](https://qualifications.pearson.com/en/qualifications/edexcel-gcses/computer-science-2020.coursematerials.html)


### Components to investigate

* Command Words (10min)
    * Look at the definitions of the command words used by the exam board.
        * THIS IS NOT OBVIOUS TO STUDENTS. They words mean different things in different subjects
    * OCR [Assessment story: exploring our question papers](https://www.ocr.org.uk/Images/562109-assessment-story-exploring-our-question-papers.pdf)
* Psudocode is defined for exam boards (10min)
    * [Notes and guidance: Pseudo-code](https://filestore.aqa.org.uk/resources/computing/AQA-8525-NG-PC.PDF)
        * Note the arrow thingy for assignment
    * OCR Spec - 3c. OCR Exam Reference Language
* Mark scheme (10min)
    * AQA [Mark scheme: Paper 1 Computational thinking and programming skills - Sample set 1](https://filestore.aqa.org.uk/resources/computing/AQA-85251-SMS-S1.PDF)
        * Annotation Notation: NE, I, //, : (find out what they mean)
* AQA Marking Practice (30min)
    * [Exam Series: Sample Set 1](https://www.aqa.org.uk/subjects/computer-science-and-it/gcse/computer-science-8525/assessment-resources?num_ranks=200&f.Exam+series%7CW=Sample+set+1&sort=date)
    1. Do "Question paper: Paper 1"(A C#, B Python, C VB.Net) - Question 5 - (Do this on printed paper!)
    2. Use "Mark scheme: Paper 1" on your own answer
    3. (As class - project - move between 5 responses in variety of languages and apply mark-scheme)
        * "Answers and commentary: Paper 1"(A,B or C)
* Edexcel (Paper 2 On-screen) 20min
    * See Programming Language Subset (PLS)
    * [Q1: Python exam practice questions for Edexcel GCSE Computer Science](https://blog.withcode.uk/2022/03/q1-python-exam-practice-questions-for-edexcel-gcse-computer-science/)
    * (From Edexcel Site) GCSE_L1_L2_Computer_Science_2020_collated_SAMs. [pdf](https://qualifications.pearson.com/content/dam/pdf/GCSE/Computer%20Science/2020/specification-and-sample-assessments/GCSE_L1_L2_Computer_Science_2020_collated_SAMs.pdf)
    * `Q04.py`
    *   ```python
        # -------------------------------------------------------------------
        # Global variables
        # -------------------------------------------------------------------
        year = 0            # Do not move this line
        strYear = ""        # Do not move this line

        # -------------------------------------------------------------------
        # Main program
        # -------------------------------------------------------------------

        # Put the lines into the correct order to solve the problem.
        # A user types in a year group.  The program indicates which stage
        # of education the year group belongs to.  The program loops until
        # the user enters 0.
        # Example:
        # Input                 Output
        # -----------------------------------------
        # 0                     Exits program
        # 1, 2, 3, 4, 5, 6      Primary
        # 7, 8, 9, 10, 11       Secondary
        # 12, 13                College

        if (year < 1):
        strYear = input ("Enter year group (1 to 13, 0 to exit)")
        strYear = input("Enter year group (1 to 13, 0 to exit)")
        year = int(strYear)
        year = int (strYear)
        print ("Year too big")
        print ("College")
        print ("Year too small")
        print ("Secondary")
        print ("Primary")
        elif (year < 7):
        elif (year > 13):
        elif (year < 12):
        else:
        while (year != 0):
        ```
* More
    * AQA [Practice questions: Paper 1 Computational thinking and programming skills](https://filestore.aqa.org.uk/resources/computing/AQA-85251-PQ-S1.PDF)
        * Examples of low-tier, mid tier and high-tier student answers 'scanned from paper' examples and mark-commentary
    * Q: Is writing code on paper the same as writing on screen?
    * Q: How much time do you allocate for students to "write code on paper"? - This paper is 50% of the GCSE
    * Q: What could this mean for your teaching?
    * WithCode.uk [GCSE Computer Science Revision Paper 1 Worked Solution](https://blog.withcode.uk/gcse-computer-science-revision-paper-1-worked-solution/)
        * Notice how he highlights the key words and describes each of the words
* Examiners report
    * Identify common patterns/misconceptions
    * [PGOnline - GCSE Computing - Examiners Report Summaries](https://www.pgonline.co.uk/landing/examiners-report-summaries/)
    * [AQA A-Level - computer-science-7516-7517 - Examiners Reports](https://www.aqa.org.uk/subjects/computer-science-and-it/as-and-a-level/computer-science-7516-7517/assessment-resources?f.Resource+type%7C6=Examiner+reports) (more readily available)


### Further reading

* [Investigating the Effects of Testing Frequency on Programming Performance and Students' Behavior](https://dl.acm.org/doi/10.1145/3545945.3569821) SIGCSE 2023
    * (1) that the frequent testing regimen encourages better study habits (e.g., more attention to work, less cramming) and leads to better learning, 
    * (2) that frequent testing reduces test anxiety, and 
    * (3) that the frequent testing regimen was more fair, 
    * but these opinions were not universally held.


### My closing thoughts

* I would suggest that every single GCSE lesson has an exam style question.
    * If your lesson did not help student work towards something in the GCSE - then was it worthwhile? - you have a VERY limited amount of time with them before the GCSE
        * If you cant set an exam question based on what you delivered - then have an exam question for spaced repetition for a previous topics
    * Students must be comfortable with the mode of assessment - *writing on paper* should be part of your computing lessons
    * Super side note: If you plan your sequence of lessons in advance, you can create and print in advance a booklet for students to write it - if as a teacher you plan each lesson ad-hoc; this does not let the teacher or the students have a clear picture of the goals of your unit/segment
