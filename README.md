# Week 1 — Python Basics: Personal Introduction Program
## Project Overview

This project is a beginner-friendly Python program that collects basic user information—such as name, age, and hobby—and displays a personalized welcome message.
It helps you understand how Python handles input, output, variables, and simple string formatting. This is your first step into programming fundamentals.

## Project Goals & Objectives

Understand what programming is

Learn basic Python concepts (variables, strings, input/output)

Write your first functional Python script

Learn program flow: taking input → storing values → printing output

Build a complete working project with documentation and testing

Practice real-world submission format (README, file structure, testing, screenshots)

## Setup Instructions
1. Install Python

Download Python 3.10+ from: https://www.python.org/downloads/

After installation, verify using:

python --version

2. Run the Program

Open your terminal or VS Code

Navigate to your project folder

cd Week1_Python_Intro


Run the script:

python personal_intro.py

## Code Structure

The folder should look like this:

Week1_Python_Intro/
│── personal_intro.py      # Main Python program
│── README.md              # Documentation file
│── requirements.txt       # Project requirements
└── screenshot.png         # Program output screenshot

## Program Code (personal_intro.py)
name = input("What is your name? ")
age = input("How old are you? ")
hobby = input("What is your favorite hobby? ")

print(f"\n Welcome {name}!")
print(f"You are {age} years old and love {hobby}.")

## Technical Details

This project uses the following Python concepts:

1. Variables

Used to store user input:

name

age

hobby

2. input() Function

Takes information from the user.

3. print() Function

Displays output to the screen.

4. f-strings

Used to format text cleanly for the welcome message.

5. Basic Program Flow

Ask user for details

Store details

Display formatted message

This project does not require loops, conditions, or advanced logic—just core fundamentals.

## Visual Documentation

A screenshot named screenshot.png is included to demonstrate the program running in the terminal, showing both input and output.

## Testing Evidence
Test Case 1

Input:

Name: Priya
Age: 20
Hobby: Sleeping


Output:

Welcome Priya! 
You are 20 years old and love Sleeping.

Test Case 2

Input:

Name: Ram
Age: 21
Hobby: Coding


Output:

Welcome Ram! 
You are 21 years old and love Coding.

## What I Learned

Throughout this project, I learned:

How to install and run Python programs

How to write my first script using input() and print()

How variables store different types of information

What strings are and how to format them

How simple programs execute step-by-step

How to organize files properly for a clean project structure

How to prepare documentation for a real submission

This project gave me confidence to continue my Python learning journey.