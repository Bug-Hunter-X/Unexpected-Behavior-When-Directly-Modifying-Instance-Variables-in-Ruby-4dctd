# Unexpected Behavior When Directly Modifying Instance Variables in Ruby

This repository demonstrates a potential issue in Ruby when directly modifying instance variables using `instance_variable_set`. While functional, this practice can lead to difficulties in maintaining and debugging code.

## Problem
Direct manipulation of instance variables bypasses methods designed for controlled access. This makes it harder to track changes and implement proper validation or side-effects.

## Solution
Favor using accessor methods (getters and setters) instead of directly modifying instance variables. This improves code readability, maintainability, and allows for future modifications without unexpected consequences.
