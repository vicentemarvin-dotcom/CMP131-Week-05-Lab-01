# CMP 131 – Python Programming


> **Required file location:** Keep every Python file directly in the repository root. Do not create a `src` folder.

## Week 5 – Lab 1: Temperature Categories and Even or Odd

**Total Points: 100**

* Program 1: Temperature Category — 50 points
* Program 2: Even or Odd — 50 points

### Learning Objectives

After completing this lab, students should be able to:

* Accept numeric input from the user.
* Convert user input to an appropriate numeric data type.
* Use comparison operators to evaluate values.
* Use `if`, `elif`, and `else` statements.
* Use temperature ranges in conditional statements.
* Use the remainder operator to determine whether an integer is even or odd.
* Display clear and appropriately formatted results.
* Test conditional statements using different input values.
* Use comments to explain the major sections of a program.

## Assignment Overview

Create two separate Python programs that use conditional statements.

The first program will ask the user to enter a temperature in degrees Fahrenheit and categorize it as `Cold`, `Warm`, or `Hot`.

The second program will ask the user to enter an integer and determine whether the number is even or odd.

Create the following Python files:

* `temperature_category.py`
* `even_or_odd.py`

Both programs must accept input from the user, use conditional statements, and display a clear result.

The instructor is not providing completed Python code or an exact output design. Students must design, write, and test their own programs.

# Program 1: Temperature Category

**Points: 50**

## Program Description

Create a Python program that asks the user to enter a temperature in degrees Fahrenheit.

The program must compare the temperature with the required ranges and categorize it as:

* `Cold`
* `Warm`
* `Hot`

The program must display the temperature entered by the user and its corresponding category.

## Required Python File

Create a Python file named:

`temperature_category.py`

Include a comment header at the beginning of the file containing:

* Student name
* Course number
* Week number
* Lab number
* Assignment title
* Date

## Part 1: Display a Program Title

Display a descriptive title when the program begins.

The title should clearly indicate that the program categorizes temperatures.

Use appropriate spacing or decorative characters to make the title easy to identify.

## Part 2: Temperature Input

Ask the user to enter a temperature in degrees Fahrenheit.

The temperature may include a decimal value.

Convert the user’s input to an appropriate numeric data type before using it in a comparison.

Store the temperature in a meaningfully named variable.

## Part 3: Temperature Ranges

Use the following required temperature ranges:

* **Cold:** Below 50°F
* **Warm:** From 50°F through 79°F
* **Hot:** 80°F or above

The boundary values are important:

* A temperature of `49.9` is Cold.
* A temperature of `50` is Warm.
* A temperature of `79` is Warm.
* A temperature of `80` is Hot.

Every temperature must belong to exactly one category.

## Part 4: Conditional Statements

Use conditional statements to determine the temperature category.

The program should evaluate the temperature and select only one of the following categories:

* Cold
* Warm
* Hot

Use an appropriate combination of:

* `if`
* `elif`
* `else`

The conditions must correctly handle all three temperature ranges.

## Part 5: Display the Result

Display:

* The temperature entered by the user
* The Fahrenheit symbol or the abbreviation `°F`
* The temperature category

The result must use a clear message explaining whether the temperature is Cold, Warm, or Hot.

Format the output so it is easy to read.

## Required Testing for Program 1

Test the program using all the following values:

### Test 1: Cold

Enter:

`35`

Expected category:

`Cold`

### Test 2: Cold Boundary Check

Enter:

`49.9`

Expected category:

`Cold`

### Test 3: Warm Lower Boundary

Enter:

`50`

Expected category:

`Warm`

### Test 4: Warm

Enter:

`72`

Expected category:

`Warm`

### Test 5: Warm Upper Boundary

Enter:

`79`

Expected category:

`Warm`

### Test 6: Hot Lower Boundary

Enter:

`80`

Expected category:

`Hot`

### Test 7: Hot

Enter:

`95`

Expected category:

`Hot`

Confirm that the program displays only one category for each test.

## Program 1 Point Distribution

* Program title and clear input prompt: 5 points
* Correct numeric input conversion: 5 points
* Correct Cold condition: 10 points
* Correct Warm condition: 10 points
* Correct Hot condition: 10 points
* Clear and properly formatted output: 5 points
* Comment header, code comments, and successful testing: 5 points

**Program 1 Total: 50 points**

# Program 2: Even or Odd

**Points: 50**

## Program Description

Create a Python program that asks the user to enter an integer.

The program must determine whether the integer is:

* Even
* Odd

An even number is evenly divisible by `2`. An odd number has a remainder when divided by `2`.

The program must use an `if` statement to check the number and display the appropriate message.

## Required Python File

Create a Python file named:

`even_or_odd.py`

Include a comment header at the beginning of the file containing:

* Student name
* Course number
* Week number
* Lab number
* Assignment title
* Date

## Part 1: Display a Program Title

Display a descriptive title when the program begins.

The title should clearly indicate that the program determines whether a number is even or odd.

## Part 2: Integer Input

Ask the user to enter an integer.

Convert the user’s input to the integer data type before using it in a calculation or comparison.

Store the integer in a meaningfully named variable.

The user should enter a whole number without a decimal portion.

Examples of valid integer values include:

* `8`
* `17`
* `0`
* `-6`
* `-11`

## Part 3: Determine the Number’s Parity

Use the remainder operator to divide the integer by `2` and examine the remainder.

A number is even when division by `2` produces a remainder of `0`.

A number is odd when division by `2` does not produce a remainder of `0`.

Use an `if` and `else` statement to determine the result.

The program must identify only one result:

* Even
* Odd

