# NUMERICAL PYTHON (NUMPY): EXPERIMENT#2

This repository contains solutions to three Python programming exercises as part of an Introductory Python Programming Experiment.

# EXERCISES:
# A. WORD ROTATION PROBLEM

Task: Create a function named rotate word() that accepts a non-empty string. Move the first character
of the string to the end while keeping all remaining characters in their original order. Preserve the
capitalization of every character.

Example: rotate_word("Programming") -> "rogrammingP", rotate_word("Google") -> "oogleG"

# B. USERNAME BUILDER PROBLEM

Task: Create a function named make username() that accepts two strings: first name and last name. The
function must:
1. convert all letters to lowercase;
2. remove all spaces from the first name;
3. remove all spaces from the last name; and
4. join the processed first and last names using one period (.).
Function format: make username(first name, last name)

Example: make_username("Joseph", "Sy") -> "joseph.sy", make_username("Sherina", "Padilla") -> "sherina.padilla"


# C. BOOKEND SWAP PROBLEM

Task: Create a function named swap bookends() that accepts a list containing at least two elements. Using these variables, return a new list in which the first and last elements have exchanged positions. The elements in middle must remain in their original order.

Example: swap_bookends(["happy", "sad", "angry"]) -> ["angry", "sad", "happy"], swap_bookends([6, 7]) -> [7, 6]

# Implementation:
The solutions are implemented in a Jupyter Notebook file (.ipynb) conatining:
1. create and reshape NumPy arrays using appropriate NumPy functions;
2. perform vectorized numerical operations on an ndarray;
3. compute array statistics and use Boolean conditions to select elements

# Learning Outcomes:
Through these exercises, you will:
- Identify complex codes and functions using NumPy in Python Programming
