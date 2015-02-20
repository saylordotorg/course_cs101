---
layout: default
title: "CS101: Introduction to Computer Science I"
course_description: "An introductory course that covers the basic concepts, nomenclature, and historical perspective of computers and computing. Includes an introduction to software development and object-oriented programming."
next: ../Unit07
previous: ../Unit05
---
**Unit 6: User-Defined Methods** <span id="6"></span> 
*In addition to the methods predefined in Java, we can write
user-defined methods. In this unit, we will discuss how to name a
method, declare a parameter list, and specify the return type. This unit
introduces the scope of variables as well. By the end of this unit, you
will have a strong understanding of how to define and call a method.*

**Unit 6 Time Advisory**  
This unit should take you approximately 6.75 hours to complete.  
  
 ☐    Subunit 6.1: 3 hours  
  
 ☐    Subunit 6.2: 3.75 hours

**Unit6 Learning Outcomes**  
Upon successful completion of this course, the student will be able to:
-   write methods with or without parameters;  
      
-   write methods with return types;  
      
-   define overloaded methods; and  
      
-   make method calls.

**6.1 Method Syntax in Java** <span id="6.1"></span> 
-   **Reading: Massachusetts Institute of Technology Open Courseware:
    Dr. George Kocur’s *Introduction to Computing and Engineering
    Problem Solving*: “Lecture 6: Methods, Scope”**
    Link: Massachusetts Institute of Technology Open Courseware: Dr.
    George Kocur’s *Introduction to Computing and Engineering Problem
    Solving*: [“Lecture 6: Methods,
    Scope”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS101-6.1.pdf) (PDF)  
      
     Instructions: Review these lecture notes. This reading will also
    cover the topics outlined in Subunits 6.1.1 - 6.1.4.  
      
     Reading these lectures and taking notes should take approximately 1
    hour and 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/).

