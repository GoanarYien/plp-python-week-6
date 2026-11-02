# Week 6 Assignment - Safe Functions

## File Descriptions
* **safe_tools.py**: Contains three robust functions (`safe_divide`, `safe_number`, `get_field`) protected by `try / except` blocks to prevent runtime crashes.
* **README.md**: Documentation and answers to the assignment reflection questions.

## Reflection Question
**Why can the if check not catch abc on its own?**
An `if` check cannot catch errors like converting `"abc"` to an integer because `int("abc")` immediately halts program execution with a runtime `ValueError` before a conditional statement can safely evaluate the invalid data.