# Discrete Structures (CMPSC 102) Final Project

This repository contains information about the final project deliverables. This final project invites students to find an area of Discrete Structures in which to complete a demonstration of some mathematical property in Python code. The demonstration can be anything mathematic which has been placed into code.

## Dates

Handed out: 18 November 2022

Presentations: 5th December - 9th December, 2022

Final Submission Due: 16th December 2022, 7:00am

![logo](graphics/hands.png)
Caption 1: You are invited to create a practical demonstration for Discrete Structures! Your topic can cover any concept from the course, or that should be in the course. Interestingly, ideas may come from all over mathematics but if you know how to program, then you are in a better position to study and demonstrate those ideas. 

## Contents

- [Objectives](#Objectives)
- [Timeline](#Timeline)
- [Motivation](#Motivation)
- [Research Task](#Research-Task)
- [Individual Tasks](#Individual-Tasks)
- [Sample Research Questions](#Sample-Research-Questions)
- [Cloning Your Repository](#Cloning-Your-Repository)
- [GatorGrade](#GatorGrade)
- [Assessment](#Assessment)



## Objectives

  * To learn and understand a mathematical concept
  * To learn and understand how to write the concept into computer code.
  * To gain experience in demonstrating concepts using code.

## Timeline

The below due dates cannot be extended. An assignment is considered late if it has been submitted after the deadline.

Activity                                                                      | Deadline
----------------------------------------------------------------------------- | ------------------------------------------
`writing/proposal.md`: Create a team and complete proposal of study. Discuss relevance to Discrete Structures. | By end of class; 2:20pm on Monday, November 21st, 2022
`writing/progress.md`: Demonstrate progress during class work time (commits from each member). Addition of data, references, notes, etc. to show that your project is building. | By end of lab; 4:20pm on Monday, November 28th, 2022
`writing/report.md`: Final report due.| By 19th December 2022, 9:00am
Presentation of research and discussion of results | 5th December - 9th December, 2022 (Exact date TBA)

## Motivation

Throughout the semester in Discrete Structues, we have studied many artifacts from mathematics that have made their way into computer science. As we studied the below list of structures, we took care to examine how to use them in Python code we spent some time to recognize where they originated in mathematics.  

  * Variables: Integers, Floats, Booleans, Strings, 
  * Lists, Dictionaries, Sets, Tuples
  * Monoids, Generator functions (regular functions), lambda functions
  * Advanced: Finding square roots using functions, studying 3x+1 sequence convergence, calculating Fibonacci sequences using different techniques 
  * Lots of other fascinating concepts

## Research Task

Each week our lessons, assessments and surveys made clear connections between the mathematical concepts, with those from Computer Science by using demonstrations. These demonstrations were written in Python code and allowed the members of the class to see and understand mathematical methods at play in computer code. In addition to learning the mechanisms behind the computation, students were given opportunities to learn and practice better code writing skills for Python.

To create these demonstrations for lessons in the course, it was first necessary to conduct some meaningful research in basic mathematics to be able to connect a concept to some structure in Computer Science.

In this final project, you are invited to work as an individual, or as a group of _two or three_ members, to complete similar research in mathematics to create a interesting demonstration for the class. 
In particular, you are to find some mathematical quality, mechanism, equation, function or a similar construct from mathematics, that can be modelled and demonstrated in  Python code. 

### Individual Tasks

The tasks of the project are the following.

  * __Literature Review__: Find something worth a demonstration by reading mathematical articles, online sites, wikipedia and etc. Once you have found the mathematical concept, learn how it works to be able to reproduce its logic using computer code. If there are unusual cases, be sure to learn some of them for your upcoming demonstration.

  *  __Programming a Demonstration__: Once you have understood the principles behind your chosen mathematical concept so that you can teach it to your peers, begin work on writing computer code to showcase the concept. Be sure to make your code elegant and readable to facilitate comprehension.

  * __Presentation__: Now that your code works to describe concept, you are ready to present the concept and its assciated code. Here you are to discuss the concept, and make it perfectly clear that mathematics behind the concept are absolutely fascinating. Next, you will run your Python code to show your colleagues the concept i action (in some way). This demonstration will be live, meaning that you will prepare your laptop to be able to run the demonstration in front of the class.
  
### Sample Research Questions

Potential research questions may be comparable to the following:

  * We studied sequence convergence of the _3XPlus1_ system of equations. Can you change the rules in some way to demonstrate what happens?
  * Fibonacci numbers were a focus in the class. Can you find yet another way to calculate these sequence values to demonstrate?
  * We worked with Morse Code. Can you create a new mapping system to code and decode text using a different type of system or encryption? for example, could your code use [Huffman](https://en.wikipedia.org/wiki/Huffman_coding) codes to send messages?
  * Can you look up a Prime number tester by [Miller and Rabin](https://en.wikipedia.org/wiki/Miller%E2%80%93Rabin_primality_test) to implement some computer code to demonstrate how it works?
  * Can you find some other logic-driven system to implement in Python code for a demonstration?

## Project Access

You can access this assignment by clicking the link provided to you in lab.
Once you click this link it will create a GitHub repository that you can clone
to your computer. Specifically, you
will need to use the `git clone` command to download the project from GitHub to
your computer. Now you are ready to add source code and documentation to the
project!

## Cloning Your Repository

To use the link that you were given in class, please follow the steps below.

- Click on the link and accept the assignment.
- Once the importing task has completed, click on the created assignment link which will take you to your newly created GitHub repository for this lab.
- Clone this repository (bearing your name) and work locally.
- As you are working on your lab, you are to commit and push regularly. The commands are the following.

```
git add -A
git commit -m ``Your notes about the commit here''
git push
```

After you have pushed your work to your repository, please visit the repository at the GitHub website (you may have to log-in using your browser) to verify that your files were correctly sent.

### Individually

* If you are working alone, you will still need to establish a group name due to the setup in GitHub Classrooms.

### As a Group

* If you are working in a group, first, decide who will be in your group before you click on the link. In group assignments, _only one person will be creating the team while the other team members will join that team._  The selected person of the team should click on the link of the assignment sheet to establish a group name that is unique and descriptive. Use the `Create a new team` option.

* Now the other members of the team can click on the assignment link and select their team from the list under _Join an Existing Team._ When other team members join their group in GitHub Classroom, a team is created in our GitHub organization. Every team member will be able to push and pull to their team’s repository.

* As you work in groups, please work collaboratively and leave no-one out of the loop of your thinking: working in groups is one of the best ways to add focus to your project and to develop ideas (by brainstorming).

## GatorGrade

You can check the baseline writing and commit requirements for this lab assignment by running department's assignment checking `gatorgrade` tool. To use `gatorgrade`, you first need to make sure you have Python3 installed (type `python --version` to check). If you do not have Python installed, please see:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [How to Install Python 3 and Set Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Then, if you have not done so already, you need to install `gatorgrade`:

- First, [install `pipx`](https://pypa.github.io/pipx/installation/)
- Then, install `gatorgrade` with `pipx install gatorgrade`

Finally, you can run `gatorgrade`:

`gatorgrade --config config/gatorgrade.yml`

## Deliverables
See due dates in the above Timeline table.

* Address `writing/proposal.md` for proposal.

* Address `writing/progress.md` for progress.

* Address `writing/report.md` for final report.


## Assessment

The grade that a student receives on this assignment will have the following components.

- **GitHub Actions CI Build Status [up to 5%]:** For the project repository associated with this assignment students will receive a checkmark grade if their last before-the-deadline build passes. This is only checking some baseline writing and commit requirements as well as correct inclusion of files. An additional reduction will given if the commit log shows a cluster of commits at the end clearly used just to pass this requirement. An addition reduction will also be given if there is no commit during lab or class project work times. All other requirements are evaluated manually.

- **Timely Submission of Proposal and Progress documents [up to 20%]:** Students will also receive a check mark for the submissions for `writing/proposal` and `writing/progress.md` that demonstrate clear project idea and sufficient progress and contain all information requested in those documents' TODO tags. 

- **Mastery of technical Skills [up to 50%]:**: Students will also receive a check mark grade when their project demonstrates proficiency in posing, understanding, and correctly responding to Discrete Structures question(s). A part of this grade is based on the responses to the writing questions presented in the `report.md`. The submitted writing should have correct spelling, grammar, and punctuation in addition to following the rules of Markdown and providing conceptually and technically accurate answers. Additionally, all steps of the inquiry must be clearly demonstrated and all visual output must be included in the report. Any produced code must be included in the `src/` directory of the project repository.

- **Mastery of Oral Communication [up to 25%]**: Students will receive a portion of their assignment grade when the team presentation shows a complete understanding of the completed work and ability to communicate its ideas.