-   **Web Media: Khan Academy’s “Defining a Factorial Function,”
    “Diagramming What Happens with a Function Call,” “Recursive
    Factorial Function,” and “Comparing Iterative and Recursive
    Factorial Functions”**
    Link: Khan Academy’s [“Defining a Factorial
    Function”](https://www.youtube.com/watch?v=JwO_25S_eWE) (YouTube), [“Diagramming
    What Happens with a Function
    Call”](https://www.youtube.com/watch?v=6qCQB8E5bkI) (YouTube), [“Recursive
    Factorial
    Function”](https://www.youtube.com/watch?v=o920mj0NbhE) (YouTube),
    and [“Comparing Iterative and Recursive Factorial
    Functions”](https://www.youtube.com/watch?v=kx6DfrYfWnQ) (YouTube)  
      
     Instructions: Click on the first link above to watch the 10-minute
    lecture, which implements factorial as a function. Note that a
    *method* is often referred to as *function* in some programming
    languages. The above resource uses the term *function* instead of
    *method* as the concepts are explained using Python.  
      
     Next, click on the second link to watch “Diagramming What Happens
    with a Function Call.” The second video (10 minutes) verifies the
    function design by manually diagramming what happens statement by
    statement, and function call by function call. This lecture also
    introduces variable scoping.  
      
     Then, click on the link to “Recursive Factorial Function.” This
    third video (8 minutes) introduces recursion by implementing the
    factorial function using recursion. If you are familiar with proof
    by induction in mathematics, you will notice its conceptual
    similarity with recursion. Verification is done by running the
    program for several cases.  
      
     Finally, select the link for the “Comparing Iterative and Recursive
    Factorial Functions.” The fourth video (6 minutes) compares the loop
    implementation with the recursive implementation of the factorial
    function by stepping through them, side by side, using the same
    example inputs.  
      
     Watching these lectures and taking notes should take approximately
    1 hour and 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/).

-   **Assessment: The Saylor Foundation’s “Method Syntax in Java
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
    Activity”](http://www.saylor.org/site/wp-content/uploads/2013/10/CS101-6.1-Guide-to-Responding.pdf)
    (PDF)  
        
     Completing this activity should take approximately 1 hour.

**6.1.1 Method Declaration** <span id="6.1.1"></span> 
*A method must have a name but may not have parameters and a return
type. Pages 1 - 2 of the reading in Dr. George Kocur’s Introduction to
Computing and Engineering Problem Solving: “Lecture 6: Methods, Scope”
explain how a method is declared in Java. *

**6.1.2 Method Parameters** <span id="6.1.2"></span> 
*The parameter list contains variables that receive values from the
caller. These variables are local to the method. Method parameters are
also referred to as ‘arguments’ when they are substituted with specific
values during the method call. Method parameters are explained on page
2.*

**6.1.3 Return Types** <span id="6.1.3"></span> 
*As you read the section, you will learn that some methods do not return
any value, while others return a value of certain data type. A method
that does not return a value uses the keyword ‘void’ in the method
signature. Value returning methods are illustrated on page 2 and
non-value returning methods are illustrated in the example on page 3.*

**6.1.4 Scope of a Variable** <span id="6.1.4"></span> 
*The scope of a variable refers to where the value of the variable is
accessible or valid. A variable declared inside a method is only
available in that method. The values of variables declared as parameters
of a method are valid only inside that method as well. Read pages 4, 5,
and 6 to learn about the scope of a variable.*

**6.2 Overloaded Methods** <span id="6.2"></span> 
-   **Reading: Oracle’s *The Java Tutorials*: “Defining Methods”**
    Link: Oracle’s *The Java Tutorials*: [“Defining
    Methods”](http://docs.oracle.com/javase/tutorial/java/javaOO/methods.html) (HTML)  
      
     Instructions: Read this tutorial. It reviews how to declare and
    name a method in Java. It also discusses how to overload a method
    within a class. This reading will also cover the topics outlined in
    Subunit 6.2.1 and Subunit 6.2.2.  
      
     Reading this article and taking notes should take approximately 1
    hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 34A:
    Parameters, Local Variables, and Overloading”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter
    34A: Parameters, Local Variables, and
    Overloading”](http://chortle.ccsu.edu/java5/Notes/chap34A/ch34A_1.html) (HTML)
    (MP3)  
      
     Instructions: Read this chapter. Make sure to use the arrow keys to
    navigate through the slides. You may also click on the sound icon at
    the top of the page to listen to the MP3. This chapter reviews
    method parameters and local variables, as well as method overloading
    and method signature. This reading will also cover the topics
    outlined in Subunit 6.2.1 and Subunit 6.2.2.  
      
     Reading this chapter and taking notes should take approximately 2
    hours.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

**6.2.1 Method Overloading** <span id="6.2.1"></span> 
*Method overloading means two or more methods have the same name but
have different parameter lists: either different number of parameters or
different types of parameters. When a method is called, the
corresponding method is invoked by matching the arguments in the call to
the parameter lists of the methods. Pay attention to section 3 in
Oracle’s The Java Tutorials: “Defining Methods.” Pages 13 of the reading
in Central Connecticut State University: Bradley Kjell’s Introduction to
Computer Science Using Java: “Chapter 34A: Parameters, Local Variables,
and Overloading” explain how a method is overloaded in Java.*

**6.2.2 Signature of a Method** <span id="6.2.2"></span> 
*The name together with the number and type of the parameter list of a
method is called the signature of a method. The return type itself is
not part of the signature of a method. Note that pages 14 and 15 of the
reading in Central Connecticut State University: Bradley Kjell’s
Introduction to Computer Science Using Java: “Chapter 34A: Parameters,
Local Variables, and Overloading” discuss the signature of a method.*

-   **Assessment: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Fill in the Blanks
    Exercise for Parameters, Local Variables, and Overloading”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Fill in the
    Blanks Exercise for Parameters, Local Variables, and
    Overloading”](http://chortle.ccsu.edu/java5/Notes/chap34A/fillBlankCh34.html) (HTML)  
      
     Instructions: Complete the fill in the blanks exercise. Think of
    the correct response to fill in the blank, or write your answer down
    on a separate piece of paper. Then, click on the blank to reveal the
    correct answer.  
      
     Completing this assessment should take approximately 45 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.


