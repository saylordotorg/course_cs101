**Unit 5: Control Structures** <span id="5"></span> 
*Control structures dictate what the behavior of a program will be under
what circumstances. Control structures belong to one of two families:
those that test values and determine what code will be executed based on
those values, and those that loop, performing identical operations
multiple times. Control structures like* if-then-else*and* switch*the
program to behave differently based on the data that they are fed. The*
while *and* for loops *allow you to repeat a block of code as often as
it is needed. As you can see, that functionality can be very useful when
designing complex programs. This unit will introduce you to control
structures and the ways in which they are used before moving on to
discuss* if*,* switch*,* while/do-while*, and* for loops*. We will also
discuss some advanced topics, such as* nesting *and* scope*. By the end
of this unit, you should be able to draw from the information you
learned in the previous unit to create a control structure, which will
allow you to create more complex and useful programs.*

**Unit 5 Time Advisory**  
This unit should take you approximately 16.75 hours to complete.  
  
 ☐    Subunit 5.1: 1 hour  
  
 ☐    Subunit 5.2: 2.5 hours  
  
 ☐    Subunit 5.3: 2.5 hours  
  
 ☐    Subunit 5.4: 3.75 hours  
  
 ☐    Subunit 5.5: 4 hours  
  
 ☐    Subunit 5.6: 3.5 hours

**Unit5 Learning Outcomes**  
Upon successful completion of this course, the student will be able to:
-   use control structures;  
      
-   identify an “if” statement;  
      
-   identify a “switch” statement; and  
      
-   explain various looping structures such as “for,” “while,” and “do”
    loops.

