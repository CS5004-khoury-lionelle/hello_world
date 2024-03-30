# Aloha World Homework Instructions

Aloha! This assignment is meant to give you an introduction to the java programming language and object oriented design. The assignment is to debug the provided java application, and then add a new java object from scratch giving you both the experience of a working java program, and writing a file from scratch. Overall, the goal is for you to learn the homework submission process, and get a feel for the java programming language.

## Table of Contents
- [Aloha World Homework Instructions](#aloha-world-homework-instructions)
  - [Table of Contents](#table-of-contents)
  - [Learning Objectives](#learning-objectives)
  - [Javadoc](#javadoc)
  - [Assumptions](#assumptions)
  - [Instructions](#instructions)
    - [Part 1: Cloning Your Repository into your IDE](#part-1-cloning-your-repository-into-your-ide)
      - [Part 1.1: Updating the README.md](#part-11-updating-the-readmemd)


## Learning Objectives

* Learn how to debug a java application along with basic java syntax
* Learn how to write a single java class 
* Practice testing using JUnit tests
* Be able to answer some introductory questions about java syntax and object oriented design
* Write a UML diagram for a java application
* Learn about git and github 
* Learn how to use gradescope combined with github for homework submission
* Learn markdown syntax used for reports and README files for homework assignments
* Learn basic mermaid syntax used for drawing diagrams in markdown

An observant reader will notice that many of the learning objectives have very little to do with the code itself. This is intentional. The goal of this assignment is to get you comfortable with the homework submission process, and to get your "ecosystem" setup for this class. Just as importantly, this classes focuses heavily on industrial practices, and we want to get you comfortable with the tools you will be using in the industry. Github and Markdown are both tools heavily used in industry, so we will be using for all our assignments. 

## Javadoc

* [Javadoc](https://cs5004-khoury-lionelle.github.io/hello_world/student/package-summary.html) - This is the link to your javadoc for any code we provide. We will have javadoc for all code we provide, so you can also get an easier understanding of what the code does.


## Assumptions

This homework assumes you have installed your favorite IDE (IntelliJ or VS Code) and installed the recommended plugins or extension as listed in the [5004 Resources](https://github.com/CS5004-khoury-lionelle/Resources) repository. Additionally, you will need to make sure gradle and java are installed. You can confirm they are installed by going to the command line and typing `java -version` and `gradle -version`. If you get a version number, you are good to go. If you get an error, you will need to install them or check your environment variables.

You should have also clicked on the link in the Canvas assignment shell to generate your github repo from the github classroom. As a reminder, you need a Github.com account! Don't use the Khoury Github Enterprise account, as it will not work with github classroom. 


## Instructions

This assignment is broken up into multiple parts. Remember, it is a two week assignment that will take **TIME** to complete! Do not delay getting it started, even if you have to take breaks and come back to it. Throughout the semester, we will be adding more and more to the assignments, so it is important to get a good start on them.


### Part 1: Cloning Your Repository into your IDE

After your starter repository is created, you will need to clone it into your IDE. To find your code, go to the github repository that was created for you, and find the green "Code" button. Click on it, and then copy the URL that is shown.

Here is a screenshot, though the graphics change from time to time, so it may not be exact.

![Clone Repo](clone_example.png)


Then go into your IDE, and find the clone repository (or get from version control) option. For IntelliJ IDEA, it looks like the following:


![IntelliJ Clone](intellij_clone_example.png)

For VS Code, it looks like the following:

![VS Code Clone](vscode_git.png) 

Note: if git is not installed on your computer, you won't see the option to clone from version control. You will need to install git on your computer.

In both cases, use the URL copied from the github repository to clone the repository into your IDE. 


#### Part 1.1: Updating the README.md

For this class, you end up submitting your homework by checking in your entire github repository, and then submitting to gradescope. You have to submit every time you want the autograder to run, so don't forget. 

In the main directory of your repository, you will find a file called [`README.md`](../README.md). This file is a markdown file that is used to describe your repository. You should update this file with your name, github account name, and the link to your repository. 

After you do this update, follow the steps in your IDE to commit your changes, and push to github. 

Take a look at your repository on github to make sure the changes are there.

After every major change to your code, you should commit and push to the repository.