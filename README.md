# Project 4: College Admissions Calculator
## Group Members: Amanda Hernandez, Ryan Essem, Nnamdi Ede, Jim Chen
## Overview

This is our fourth and final project for INST126 at the University of Maryland, College Park. For this project, we were given free reign to develop a program that tackles a real world problem. And as a group, we decided to create a college admissions calculator. Although this program cannot take into account the human biases that occur throughout the college admissions process, it can take student GPAs and SAT scores and compare them to the average scores and GPAs of recently admitted freshmen to five different universities. We chose five colleges located in different parts of the country and each has a different acceptance rates to create a more well rounded program. 

The need this project addresses is the opportunity for students to quickly filter through a list of colleges and eliminate colleges they would not likely be admitted to. This aids in relieving the headache in finding the right colleges to apply to and develops a general safety assurance for the student. The student will also be able to search the five universities implemented into the program and gauge if they are academically fit. Overall, this program streamlines the ease of the college admissions, helps relieve applicant stress, and allows for better planning and academic focus. 

## How it works

When a user first runs the program, they will be asked to input their GPA and SAT score. Then, the national and institutional data that was collected will be read from a text file. As the program runs, it is comparing the user's inputs to each institution's average GPAs and SAT scores from admitted students. At the end, the program will return/print an individualized ordered list of the colleges that the user has the best chance of getting into based on their specific GPA and SAT score. The program will generate the list based on which college’s admissions data most closely matches the user's SAT score and GPA. The college listed first will be the college the user has the greatest chance of getting into and the college listed last will be the college the user has the least chance of getting into based on similar GPAs and SAT scores. 

## Update #1 (Nov. 25)

So far, we have collected the majority of the data that we need for this program. We are still looking for a national data set that contains high school student GPAs. We have also started experimenting with code and came up with code that can determine how many times a higher or equal GPA/SAT score appears in a data set compared to the GPA and SAT score entered by a user.

## Update #2 (Dec. 2)

After our last update, we decided to change how the code/overall project would be structured as well as what information it would return to the user. Initially, we wanted to create a program that would calculate a user’s chances of getting into five different schools based on only their GPA and SAT score. The program would then return an individualized rank (1-5) of the schools for the user. The ranking would have been based on how closely the user's GPA and SAT score matched the average GPAs and SAT scores of the five different universities. Instead of going forward with this plan, we wanted to create a more realistic and useful program for students which is explained in full above. We also updated our flowcharts to reflect the changes and designated sections of the code to each group member. 
