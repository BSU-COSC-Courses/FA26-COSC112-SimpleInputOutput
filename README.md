# Lab Assignment 2: Java Programming Fundamentals

## Overview

In this lab, you will practice fundamental Java programming concepts, including:

- Importing Java classes
- Creating and using `Scanner` objects
- Declaring variables and constants
- Reading input from the keyboard
- Performing arithmetic calculations
- Assigning and updating variable values
- Producing formatted output
- Testing a Java program with multiple sets of input
- Using GitHub and IntelliJ IDEA to complete and submit your assignment

You will **fork the instructor's repository**, clone your fork to your computer, complete the assignment in IntelliJ IDEA, and push your completed work back to **your own GitHub repository**.

> **Important:** Do not push your assignment directly to the instructor's repository. You will push your work to your own fork.

---

# Learning Objectives

By completing this lab, you should be able to:

1. Import and use the `Scanner` class.
2. Declare Java variables and named constants.
3. Read integer, string, and decimal input from the keyboard.
4. Perform arithmetic operations using variables and constants.
5. Store calculation results in variables.
6. Display formatted program output.
7. Compile, execute, and test a Java program.
8. Fork a GitHub repository.
9. Clone a GitHub repository using IntelliJ IDEA.
10. Commit changes using Git.
11. Push your completed assignment to your GitHub repository.

---

# Part 1: Fork the Instructor Repository

Before writing your program, create your own copy of the instructor's repository.

## What is a Fork?

A **fork** creates your own copy of a GitHub repository under your GitHub account.

For this assignment:

```text
Instructor Repository
        │
        │ Fork
        ▼
Your GitHub Repository
        │
        │ Clone
        ▼
Your Computer
        │
        │ Open
        ▼
IntelliJ IDEA
```

Your instructor's repository remains unchanged while you work.

---

## Step 1: Open the Instructor Repository

Your instructor will provide a GitHub repository link for this assignment.

Open the repository in your web browser.

You should see a repository similar to:

```text
COSC112-Lab-Assignment-2
```

---

## Step 2: Fork the Repository

On the GitHub repository page:

1. Click **Fork**.
2. Select your GitHub account as the destination.
3. Review the repository name.
4. Click **Create fork**.

GitHub will create a copy of the repository under your account.

Your repository should now look similar to:

```text
github.com/YOUR-USERNAME/COSC112-Lab-Assignment-2
```

> **Important:** Make sure you are working in the repository under **your GitHub username**, not the instructor's repository.

---

# Part 2: Clone Your Fork

After creating your fork, clone **your fork** to your computer.

## Step 1: Open Your Fork

Go to your newly created GitHub repository.

Verify that the repository belongs to your GitHub account.

For example:

```text
github.com/YourUsername/COSC112-Lab-Assignment-2
```

---

## Step 2: Copy the Repository URL

Click:

**Code → HTTPS**

Copy the repository URL.

It will look similar to:

```text
https://github.com/YourUsername/COSC112-Lab-Assignment-2.git
```

> Make sure the URL contains **your GitHub username**.

---

# Part 3: Clone the Repository in IntelliJ IDEA

## Step 1: Open IntelliJ IDEA

Launch **IntelliJ IDEA**.

From the Welcome screen, select:

**Clone Repository**

If you already have another project open:

1. Select **File**
2. Select **New**
3. Select **Project from Version Control**

---

## Step 2: Enter the Repository URL

In the **Get from Version Control** window:

1. Select **Git**.
2. Paste the URL for **your fork**.
3. Select the local folder where you want to store the project.
4. Click **Clone**.

Example:

```text
https://github.com/YourUsername/COSC112-Lab-Assignment-2.git
```

---

## Step 3: Open the Project

IntelliJ IDEA should open the cloned project.

If prompted:

- Select **Trust Project** if appropriate.
- Allow IntelliJ IDEA to finish loading the project.
- Wait for indexing to complete.

---

# Part 4: Verify Your Project

Before beginning the assignment, make sure you cloned the correct repository.

In IntelliJ IDEA, look at the project files.

You should see something similar to:

