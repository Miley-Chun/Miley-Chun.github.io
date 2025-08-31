---
layout: project
type: project
image: img/Bank.jpeg
title: "Bank Database"
date: 2025-04-26
published: true
labels:
  - User interface
  - Programming
  - C++
summary: "In my Program Structure class, ICS 212, that I took spring 2025 I worked to create a Bank Database."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

Over the course of 6 weeks I worked to implement a Bank Database in my ICS212 class. In this program structure class I learned to include a working user interface along with a modifyable database. The database holds numbered bank accounts with information about the holders name, home address and account number. Through the user interface, authority to add, delete, find, and print all account records was available. Users were also given the option to quit, which resulted in closing the program. The user interface would continuously prompt the user with these options until the user would decide to quit and exit the Bank Database. This program saved the data in the Bank Database in a file which would automatically be written to when the program was closed. Upon returning to the program after, the same Database information would be accessed. 

This project was written entirely in C++, which was a main focus for this computer science class. The data in the Database was structured in a linked list in order to be flexible. The linked list allowed the database to have anywhere from 1 to 500 records depending on what the user might need or request. The head of the list of bank account records was stored as a pointer to a pointer value. Each of the modifyer functions, such as the add, delete or find functions were run based on the user input but also threw warnings when bad inputs were given. 

From this project I was able to learn and grow my knowledge in C and C++. I worked a lot with pointers and was able to get a lot of experience with dereferencing objects and understanding how space is taken in memory. While this was a solo project, I was given a lot of guidence from my professor and TA in this course. This allowed me to smoothly understand the topics we talked about in class and apply them to this project.

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
