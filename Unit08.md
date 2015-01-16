**Unit 8: Java I/O and Exception Handling** <span id="8"></span> 
*In this unit, we will discuss two important programming concepts in
Java: input and output, and well as exception handling. Input and output
techniques allow programmers to design more complex and useful programs.
For this reason, you must fully understand how to use a programming
language's built-in I/O (input/output) functionality. In this unit, we
will discuss function I/O in Java before moving on to file I/O: both
writing and reading data to and from files. Each unit will contain a
discussion of the applicable Java classes, which are part of the
standard programming language -* FileWriter, PrintWriter, FileReader,
BufferedReader,* and *IOException*. We will then identify the common
pitfalls and design concepts that you should keep in mind as a
programmer. By the end of this unit, you will have a strong
understanding of how to write and read from a file and how to write a
Java program that performs these functions. Exception handling mechanism
allows a program to continue executing, even if an error occurs in the
program, instead of terminating it abruptly.*

**Unit 8 Time Advisory**  
This unit should take you approximately 11.75 hours to complete.  
  
 ☐    Subunit 8.1: 3.5 hours  
  
 ☐    Subunit 8.2: 3 hours  
  
 ☐    Subunit 8.3: 2 hours  
  
 ☐    Subunit 8.4: 3.25 hours

**Unit8 Learning Outcomes**  
Upon successful completion of this course, the student will be able to:
-   describe Java I/O package;  
      
-   read and write data from/to an external file; and  
      
-   use exception handling techniques.