```text
COSC112-Lab-Assignment-2
│
├── README.md
└── src
    └── Exercise5.java
```

Your project may have a slightly different structure depending on the instructor's repository.

---

# Part 5: Create the Java Program

The assignment provides the following basic Java program structure:

```java
public class Exercise5
{
    public static void main(String[] args)
    {
        // variable declaration
        // executable statements
    }
}
```

You will place your declarations and executable statements in the appropriate locations.

---

# Part 6: Programming Requirements

Complete each of the following sections.

## A. Import Scanner

Write a Java statement that imports the `Scanner` class.

---

## B. Declare the Scanner Object

Declare `console` as a `Scanner` object that will be used to input data from the standard input device.

---

## C. Declare Named Constants

Declare and initialize the following named constants:

| Constant | Type | Value |
|---|---|---:|
| `SECRET` | `int` | `11` |
| `RATE` | `double` | `12.50` |

---

## D. Declare Variables

Declare the following variables:

| Variable | Type |
|---|---|
| `num1` | `int` |
| `num2` | `int` |
| `newNum` | `int` |
| `name` | `String` |
| `hoursWorked` | `double` |
| `wages` | `double` |

---

## E. Input Two Integers

Prompt the user to enter two integers.

Store:

- The first number in `num1`
- The second number in `num2`

---

## F. Display `num1` and `num2`

Output the values of `num1` and `num2`, clearly identifying each value.

For example:

```text
The value of num1 = 8 and the value of num2 = 5.
```

---

## G. Calculate `newNum`

Multiply the value of `num1` by `2`.

Then add the value of `num2`.

Store the result in `newNum`.

Conceptually:

```text
newNum = (num1 × 2) + num2
```

Display the value of `newNum`.

---

## H. Update `newNum`

Add the value of the named constant `SECRET` to `newNum`.

Display the updated value with an appropriate message.

---

## I. Input Last Name

Prompt the user to enter a person's last name.

Store the entered name in:

```text
name
```

---

## J. Input Hours Worked

Prompt the user to enter a decimal number between `0` and `70`.

Store the value in:

```text
hoursWorked
```

---

## K. Calculate Wages

Multiply the value of the named constant `RATE` by `hoursWorked`.

Store the result in:

```text
wages
```

Conceptually:

```text
wages = RATE × hoursWorked
```

---

## L. Display Employee Information

Your program should produce output in the following format:

```text
Name: [name]
Pay Rate: $[RATE]
Hours Worked: [hoursWorked]
Salary: $[wages]
```

For example:

```text
Name: Rainbow
Pay Rate: $12.50
Hours Worked: 45.50
Salary: $568.75
```

The assignment requires the output to display `name`, `RATE`, `hoursWorked`, and `wages`.

---

# Part 7: Complete Java Program

Combine all of your statements into one working Java program.

Your program should follow the general structure:

```java
// import classes

public class Exercise5
{
    public static void main(String[] args)
    {
        // variable declaration

        // executable statements
    }
}
```

Do **not** create separate programs for each part.

Part **(m)** requires you to create one Java program that tests the statements from parts **(a)–(l)**.

---

# Part 8: Run and Test Your Program

You must test your program using both sets of test data provided in the assignment.

## Test Case 1

```text
num1 = 13
num2 = 28
name = Jacobson
hoursWorked = 48.30
```

The assignment requires this test run.

---

## Test Case 2

```text
num1 = 32
num2 = 15
name = Cynthia
hoursWorked = 58.45
```

The assignment requires this second test run.

---

# Part 9: Run the Program in IntelliJ IDEA

## Step 1: Open `Exercise5.java`

In the IntelliJ **Project** panel, locate your Java source file.

For example:

```text
src
└── Exercise5.java
```

---

## Step 2: Run the Program

Click the green **Run ▶** button next to the `main` method.

You can also:

1. Right-click `Exercise5.java`.
2. Select **Run 'Exercise5.main()'**.

---

## Step 3: Enter the Test Data

The **Run** window will appear at the bottom of IntelliJ IDEA.

Enter each value when prompted.

Run the program once using **Test Case 1** and again using **Test Case 2**.

Check your output carefully.

---