**5.1 Introduction to Control Structures** <span id="5.1"></span> 
-   **Reading: Learnola.com’s “Beginning Java Tutorial - Methods -
    Control Structures”**
    Link: Learnola.com’s [“Beginning Java Tutorial - Methods - Control
    Structures”](http://web.archive.org/web/20081206023033/http://learnola.com/2008/12/03/beginners-java-tutorial-methods-control-structures/) (HTML)  
      
     Instructions: Read the first three paragraphs of the reading.
    Control structures can transfer the execution of a sequential code
    to some other part of the program based on user input or some other
    value. There are various kinds of control structures such as
    conditional statements, loops, and methods that control the flow of
    a program. Read the sections under headings “Conditional,” “Loops in
    Java,” and “Methods” to understand more about the types of
    conditional structures in Java. Different type of control structures
    are discussed in greater detail in Subunit 5.2.  
      
     Reading this article and taking notes should take approximately 1
    hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.2 The “if” Statement** <span id="5.2"></span> 
-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 12: Decision
    Making”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter 12:
    Decision
    Making”](http://chortle.ccsu.edu/java5/Notes/chap12/ch12_1.html) (HTML)
    (MP3)  
      
     Instructions: Read this chapter. Make sure you click on the “next”
    button to move through each slide. You may also click on the sound
    icon to listen to the MP3. This chapter discusses how computer can
    make decisions using an *if* statement. Note that this reading
    applies to the topics outlined in Subunit 5.2.1 and Subunit 5.2.2.  
      
     Reading this chapter and taking notes should take approximately 2
    hours.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Assessment: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Quiz on the If
    Statement”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Quiz on the
    If
    Statement”](http://chortle.ccsu.edu/java5/Notes/chap12/chap12quiz.html) (HTML)  
      
     Instructions: Work through the quiz. Click on the “Grade Quiz”
    button at the end. Note that this assessment applies to Subunit
    5.2.1 and Subunit 5.2.2.  
      
     Completing this assessment should take less than 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

**5.2.1 Uses** <span id="5.2.1"></span> 
*As you read this tutorial, you will understand that sometimes it is
important to evaluate the value of an expression and perform a task if
the value comes out to be true and another task if it is false. In
particular, try the simulated program under the heading “Simulated
Program” to see how a different response is presented to the user based
on if a number is positive or negative.*

**5.2.2 General “if-else” Structure in Java** <span id="5.2.2"></span> 
*The* if-else *structure can evaluate a Boolean expression and execute
the statements in the “if” block when the value is “true,” or the
statements in the “else” block when the value is “false.” Pay special
attention to the reading under the heading “More Than One Statement per
Branch” to learn how the ‘else’ statement is used when there is more
than one choice.*

**5.3 The ‘switch’ Statement** <span id="5.3"></span> 
-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 43: More
    Ways to Make Decisions”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter 43:
    More Ways to Make
    Decisions”](http://chortle.ccsu.edu/java5/Notes/chap43/ch43_1.html) (HTML)  
      
     Instructions: Read the chapter. It discusses *switch* statement and
    “?” operator to write conditional statement. Note that this reading
    applies to the topics outlined for Subunit 5.3.1 and Subunit
    5.3.2.  
      
     Reading this chapter and taking notes should take approximately 2
    hours.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Assessment: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Quiz on the
    Conditional Operator and the Switch Statement”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Quiz on the
    Conditional Operator and the Switch
    Statement”](http://chortle.ccsu.edu/java5/Notes/chap43/chap43quiz.html) (HTML)  
      
     Instructions: Work through the quiz. Click on the grade quiz button
    at the end. Note that this applies to Subunit 5.3.1 and Subunit
    5.3.2.  
        
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

**5.3.1 Uses** <span id="5.3.1"></span> 
*As you read this tutorial, you will learn that sometimes is better to
use a switch statement when there are multiple choices to choose from.
Under such conditions, an if-else structure can become very long and at
times difficult to comprehend. Read the section under the heading
“Many-way Branches,” and pay special attention to the syntax of the
‘switch’ statement.*

**5.3.2 Relationship to ‘if’** <span id="5.3.2"></span> 
*Read the rest of this tutorial will help you understand the limitation
of the*s witch *statement, and the similarity of the logic used for the*
if-else *statement and* switch *statement and how they can be used
alternately. The* switch *statement can only be used to implement
multi-way branches based on the value of a single expression.*

**5.4 The “while’ and “do-while” Loops** <span id="5.4"></span> 
-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 15: Loops
    and the While Statement”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter 15:
    Loops and the While
    Statement”](http://chortle.ccsu.edu/java5/Notes/chap15/ch15_1.html) (HTML)
    (MP3)  
      
     Instructions: Read this chapter. Make sure to click on the arrows
    to navigate through these webpages. You may also click on the sound
    icon at the top of the webpage to listen to the MP3. This chapter
    explains *while* loop. Note that this reading applies to Subunit
    5.4.1 and Subunit 5.4.2.  
      
     Reading this chapter and taking notes should take approximately 2
    hours.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Web Media: Khan Academy’s “While Loops”**
    Link: Khan Academy’s [“While
    Loops”](https://www.youtube.com/watch?v=D0Nb2Fs3Q8c) (YouTube)  
      
     Instructions: Watch the 6-minute lecture. It explains loops by
    applying them to a simple application, manipulating lists. Though
    the video uses Python programming language to explain
    the *while* loop, the basic concept of the *while *loop remains the
    same. The *while* loop requires a statement in the body of the loop
    that updates the control variable. In the next section, we will
    learn about the ‘for’ loop, which is another implementation of a
    loop, where the control is automatically updated.  
      
     Watching this lecture and taking notes should take approximately 15
    minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/). It
    is attributed to the Khan Academy. 

-   **Assessment: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Fill in the Blank
    Exercise *For* Loops and the *While* Statement”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Fill in the
    Blank Exercise *For *Loops and
    the *While* Statement”](http://chortle.ccsu.edu/java5/Notes/chap15/fillBlankCh15.html) (HTML)  
      
     Instructions: Think of the correct response to fill in the blank
    for each question, or write your response down on a separate piece
    of paper. Then, click on the blank to reveal the correct answer.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 44: The
    Daring Do Statement”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter 44:
    The Daring Do
    Statement”](http://chortle.ccsu.edu/java5/Notes/chap44/ch44_1.html) (HTML)  
      
     Instructions: Read this chapter. It discusses the *do* loop, which
    is a variation of the *while* loop. Note that this resource applies
    to the topics outlined in Subunit 5.4.1 and Subunit 5.4.2.  
        
     Reading this chapter and taking notes should take approximately 30
    minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Assessment: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Quiz on the do
    Statement”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Quiz on the
    do
    Statement”](http://chortle.ccsu.edu/java5/Notes/chap44/chap44quiz.html) (HTML)  
      
     Instructions: Work through the quiz. Click on the “Grade Quiz”
    button at the end to see how many questions you answered correctly
    as well as to reveal the correct answers. Note that this assessment
    applies to Subunit 5.4.1 and Subunit 5.4.2.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Assessment: The Saylor Foundation’s “Control Structures
    Programming”**
    Instructions: Write a Java program to calculate the average
    temperature of the weekday, i.e., Monday through Friday. The program
    asks the user to enter the temperature of each day, calculate the
    average, and print out the result. It also prints out a message if
    the average is above 100 degrees (too hot!) or if the average is
    below 0 degrees (too cold!). In addition, the program asks if the
    user wants to calculate the average temperature of another week. Use
    appropriate control structures.  
        
     After you have completed the activity, or if you need assistance,
    check the Saylor Foundation’s [“Guide to Responding to the Control
    Structures Programming
    Activity”](http://www.saylor.org/site/wp-content/uploads/2013/10/CS101-Unit-5-Guide-to-Responding.pdf)
    (PDF).  
      
     Completing this activity should take approximately 1 hour.

**5.4.1 Uses** <span id="5.4.1"></span> 
*After reading the tutorial, you will understand how a *do-while* loop
works. In a *do-while* loop, the body of the loop is executed at least
one time, whereas in a *while* loop, the loop may never execute if the
loop condition is false. Read the pages starting with the heading
“Bottom Driven Loop” to understand the advantages of this loop.*

**5.4.2 “while” vs. “do-while”** <span id="5.4.2"></span> 
*At the end of this tutorial, you will understand the difference
between *while* and *do-while* loops. They both are essentially the same
except that the *while* loop is a pre-test loop and may never execute if
the condition is false to begin with. On the other hand,
the *do-while* loop is a post-test loop and always executes at least one
time, even if the condition is false.*

**5.5 The ‘for’ Loop** <span id="5.5"></span> 
-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 41: The
    Fantastic For Statement”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter 41:
    The Fantastic For
    Statement”](http://chortle.ccsu.edu/java5/Notes/chap41/ch41_1.html) (HTML)
    (MP3)  
      
     Instructions: Read this chapter. It discusses *for *loop. This loop
    is more compact than the *while *and *do loops* and automatically
    updates the loop counter at the end of each iteration. Note that
    this resource applies to the topics outlined in Subunit 5.5.1 and
    Subunit 5.5.2.  
      
     Reading this chapter and taking notes should take approximately 1
    hour and 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Assessment: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Quiz on For Loops”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Quiz
    on *For *Loops”](http://chortle.ccsu.edu/java5/Notes/chap41/chap41quiz.html) (HTML)  
      
     Instructions: Work through the quiz. Click on the “Grade Quiz”
    button at the end to see how many answers you got correct as well as
    to reveal the correct answers. Note that this assessment applies to
    Subunit 5.5.1 and Subunit 5.5.2.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 42: More
    about the For Statement”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter 42:
    More about the For
    Statement”](http://chortle.ccsu.edu/java5/Notes/chap42/ch42_1.html) (HTML)  
      
     Instructions: Read this chapter. Make sure to click on the arrow
    buttons to navigate through each slide. You may also click on the
    sound icon at the top of the webpage to listen to the MP3. This
    chapter discusses the *for* loop in greater detail as well as the
    scope of variables in the *for *loop. Note that this resource
    applies to the topics outlined in Subunit 5.5.1 and Subunit 5.5.2.  
      
     Reading this chapter and taking notes should take approximately 1
    hour.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Assessment: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Quiz on Further For
    Loops”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Quiz on
    Further *For *Loops”](http://chortle.ccsu.edu/java5/Notes/chap42/chap42quiz.html) (HTML)  
      
     Instructions: Work through the quiz. Click on the “Grade Quiz”
    button at the end to see how many answers you got correct as well as
    to reveal the correct answers for each question. Note that this
    assessment applies to Subunit 5.5.1 and Subunit 5.5.2.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

**5.5.1 Uses** <span id="5.5.1"></span> 
-   **Web Media: Khan Academy’s “Writing a Simple Factorial Program,”
    “Stepping through the Factorial Program,” and “Flowchart for the
    Factorial Program”**
    Link: Khan Academy’s [“Writing a Simple Factorial
    Program”](https://www.youtube.com/watch?v=ZyYp1V84Xqc) (YouTube), [“Stepping
    through the Factorial
    Program”](https://www.youtube.com/watch?v=dn9XjHz33O8) (YouTube),
    and [“Flowchart for the Factorial
    Program”](https://www.youtube.com/watch?v=EiR6cf8Towc) (YouTube)  
      
     Instructions: Click on the first link above to watch the 8-minute
    lecture. This lecture uses a *for *loop to calculate the factorial
    of a natural number greater than or equal to 0. Remember to focus on
    the design or algorithm of the program and the semantics of the
    program statements.  
      
     Then, click on the second link above to watch the 9-minute lecture
    to note how Khan verifies the program by stepping through it. In the
    previous video, he also ran it several times to check it out.  
      
     Finally, click on the third link above to watch the 6-minute
    lecture. In this lecture, Khan discusses the design of the factorial
    program by flowcharting it; this is the design of the program, which
    logically is done before writing the program.  
      
     Watching these lectures and taking notes should take approximately
    30 minutes.  
      
     Terms of Use: These resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/). They
    are attributed to the Khan Academy. 

**5.5.2 Comparison to “while” and “do-while”** <span id="5.5.2"></span> 
*After completing Subunit 5.5.1, you will have clear understanding of
how a* for*loop is used and some of its advantages. At this point you
will be able to compare the* for *loop to while and* do-while*loops.*

**5.6 Advanced Topics** <span id="5.6"></span> 
**5.6.1 Nesting Control Structures** <span id="5.6.1"></span> 
-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 17: Nesting
    Loops and Ifs”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter 17:
    Nesting Loops and
    Ifs”](http://chortle.ccsu.edu/java5/Notes/chap17/ch17_1.html) (HTML)
    (MP3)  
      
     Instructions: Read this chapter. Make sure to use the arrow keys to
    navigate through the webpages. You may also click on the sound icon
    at the top of the page to listen to the MP3. This chapter discusses
    how control structures such as loops and if statements can be
    combined together to implement program logic.  
      
     Reading this chapter and taking notes should take approximately 2
    hours.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Assessment: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Fill in the Blanks
    Exercise for Nested Loops and Ifs”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Fill in the
    Blanks Exercise for Nested Loops and
    Ifs”](http://chortle.ccsu.edu/java5/Notes/chap17/fillBlankCh17.html) (HTML)  
      
     Instructions: Think of the correct response to fill in the blank or
    write your answer down on a separate piece of paper. Then click on
    the blank to reveal the correct answer.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

**5.6.2 Variable Scope within a Control Structure** <span
id="5.6.2"></span> 
-   **Reading: Hobart and William Smith Colleges: David Eck’s
    “Introduction to Programming using Java: Section 3.1 Blocks, Loops,
    and Branches”**
    Link: Hobart and William Smith Colleges: David Eck’s [“Introduction
    to Programming using Java: Section 3.1 Blocks, Loops, and
    Branches”](http://www.faqs.org/docs/javap/c3/s1.html) (HTML)  
      
     Also available in:  
     [PDF](http://math.hws.edu/eck/cs124/downloads/javanotes4.pdf)  
      
     Instructions: Read the webpage. It explains the variable scope in
    different control structures such as a block, *while *loop, and
    branching statement such as the *if* statement.  
      
     Reading this article and taking notes should take approximately 1
    hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


