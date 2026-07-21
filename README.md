# Longest Valid Parentheses - Node.js

## Problem
Given a string containing only '(' and ')', return the length of the longest valid (well-formed) parentheses substring.

## Approach
- Use a stack to store indices.
- Initialize the stack with -1 as a base index.
- Push indices of '('.
- On ')', pop the stack.
- If the stack becomes empty, push the current index.
- Otherwise, calculate the current valid substring length and update the maximum.

## Time Complexity
O(n)

## Space Complexity
O(n)

## Example

Input:
(()

Output:
2

Input:
)()())

Output:
4
