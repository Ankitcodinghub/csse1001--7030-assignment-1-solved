# csse1001--7030-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSSE1001 -7030 Assignment 1 Solved](https://www.ankitcodinghub.com/product/csse1001-7030-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116003&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSSE1001 -7030 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Assignment 1

Introduction

Welcome to the dating game. With the popularity of Married at First Sight, we are going to build a matchmaking program. Some people worry that robots will replace workers, here is your chance to replace some pop-psychologists ☺.

The program will give the user a personality test and ask some questions about their physical characteristics and preferences. It will use these to find the best match in a database of potential partners.

You are provided with the code that reads the partner data from the database. You need to implement the functionality to perform the personality test, question the user and perform the matching. The database is in the form of a text file. You can edit the text file to add more partners. You must follow the text file format exactly as specified.

Example Interaction

Welcome to PyMatch

Please enter your name: Ian Foo

Hi Ian Foo.

What is your gender?

1) male

2) female

3) other

Please enter your answer: 1

What is your sexual preference?

1) male

2) female

3) other

Please enter your answer: 2

What is your height?

1) tall

2) medium

3) short

Please enter your answer: 1

What height do you prefer your partner to be?

1) tall

2) medium

3) short

Please enter your answer: 2

We will now ask you some questions to try to determine your personality type.

Do you find it easy to introduce yourself to other people?

1) Yes

2) Most of the time

3) Neutral

4) Some times

5) No

Please enter your answer: 4

Do you usually initiate conversations?

1) Yes

2) Most of the time

3) Neutral

4) Some times

5) No

Please enter your answer: 4

Do you often do something out of sheer curiosity?

1) Yes

2) Most of the time

3) Neutral

4) Some times

5) No

Please enter your answer: 2

Do you prefer being out with a large group of friends rather than spending time on your own?

1) Yes

2) Most of the time

3) Neutral

4) Some times

5) No

Please enter your answer: 2

Thank you for answering all the questions. We have found your best match from our database and hope that you enjoy getting to know each other. Your best match is: Mary Smith

The final output of your program must be only the full name of the match on a line by itself. Do not provide any embellishments in the output as this will cause automatic program checking to fail.

Design

The focus of this assignment is on implementing and testing the required functionality. A simple design is provided below.

You should have one or two functions that prompt the user to answer the physical characteristics questions and the personality test questions. Some people will find it easier to implement this functionality with two functions.

physical_characteristics_question(question, answer1, answer2, answer3)

This function would take the question and three answer options as parameters. After displaying the question and answer options it will prompt the user for an answer choice. It will return the number corresponding to the answer that the user selected.

personality_question(question)

This function would take the question as a parameter. After displaying the question and the five standard answer options it will prompt the user for an answer choice. It will return the number corresponding to the answer that the user selected.

The personality test scoring is a simple summation of two times the number corresponding to the user’s answer to each question. For example, if a user answered the four personality test questions above as: 2, 2, 3 and 4; their personality test score would be (2 + 2 + 3 + 4) × 2, which equals 22. A personality match is determined by simply finding the potential partners with a test score as close as possible to the user’s score. For example, if there were three potential partners with scores of 10, 12 and 40, then the person with the score of 12 would be the closest match for the user with a score of 22.

You should have at least one function that performs the matching. The matching algorithm guarantees that the genders and gender preferences of the user and suggested partner match. It then finds the potential partners in the database that have personality test scores that are closest to the user’s score. From these potential partners, it then finds the best match based on the user’s, and secondarily the potential partners’, height preferences. If there is more than one best match it will just return the name of the first one found. If there is no match it returns None.

match(gender, sexual_pref, height, height_pref, personality_score)

The five parameters are the user’s details. It uses the utility functions in the partners.py file to iterate through the database of potential partners and perform the matching logic. (An example of iterating through all of the potential partners in the database and accessing each person’s details is provided in the file: partners_example.py.) You are not required to use the utility functions in the partners.py file but are encouraged to do so to reduce the amount of work you need to do to complete this assignment. (Note: The two classes in the partners.py file could be designed better. They have been simplified for use in this assignment, as you are not required to understand object-oriented concepts. Redesigning these classes will not contribute towards the bonus mark.)

It is good design practice, and a good assessment strategy, to implement a program in stages. Doing this means that you are much more likely to have a working program to submit even if you cannot implement all of the requirements. As a suggestion, you should first implement the personality_question function and the match function that only uses the personality score to match a user to a partner. Next try implementing the physical_characteristics_ question function and extend the match function to add in gender and gender preferences to the matching algorithm. Then extend the match function to add in height and height preferences to the matching algorithm. Finally add input testing to your program.

Database

The database is a text file containing the names and results of the PyMatch questions. Each line of the text file corresponds to a single person. Each data item on the line is separated by a single space. The first data item is the person’s first name. The second item is their last name. The third item is their gender. The fourth item is the gender of the partner they are seeking. The fifth item is the person’s height. The sixth item is their preference for the height of their partner. The seventh item is their personality test score. The structure of the text file is as follows: first_name last_name gender gender_preference height heigh_preference personality_test_score You should add new entries to the text file to test your program thoroughly.

Submission

You must submit your completed assignment electronically through Blackboard.

For information on submitting through Blackboard, please read: https://web.library.uq.edu.au/library-services/it/learnuq-blackboard-help/learnuqassessment/blackboard-assignments

See the course profile for details of how to apply for an extension: http://www.courses.uq.edu.au/student_section_loader.php?section=5&amp;profileId=85405

Assessment and Marking Criteria

This assignment assesses course learning objectives:

1. apply program constructs such as variables, selection, iteration and sub-routines,

3. read and analyse code written by others,

5. read and analyse a design and be able to translate the design into a working program,

6. apply techniques for testing and debugging

Criteria Mark

Programming Constructs

• Program is well structured and readable

• Variable and function names are meaningful

• Appropriate constructs are employed

• Functions correspond to design expectations

• Algorithmic logic is appropriate

1

1

1

1

2

Sub-Total 6

Functionality

• Implements correct functionality with no serious errors

• Implements correct functionality with some errors

• Implements part of the functionality

2

1.5

0.5

Sub-Total 2

Documentation

• Entire program is documented clearly and concisely, without excessive or extraneous comments

• Program is documented clearly, with all functions having meaningful docstring comments

• Some parts of the program have adequate comments

2

1.5

0.5

Sub-Total 2

Bonus

• Improved on the provided design. This bonus will only be awarded if the total mark for the previous sections is at least 7.5. Changing the design, without improving it, will result in a low mark for the Programming Constructs section.

• Criteria that will be used for assessing if the design has been improved are:

o simplification of logic (e.g. combining the two question functions into a single function); and

o improving the cohesion of functions (cohesion means that all parts of the function relate to a single purpose).

• The maximum possible mark for this assignment is 10, even if the total for the assignment and the bonus is greater than 10. 1

Total / 10

• any parts of the assignment that you found particularly difficult, and how you overcame them to arrive at a solution;

• whether you considered any alternative ways of implementing a given function;

• where you have known errors in your code, their cause and possible solutions (if known).
