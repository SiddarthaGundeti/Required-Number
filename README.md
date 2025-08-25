# Required-Number

Question Explanation:

Input: 54

Output: True

You are given a number N, and you need to write a program to check two conditions:

If the number N is between 50 and 100 (inclusive).

If the first digit of N is equal to 7.

You should return True if either of these conditions is met; otherwise, return False.

Logical Approach:

Read an integer input N.

Convert N to a string and store it in a variable (e.g., length) to make it easier to access individual digits.

Check two conditions:

Condition 1: Check if N is between 50 and 100 (inclusive). You can use the logical "and" operator (and) to combine two conditions:

range_condition = (number > 50 and number <= 100)

Condition 2: Check if the first digit of N is equal to 7 by comparing the first character of the string representation of N to the character '7':

first_digit_condition = length[0] == '7'

Use an if-else statement to determine the final result:

If either of the conditions (range_condition or first_digit_condition) is True, print True.

Otherwise, print False.
