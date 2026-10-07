# Week 6 Assignment - Safe Functions

This assignment practices using `try` and `except` to safely handle errors in Python without allowing the program to crash.

## Files

- `safe_tools.py` - Contains three safe functions for division, converting text to whole numbers, and looking up dictionary fields.
- `README.md` - Provides information about the assignment and explains why an `if` check alone cannot catch invalid number input.

## Why can the `if` check not catch `abc` on its own?

An `if` check can test conditions, but converting `"abc"` to an integer using `int()` causes Python to raise a `ValueError`. The `try` and `except` structure is needed to catch this error and return `"Not a number"` instead of allowing the program to crash.
