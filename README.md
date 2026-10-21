# Python Week 6 Assignment: Safe Functions

**Files included:**
- `safe_tools.py`: Contains three functions that use try/except blocks to handle division by zero, type conversion errors, and missing dictionary keys without crashing.

**Why can the `if` check not catch "abc" on its own?**
A standard `if` check evaluates a condition, but it doesn't handle the internal crash that happens when Python's `int()` function tries to convert letters into numbers. If you run `int("abc")`, Python immediately throws a `ValueError` and stops the program before an `if` statement can even check the result. A `try...except` block intercepts this crash directly.



