
# Week 6 Assignment: Safe Tools

## Project Files

- `safe_tools.py` - Contains three safe functions that handle division by zero, invalid number conversion, and missing dictionary keys using try and except.

## Reflection

An if check alone cannot catch "abc" as an invalid number because the error happens when Python tries to convert the text into an integer using int(). Using try and except ValueError allows the program to handle the conversion error without crashing.