**8.1 Input/Output in Java** <span id="8.1"></span> 
-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java:* “Chapter 10: Input
    and Output”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter 10:
    Input and
    Output”](http://chortle.ccsu.edu/java5/Notes/chap10/ch10_1.html)
    (HTML) (MP3)  
      
     Instructions: Read through the tutorial. Click on the arrow keys to
    navigate to each slide. You may click on the sound icon at the top
    of the webpage to listen to the MP3. Note that this resource applies
    to the topics outlined for Subunit 8.1.1 and Subunit 8.1.2.  
      
     Reading this chapter and taking notes should take approximately 2
    hours.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Assessment: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Fill in the Blanks
    Exercise for Input and Output”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Fill in the
    Blanks Exercise for Input and
    Output”](http://chortle.ccsu.edu/java5/Notes/chap10/fillBlankCh10.html) (HTML)   
      
     Instructions: Complete the fill in the blanks exercise. Think of
    the best response to fill in the blanks for each question, or you
    may write your answer down on a separate sheet of paper. After
    thinking of the answers, click on the blank in each question to
    reveal the correct response.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

**8.1.1 Standard I/O** <span id="8.1.1"></span> 
*Java provides a* Scanner*class to facilitate the data input/output. In
this section, you will learn about the* Scanner*class that is used to
get input from the user. Read pages 1 to 4 to learn about the Standard
I/O classes in Java. Page 4 discusses three more I/O classes that are
used to get input/output from the user.*

**8.1.2 Common I/O Classes and Operations** <span id="8.1.2"></span> 
*Java also defines various methods from the* Scanner*class can convert
user input into appropriate data type before conducting any operation on
the data. Read page 5 onwards till the end and run the program called
‘Echo.java’ to understand the use of these classes and the program’s
methods.*

**8.1.3 String Formation** <span id="8.1.3"></span> 
-   **Reading: The Saylor Foundation’s “String Formation”**
    Link: The Saylor Foundation’s [“String
    Formation”](http://www.saylor.org/site/wp-content/uploads/2013/02/CS101-6.3.3-String-Formation-FINAL.pdf) (PDF)  
      
     Instructions: Read this article.  
      
     Reading this article and taking notes should take approximately 1
    hour.

**8.2 Writing Data to a File** <span id="8.2"></span> 
**8.2.1 The FileWriter Class in Java** <span id="8.2.1"></span> 
-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 83: Writing
    Text Files”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter 83:
    Writing Text
    Files”](http://chortle.ccsu.edu/java5/Notes/chap83/ch83_1.html) (HTML)   
      
     Instructions: Read through the chapter. Make sure to use the arrow
    keys to navigate to each slide.  
      
     Reading this chapter and taking notes should take approximately 2
    hours.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Assessment: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Quiz on Writing Text
    Files”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Quiz on
    Writing Text
    Files”](http://chortle.ccsu.edu/java5/Notes/chap83/chap83quiz.html) (HTML)  
      
     Instructions: Work through the quiz. Click on the “Grade Quiz”
    button at the end to see how many answers you got correct as well as
    to reveal the correct answers for each question.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

**8.2.2 The PrintWriter Class in Java** <span id="8.2.2"></span> 
-   **Reading: Java Samples: Abinaya’s “Using PrintWriter in Java”**
    Link: Java Samples: Abinaya’s [“Using PrintWriter in
    Java”](http://www.java-samples.com/showtutorial.php?tutorialid=329) (HTML)  
      
     Instructions: Read through the tutorial.  
      
     Reading the tutorial and taking notes should take approximately 30
    minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.3 Reading Data from a File** <span id="8.3"></span> 
-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 84: Reading
    from Text Files”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter 84:
    Reading from Text
    Files”](http://chortle.ccsu.edu/java5/Notes/chap84/ch84_1.html) (HTML)   
      
     Instructions: Read through the chapter. Make sure to use the arrow
    keys to navigate to each slide. Note that this resource will also
    cover the topics outlined in Subunit 8.3.1 and Subunit 8.3.2.  
      
     Reading this chapter and taking notes should take approximately 1
    hour and 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Assessment: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Quiz on FileReader
    and BufferedReader”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Quiz on
    FileReader and
    BufferedReader”](http://chortle.ccsu.edu/java5/Notes/chap84/chap84quiz.html) (HTML)  
      
     Instructions: Work through the quiz. Click on the “Grade Quiz”
    button at the end to see how many answers you got correct as well as
    to reveal the correct answer to each question. Note that this
    assessment applies to Subunit 8.3.1 and Subunit 8.3.2.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

**8.3.1 The FileReader Class in Java** <span id="8.3.1"></span> 
*This tutorial explains the Java I/O API and discusses* Reader*classes
in detail. The second page shows* ReaderStream *class hierarchy.*
FileReader*and* BufferedReader*classes are used together when reading
data from an external file. Please study the example on page 4 to see
how these classes are used. Also, copy and paste the code on page 4 in
a* newNetBeans*file, and run the program on your machine.*

**8.3.2 The BufferedReader Class in Java** <span id="8.3.2"></span> 
*The use of* BufferedReader*class allows data to be buffered as it is
read from the file before manipulating it. The readLine() method of the*
BufferedReader*class reads a line of text from a character-oriented
input stream, and puts it into a new* String*object. Read page 4 to
learn about* BufferedReader*class.*

**8.4 Exception Handling** <span id="8.4"></span> 
-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 80:
    Exceptions”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter 80:
    Exceptions”](http://chortle.ccsu.edu/java5/Notes/chap80/ch80_1.html) (HTML)
    (MP3)  
      
     Instructions: Read through the tutorial. Click on the arrow keys to
    navigate to each slide. You may click on the sound icon at the top
    of the webpage to listen to the MP3. Note that the resource also
    covers the topics outlined for Subunits 8.4.1 - 8.4.3.  
      
     Reading this chapter and taking notes should take approximately 2
    hours and 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Web Media: YouTube: The New Boston’s “Exception Handling”**
    Link: YouTube: The New Boston’s [“Exception
    Handling”](http://www.youtube.com/watch?feature=player_embedded&v=K_-3OLkXkzY) (YouTube)  
      
     Instructions: Watch this video as it demonstrates the use of *try*
    and *catch* blocks to catch exceptions in a simple Java program.
    Note that this resource also covers the topic outlined in Subunit
    8.4.2.  
      
     Watching this video and taking notes should take approximately 15
    minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.4.1 Exception and Errors** <span id="8.4.1"></span> 
*Both exceptions and errors are problems that may happen when a program
is running. They can disrupt the normal execution of the program and
halt the program abruptly. An exception is usually external to the
program such as invalid values from an input and output device, which
can be recovered so that the program can resume execution, while an
error is usually severe so that the program has to be stopped. Java
uses*Exception*class to hold information about the exception and*
Error*class But Read first three pages of the resource to understand the
difference between exception and error. In Java, both* Exception*class
and* Error *class are derived from a class called “throwable.” Read
first three pages of the resource to understand the hierarchy of
exception handling classes.*

**8.4.2 “try” and “catch” Blocks** <span id="8.4.2"></span> 
*At the very core of exception handling mechanism are the keywords*
try*and* catch*. They work together to catch and fix problems in a
program. The try block contains code that might throw an exception while
the catch block contains code that handles the exception. Read slides 5
to 10 in the tutorial of Central Connecticut State University: Bradley
Kjell’s Introduction to Computer Science Using Java: “Chapter 80:
Exceptions” as well as view the video by The New Boston to understand
how the try and catch blocks are used to handle problems in the
program.*

**8.4.3 Stack Trace** <span id="8.4.3"></span> 
*Once an execution of a program stops due to a problem, JVM’s default
exception handler terminates program execution and displays an error
message followed by a list of method calls that lead to the exception.
This is referred to as stack trace. Study slides 1, 2, 17 and 18 in the
tutorial of Central Connecticut State University: Bradley Kjell’s*
Introduction to Computer Science Using Java: *“Chapter 80: Exceptions”
to understand stack trace and how it is printed.*

-   **Assessment: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Quiz on Exceptions
    and Errors”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Quiz on
    Exceptions and
    Errors”](http://chortle.ccsu.edu/java5/Notes/chap80/chap80quiz.html) (HTML)  
        
     Instructions: Complete the multiple-choice quiz. After you have
    answered each question, click on the “Grade Quiz” button to see how
    many answers you got correct. Note that the correct answer will
    appear below each question.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.