## Part 4: Display the Result

Display:

* The integer entered by the user
* A message stating whether the integer is even or odd

Use a complete and clear message.

For example, the result should explain that the entered number is either an even number or an odd number. Students must create their own output wording.

## Required Testing for Program 2

Test the program using all the following values:

### Test 1: Positive Even Number

Enter:

`8`

Expected result:

`Even`

### Test 2: Positive Odd Number

Enter:

`17`

Expected result:

`Odd`

### Test 3: Zero

Enter:

`0`

Expected result:

`Even`

### Test 4: Negative Even Number

Enter:

`-6`

Expected result:

`Even`

### Test 5: Negative Odd Number

Enter:

`-11`

Expected result:

`Odd`

Confirm that the program displays the correct result for positive numbers, negative numbers, and zero.

## Program 2 Point Distribution

* Program title and clear input prompt: 5 points
* Correct integer input conversion: 5 points
* Correct use of the remainder operator: 10 points
* Correct `if` condition: 10 points
* Correct `else` result: 10 points
* Clear and properly formatted output: 5 points
* Comment header, code comments, and successful testing: 5 points

**Program 2 Total: 50 points**

# Code Comments

Use comments to identify and explain the major sections of both programs.

Include comments for:

* The program information header
* The program title
* The user-input section
* The conditional-statement section
* The result-output section

Comments should briefly explain the purpose of each section. They do not need to explain every individual Python statement.

# Functional Requirements

## Temperature Category Program

When `temperature_category.py` runs, it must:

* Display a descriptive program title.
* Ask the user for a temperature in degrees Fahrenheit.
* Accept a whole-number or decimal temperature.
* Convert the input to an appropriate numeric data type.
* Use conditional statements.
* Categorize temperatures below 50°F as Cold.
* Categorize temperatures from 50°F through 79°F as Warm.
* Categorize temperatures of 80°F or above as Hot.
* Display the entered temperature.
* Display only one temperature category.
* Run without errors.

## Even-or-Odd Program

When `even_or_odd.py` runs, it must:

* Display a descriptive program title.
* Ask the user to enter an integer.
* Convert the input to the integer data type.
* Use the remainder operator.
* Use an `if` and `else` statement.
* Correctly identify even numbers.
* Correctly identify odd numbers.
* Correctly identify zero as even.
* Work with positive and negative integers.
* Display the entered integer and the result.
* Run without errors.

# General Requirements

* Use Python to complete the assignment.
* Create both required Python files.
* Use meaningful and consistent variable names.
* Use clear input prompts.
* Convert user input to the appropriate data type.
* Use conditional statements in both programs.
* Include a complete comment header in both files.
* Include comments explaining the major sections.
* Display clear and understandable results.
* Test both programs using all required test values.
* Check spelling, capitalization, grammar, and punctuation.
* Make sure both programs run without errors.
* Follow the course AI-use policy.
* Record any AI assistance in `AI-Use-Report.md`.

# Required Organization

Organize the assignment as follows:

* `Week-05`

  * `Lab-01`

    * `CMP131-Week-05-Lab-0.md1.md`
    * `AI-Use-Report.md`
    * `src`

      * `temperature_category.py`
      * `even_or_odd.py`

# Submission Requirements

Submit or push the complete `Lab-01` folder.

The submission must include:

* `temperature_category.py`
* `even_or_odd.py`
* `AI-Use-Report.md`

Before submitting, verify that:

* Both required Python files are included.
* Both filenames are correct.
* Both programs contain a complete comment header.
* Both programs contain appropriate comments.
* The temperature program uses the required ranges.
* The temperature program correctly handles all boundary values.
* The temperature program displays only one category.
* The even-or-odd program accepts an integer.
* The even-or-odd program uses the remainder operator.
* The even-or-odd program correctly identifies positive and negative numbers.
* The even-or-odd program correctly identifies zero as even.
* Both programs display clear results.
* Both programs were tested using all required test values.
* Both programs run without errors.
* The AI-use report is complete.
* The latest work has been committed and pushed to GitHub.

# Suggested Git Commit Messages

* Create Week 5 Lab 1 Python files
* Add temperature input and categories
* Add temperature conditional statements
* Test temperature boundary values
* Add even-or-odd program
* Add parity conditional statement
* Test positive and negative integers
* Complete Week 5 Python lab

---

## GitHub Starter Repository

Use the following public starter repository:

[CMP131-Week-05-Lab-01](https://github.com/ahedhli12/CMP131-Week-05-Lab-01)

### Getting Started

1. Open the starter repository using the link above.
2. If **Use this template** is available, select **Use this template → Create a new repository**.
3. Choose your personal GitHub account as the owner.
4. Name your repository `LastName-FirstName-CMP131-Week-05-Lab-01`.
5. Set your repository to **Public**.
6. Clone your own newly created repository—not the instructor’s starter repository.
7. Open the entire cloned folder in Visual Studio Code.
8. Complete and test every required Python file.
9. Commit and push your work to GitHub.
10. Verify that your latest files appear on GitHub.
11. Complete `AI-Use-Report.md`.
12. Submit the required work through Blackboard Ultra and include your public repository link when requested.

### Required Repository Files

- `CMP131-Week-05-Lab-01.md`
- `AI-Use-Policy.md`
- `AI-Use-Report.md`
- `temperature_category.py`

### Before You Submit

- [ ] All required Python files are in the repository root.
- [ ] Every required filename is exact.
- [ ] Each program runs successfully.
- [ ] Required tests and screenshots are complete.
- [ ] `AI-Use-Report.md` is complete and accurate.
- [ ] The latest commit is visible on GitHub.
