---
description: Grading other students' collegeboard performance tasks
title: Performance Task Grading 3
toc: true
comments: true
categories: [Week 24]
layout: post
---


# Response
## 3a

### 3.a.i
The purpose of this program is to help quiz users about CS and to help them learn different pieces of information relevant to the subject.

### 3.a.ii
The video showcases my program, which encompasses the following. The program displays the score, the question, and the list of options. The list of options is pulled from a backend API that has the question, answer, and incorrect answers. If the option clicked and submitted has the same text as the correct answer it will add 1 point. If the user hits submit without clicking anything, the program will prompt the user to click an option. If an incorrect answer was clicked, the program will alert the user about what the right answer was and restart the game. If 10 questions are answered correctly consecutively, than the program will return "You Win!"

### 3.a.iii
The input and output of this program, as showcased in my video, is based around the various buttons that are on the screen. The user clicks an option, then clicks submit. The program will then check whether or not the answer is correct. After doing this, the program will output whether or not the user got the answer right, then it will either add a point and load the next question or alert the user about what the right answer is and restart the game.

## 3b

### 3.b.i
![]({{site.baseurl}}/images/listproof.png)

### 3.b.ii
![]({{site.baseurl}}/images/listproof2.png)
Once the API data is recieved it displays the data with this code snippit.

### 3.b.iii
The program pulls correctAnswer, incorrectAnswer1, incorrectAnswer2, incorrectAnswer3, and question from the nested list (qAs) that the backend stores (as shown in image 1), and once the API data is recieved it displays the data with the showQuestion() function, as shown in image 2.

### 3.b.iv
The data in the list represents the different questions that could be shown to the user.

### 3.b.v
The nested list here manages complexity because it keeps all the question data very neatly organized, and it stores each question (each of which have attributes), with a variable. Then, it just plugs in those variables into another list. Without this system, not only would the code be much messier, but it may not even function, as the attributes are being stored in an sqlite table. Incorrect formmating and not using best practice here would destroy the sqlite table. If one wanted to add another question to the pool of possible questions, they would simply need to create another variable with the attributes, then plug said variable into the qAs list.


## 3c

### 3.c.i
![]({{site.baseurl}}/images/procedureproof1.png)

### 3.c.ii
![]({{site.baseurl}}/images/procedureproof2.png)

### 3.c.iii
The procedure checkAnswer is responsible for validating the user input, and whether or not an answer was even clicked before submitting. This is important for the program because this is what validates garbage and what distinguishes good input from bad input. This also is a core mechanic of the game, as the user must get 10 questions right consecutively to win.

### 3.c.iv
The procedure starts by checking whether or not an answer was clicked, if false, the procedure will immediately output "Please click an option.", if an option is selected then the procedure will check exactly what was selected and submitted. If the input is equal to the correct answer as defined in the API, then it will return "Correct Answer", and it will add 1 point to the total score, it will then load the next random question. If the input is incorrect, then the procedure will return an output of "Wrong Answer! Correct Answer: * insert correct answer here *." The procedure will then restart the game.

