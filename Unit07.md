---
layout: default
title: "CS101: Introduction to Computer Science I"
course_description: "An introductory course that covers the basic concepts, nomenclature, and historical perspective of computers and computing. Includes an introduction to software development and object-oriented programming."
next: ../Unit08
previous: ../Unit06
---
**Unit 7: Arrays** <span id="7"></span> 
*This unit discusses Arrays. An Array is a fixed-size data structure
that allows elements of same data type to be stored in it. Each array
element has a unique index associated with the value it stores. Arrays
are commonly used in a loop structure such as for loops. In addition,
this unit introduces two-dimensional arrays and its applications.*

**Unit 7 Time Advisory**  
This unit should take you approximately 7 hours to complete.  
  
 ☐    Subunit 7.1: 3 hours  
  
 ☐    Subunit 7.2: 2 hours  
  
 ☐    Subunit 7.3: 2 hours

**Unit7 Learning Outcomes**  
Upon successful completion of this course, the student will be able to:
-   declare and use one-dimensional arrays;  
      
-   create, initialize, and access multi-dimensional arrays; and  
      
-   use arrays to enhanced *for *loop to iterate over its elements.

**7.1 Introduction to Arrays** <span id="7.1"></span> 
-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 46:
    Arrays”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter 46:
    Arrays”](http://chortle.ccsu.edu/java5/Notes/chap46/ch46_1.html) (HTML)
    (MP3)  
      
     Instructions: Read this chapter. Make sure to use the arrow keys to
    navigate through the slides. You may also click on the sound icon at
    the top of the page to listen to the MP3. This chapter introduces
    *arrays*, a common data structure used to store data of same type.
    This reading will cover the topics outlined in Subunit 7.1.1 and
    Subunit 7.1.2.  
      
     Reading this chapter and taking notes should take approximately 1
    hour and 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Reading: Oracle’s *The Java Tutorials*: “Arrays”**
    Link: Oracle’s *The Java
    Tutorials*: [“Arrays”](http://docs.oracle.com/javase/tutorial/java/nutsandbolts/arrays.html) (HTML)  
      
     Instructions: Read this article. This tutorial explains how to
    create, initialize, and access arrays. It also discusses how to copy
    arrays and manipulate array elements. This reading will cover the
    topics outlined in Subunits 7.1.1 and Subunit 7.1.2.  
      
     Reading this article and taking notes should take approximately 1
    hour and 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**7.1.1 Concept of Arrays** <span id="7.1.1"></span> 
*An array is a data structure that can contain a fixed number of values
of a single type. The length of an array, i.e., the number of elements
the array can hold, is established when the array is created. Read pages
1 and 2 of Central Connecticut State University: Bradley Kjell’s
Introduction to Computer Science Using Java: “Chapter 46: Arrays” to
learn about the concept of arrays.Pay attention to section 1 and 2 in
Oracle’s The Java Tutorials: “Arrays.”*

**7.1.2 Use of One-Dimensional Arrays** <span id="7.1.2"></span> 
*A one-dimensional array occupies a consecutive block of memory. Each
element in the array can be accessed through an index. The range of the
index goes from zero to the size of the array minus one. A for loop is
commonly used to initialize the values in a two-dimensional array Read
pages 3 through 10 of Central Connecticut State University: Bradley
Kjell’s Introduction to Computer Science Using Java: “Chapter 46:
Arrays.” Pay attention to section 3 and 4 in Oracle’s The Java
Tutorials: “Arrays.”*

-   **Assessment: The Saylor Foundation’s “Use of One-Dimensional
    Arrays”**
    Link: The Saylor Foundation’s [“Use of One-Dimensional
    Arrays”](http://school.saylor.org/mod/quiz/view.php?id=1743) (HTML)  
        
     Instructions: Complete this multiple-choice quiz, which will assess
    your understanding the use of one-dimensional arrays.  
        
     Completing this assessment should take approximately 30 minutes.

**7.2 Two-Dimensional Arrays** <span id="7.2"></span> 
-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 49C:
    Two-Dimensional Arrays”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter
    49C: Two-Dimensional
    Arrays”](http://chortle.ccsu.edu/java5/Notes/chap49C/ch49C_1.html) (HTML)
    (MP3)   
      
     Instructions: Read this chapter. Make sure to use the arrow keys to
    navigate through the slides. You may also click on the sound icon at
    the top of the page to listen to the MP3. This chapter introduces
    two-dimensional arrays. This reading will cover the topics outlined
    in Subunit 7.2.1 and Subunit 7.2.2.  
      
     Reading this chapter and taking notes should take approximately 1
    hour and 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

-   **Assessment: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Quiz on 2D Arrays”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Quiz on 2D
    Arrays”](http://chortle.ccsu.edu/java5/Notes/chap49C/chap49CquizRev2.html) (HTML)  
      
     Instructions: Work through the quiz. Click on the “Grade Quiz”
    button at the end to see how many answers you got correct as well as
    to reveal the correct answers.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.

**7.2.1 Concept of Two-Dimensional Arrays** <span id="7.2.1"></span> 
*A two-dimensional array is a data structure that contains a collection
of cells laid out in a two-dimensional grid, similar to a table with
rows and columns although the values are still stored linearly in
memory. Read pages 1 through 3 to learn about the concept of
two-dimensional arrays.*

**7.2.2 Use of Two-Dimensional Arrays** <span id="7.2.2"></span> 
*Each cell in a two-dimensional array can be accessed through two
indexes that specify the row number and column number respectively.
Like-one dimensional array, the range of each index is from zero to the
size of the row or column minus one. A nested for loop is commonly used
to initialize the values in a two-dimensional array. Read pages 4
through 9 to learn about how to declare a two-dimensional array and
access the elements in the array.*

**7.3 Common Array Algorithms** <span id="7.3"></span> 
-   **Web Media: Central Connecticut State University: Bradley Kjell’s
    *Introduction to Computer Science Using Java*: “Chapter 47: Common
    Array Algorithms”**
    Link: Central Connecticut State University: Bradley
    Kjell’s *Introduction to Computer Science Using Java*: [“Chapter 47:
    Common Array
    Algorithms”](http://chortle.ccsu.edu/java5/Notes/chap47/ch47_1.html) (HTML)
    (MP3)   
      
     Instructions: Read this chapter. Make sure to use the arrow keys to
    navigate through the slides. You may also click on the sound icon at
    the top of the page to listen to the MP3. This chapter discusses how
    a *for *loop can be used to iterate over the elements of an array.
    In addition, it also discusses enhanced *for *loop. The chapter
    demonstrates use of arrays to solve common problems such as finding
    sum, average, maximum, and minimum values of numbers stored in
    array. Pay attention to some of the common programming errors one
    can make while using arrays.  
      
     Reading this chapter and taking notes should take approximately 2
    hours.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
    It is attributed to Bradley Kjell and Central Connecticut State
    University.


