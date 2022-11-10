---
title: Collegeboard Final Test Corrections/Reflection
toc: true
branch: master
badges: true
comments: true
author: Haseeb Beg
categories: [fastpages, jupyter, Week 12] 
layout: post
---

# Test Corrections:

## Question 6:
### Documentation for procedure with a loop:

In the following procedure, the parameter max is a positive integer.

PROCEDURE printNums(max)
    {
        count ← 1
        REPEAT UNTIL(count > max)
        {
            DISPLAY(count)
            count ← count + 2
        }
    }

Which of the following is the most appropriate documentation to appear with the printNums procedure?

Correct answer: B, Prints all positive odd integers that are less than or equal to max. The loop terminates when count exceeds max, so only values less than or equal to max are printed.

## Question 17: 
### Purpose of Internet protocols:

Which of the following is a primary reason for the use of open protocols on the Internet?

Correct answer: D, Open protocols provide a way to standardize data transmission between different devices. Protocols are agreed-upon sets of rules that specify the behavior of a system. Protocols used on the Internet enable devices from different manufacturers to communicate in a standard way.

## Question 43:
### Value of x after REPEAT UNTIL block:

Consider the following code segment.

x ← 0 
result ← 0
REPEAT UNTIL x is greater than 5
        result ← result plus x
        x ← x plus 1 

What is the value of result after the code segment is executed?

Correct answer: C, The variables x and result are initialized to 0. Inside the loop, result is increased by x and x is increased by 1. The loop terminates when x exceeds 5. Therefore, result is assigned the sum of the integers from 0 to 5, or 15.

## Question 45:
### Values of counts after traversing theList:

Consider the following code segment.

theList ← [-2, -1, 0, 1, 2]
count1 ← 0
count2 ← 0
FOR EACH value IN theList
{
    IF(value > 0)
    {
        count1 ← count1 + 1
    }
    ELSE
    {   
        count2 ← count2 + 1
    }
}

What are the values of count1 and count2 as a result of executing the code segment?

Correct answer: B, The code segment iterates through each element in the list, incrementing count1 for each positive value and incrementing count2 otherwise. The list contains two positive values, so count1 is 2 and count2 is 3.

# Reflection:

Overall, the test went pretty well. I did increase my understanding of the Collegeboard pseudo-code since the last quiz. However, there are still gaps in my understanding. For one, I had to mostly guess the questions on bits, and I did have to communicate with our group with members that had not completeted the assessment at the time of collaberation to understand the concepts involved. One key thing I learned was how sensors pull at multiple intervals per second measured in Hz. 
