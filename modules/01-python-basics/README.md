# Module 1: Python Basics

Harvard-style lecture for students with zero technical background.

Imagine this is the first day of CS50 at Harvard, except it is taught for a student who has never written code before.

The biggest mistake beginners make is thinking: "Programming is about code."

It is not. Programming is about solving problems. Code is simply the language we use to tell the computer what to do.

The SkillsUSA competition is not really testing whether you know Python. It is testing whether you can analyze a problem, organize information, and create a solution.

## Lesson 1: What is Programming?

Imagine you walk into McDonald's and say: *"I want 2 Big Macs and 1 Coke."*

The employee knows exactly what to do, because you gave instructions. A computer works the same way.

Programming is simply giving instructions to a computer, step by step.

### Real-life example

```text
Wake up
↓
Brush teeth
↓
Eat breakfast
↓
Go to school
```

This is called an **algorithm**: a list of steps. Programming is writing algorithms in a language a computer understands.

## What is Python?

Python is a programming language. Just like people speak English, Vietnamese, or Spanish, computers understand Python, Java, C++, or JavaScript.

Python is popular because it looks very close to English:

```python
print("Hello")
```

Even without experience, you can probably guess it prints `Hello`. Read it like English: *Print Hello.*

```python
print("Welcome to Dallas College")
```

Read it as: *Show "Welcome to Dallas College".* Python was designed to be readable, which is why it is a great first language before moving on to Java or C++.

## Think Like a Computer

Suppose I tell you: *"Make me a sandwich."* A computer would be confused, because that instruction is not detailed enough. It needs:

```text
Get bread
Put bread on plate
Add ham
Add cheese
Put another bread slice on top
```

Computers only understand very precise instructions.

### A computer is not smart

A computer is a machine that follows instructions. It has no common sense.

If I tell you *"Put milk in the refrigerator,"* you automatically understand:

```text
Open refrigerator
Place milk inside
Close refrigerator
```

A human fills in the missing steps. A computer does not. It needs every single step. This is why programmers exist: programmers write instructions, and computers execute them.

### Programming is problem solving

```text
Thinking
↓
Planning
↓
Writing Instructions
↓
Testing
```

Thinking comes first. Many people believe programming means typing code. In reality, programming means problem solving, and the code is the smallest part.

## The 3 Things Every Program Does

Almost every program in the world does three things:

```text
Input
↓
Process
↓
Output
```

### Example: ATM machine

- **Input:** You enter "Withdraw $20".
- **Process:** The computer checks whether the account has enough money.
- **Output:** Cash is dispensed.

### Example: SkillsUSA-style calorie calculator

- **Input:** The user enters Big Macs = 2, Fries = 1, Shake = 1.
- **Process:** The computer calculates calories.
- **Output:** `Total Calories = 2034`

This is the same structure as the Calorie Calculator project in this curriculum.

### Example: DoorDash

- **Input:** Phuong orders Pho.
- **Process:** The restaurant cooks the food and a driver delivers it.
- **Output:** Pho arrives at your door.

### Example: TikTok

- **Input:** You tap the app.
- **Process:** It loads your account, videos, and recommendations.
- **Output:** The feed is displayed.

### Example: a Python grade program

- **Input:** A student enters a score.
- **Process:** The computer calculates the average.
- **Output:** The grade is displayed.

All software follows this model.

## Your First Python Program

Type:

```python
print("Hello, Phuong!")
```

Run it. Output:

```text
Hello, Phuong!
```

Congratulations. You just told the computer: *display this text.*

## Understanding `print()`

Think of `print` as "show this on the screen."

Imagine a magician. The audience cannot see what is inside the box until the magician opens it. That is what `print()` does.

```python
name = "Phuong"
```

The computer remembers it, but the screen shows nothing.

```python
name = "Phuong"
print(name)
```

Output:

```text
Phuong
```

The hidden information becomes visible.

```python
print("Dallas College")
```

Output:

```text
Dallas College
```

### Practice

```python
print("I am learning Python.")
print("I want to compete in SkillsUSA.")
```

## What Are Variables?

This is the most important concept. Imagine a labeled box. The label says `Name` and inside the box is `Phuong`. That is a variable.

> A variable is a labeled container that stores information.

```python
name = "Phuong"
```

Box label → `name`, inside box → `Phuong`.

```python
age = 30
```

Box label → `age`, inside box → `30`.

```text
+--------------+
| name         |
+--------------+
| Phuong       |
+--------------+
```

### Read code like English

Do not read `age = 30` as "age equals thirty." Read it as: **put 30 into the box called `age`.** This is one of the biggest mindset shifts for beginners.

### Mental exercise

```python
city = "Dallas"
```

- What is the box called? `city`
- What is inside? `Dallas`

```python
gpa = 4.0
```

- What is the box called? `gpa`
- What is inside? `4.0`

### Why are variables important?

Netflix has hundreds of millions of customers. It cannot manually remember each name, email, and subscription. Variables store information such as username, password, subscription, and watch history.

```python
username = "phuong123"
```

## Data Types

Computers store different kinds of information.

| Type | Example |
| --- | --- |
| Text (string) | `name = "Phuong"` |
| Whole number (integer) | `age = 30` |
| Decimal number (float) | `gpa = 3.95` |
| True or false (boolean) | `is_student = True` |

## Let's Build Something

```python
name = "Phuong"
college = "Dallas College"
major = "Software Development"

print(name)
print(college)
print(major)
```

Output:

```text
Phuong
Dallas College
Software Development
```

## The Golden Rule of Programming

Many beginners think: "I need to memorize code." Wrong.

Professional programmers do not memorize everything. They learn:

```text
Problem
↓
Logic
↓
Code
```

Always ask *"What problem am I solving?"* before asking *"What code should I write?"*

### The Harvard Question

Do not ask: *How do I write code?* Ask:

- What information am I storing?
- What problem am I solving?
- What result do I want?

Then the code becomes obvious.

## Mini Challenge

Create the variables `favorite_food`, `favorite_drink`, and `favorite_movie`, then display all three.

Example values:

```python
favorite_food = "Pho"
favorite_drink = "Milk Tea"
favorite_movie = "Frozen"
```

## SkillsUSA Connection

The SkillsUSA competition requires contestants to build programs, create portfolios, demonstrate solutions, and participate in presentations and interviews.

The first big challenge, the Calorie Calculator, starts with the same concepts:

```text
Variables
↓
Input
↓
Calculations
↓
Output
```

Before you can build the calculator, you must master:

- [x] `print()`
- [x] Variables
- [x] Data types
- [x] Basic problem solving

These are the foundation of every future project in the learning roadmap:

```text
Learn
↓
Practice
↓
Mini Challenge
↓
SkillsUSA Project
↓
Portfolio Project
↓
Presentation
↓
Mock Interview
```

## End-of-Lesson Reflection

If you understand these 5 ideas, you have mastered Module 1:

- [x] Computers follow instructions
- [x] Programming is problem solving
- [x] Every program uses Input → Process → Output
- [x] Variables are labeled boxes
- [x] `print()` displays information

Next, Module 2 builds on these ideas:

```text
Variables
↓
input()
↓
User Interaction
↓
Math Operations
↓
Calorie Calculator
```

## Homework

Create a file called `student_profile.py`. Write a program that stores `name`, `age`, `college`, `major`, and `dream_job`, and prints:

```text
Student Profile
---------------
Name: Phuong Nguyen
Age: 30
College: Dallas College
Major: Software Development
Dream Job: Software Engineer
```

When you are done, send your code for review like a Harvard CS50 professor and a SkillsUSA judge would.