# Part 10: Commit Your Work

Once your program is working correctly, save your files.

In IntelliJ IDEA:

1. Select **Git**.
2. Select **Commit**.
3. Review the files that have changed.
4. Enter a meaningful commit message.

For example:

```text
Complete Lab Assignment 2
```

5. Click **Commit**.

---

# Part 11: Push Your Work to GitHub

After committing your work, push the changes to **your fork**.

In IntelliJ IDEA:

1. Select **Git**.
2. Select **Push**.
3. Review the destination repository.
4. Click **Push**.

Your workflow should be:

```text
Local IntelliJ Project
        │
        │ Commit
        ▼
Local Git Repository
        │
        │ Push
        ▼
Your GitHub Fork
```

> **Important:** You should be pushing to your repository, not the instructor's repository.

---

# Part 12: Verify Your Submission

Open GitHub in your web browser.

Navigate to **your fork**.

For example:

```text
https://github.com/YourUsername/COSC112-Lab-Assignment-2
```

Verify that:

- Your Java file is present.
- Your most recent changes are visible.
- Your commit appears in the repository.
- Your completed program is stored in your GitHub repository.

---

# Understanding Your GitHub Workflow

The complete workflow for this assignment is:

```text
┌─────────────────────────────┐
│ Instructor GitHub Repository│
└──────────────┬──────────────┘
               │
               │ FORK
               ▼
┌─────────────────────────────┐
│ Your GitHub Repository      │
│       (Your Fork)           │
└──────────────┬──────────────┘
               │
               │ CLONE
               ▼
┌─────────────────────────────┐
│ Your Computer               │
│                             │
│      IntelliJ IDEA          │
└──────────────┬──────────────┘
               │
               │ CODE
               ▼
┌─────────────────────────────┐
│ Run & Test Java Program     │
└──────────────┬──────────────┘
               │
               │ COMMIT
               ▼
┌─────────────────────────────┐
│ Local Git Repository        │
└──────────────┬──────────────┘
               │
               │ PUSH
               ▼
┌─────────────────────────────┐
│ Your GitHub Repository      │
└─────────────────────────────┘
```

## Remember

**Fork → Clone → IntelliJ → Code → Test → Commit → Push**

---

# Important: Do Not Push to the Instructor Repository

Your instructor repository is the starting point for the assignment.

You should **fork it first** and then work from your own copy.

### Correct

```text
Instructor Repository
        ↓
      FORK
        ↓
Your Repository
        ↓
      CLONE
        ↓
    IntelliJ
        ↓
      CODE
        ↓
     COMMIT
        ↓
      PUSH
        ↓
Your Repository
```


# Submission Checklist

Before submitting your assignment, verify each item.

### GitHub

- [ ] I forked the instructor's repository.
- [ ] I verified that the repository belongs to my GitHub account.
- [ ] I cloned **my fork**, not the instructor repository.
- [ ] I opened the project in IntelliJ IDEA.
- [ ] I committed my changes.
- [ ] I pushed my changes to my GitHub fork.
- [ ] I verified my submission on GitHub.

### Java Program

- [ ] `Scanner` imported
- [ ] `console` Scanner object declared
- [ ] `SECRET` declared and initialized
- [ ] `RATE` declared and initialized
- [ ] Required variables declared
- [ ] Two integers successfully read
- [ ] `num1` and `num2` displayed
- [ ] `newNum` calculated correctly
- [ ] `SECRET` added to `newNum`
- [ ] Last name stored in `name`
- [ ] Hours worked stored in `hoursWorked`
- [ ] Wages calculated using `RATE`
- [ ] Employee/pay information displayed
- [ ] Test Case 1 completed
- [ ] Test Case 2 completed
- [ ] Program runs without errors

---

# Git Command Reference

You do not have to use the command line for this assignment if you complete the Git operations through IntelliJ IDEA.

However, these are the basic Git commands corresponding to the workflow:

```bash
# Check repository status
git status

# Add changes
git add .

# Commit changes
git commit -m "Complete Lab Assignment 2"

# Push changes to your fork
git push
```

---


**Your final code should be located in your own GitHub repository.**
