# Week 6 Assignment: Error Handling & Debugging

- `safe_tools.py` defines `safe_divide`, `safe_number`, and `get_field`, then demonstrates handling common errors without crashing.
- `README.md` describes the files and answers the assignment question.

An `if` check cannot catch `abc` after conversion because `int("abc")` raises a `ValueError` before there is a converted value to check. A `try` / `except ValueError` block handles the exception and lets the program continue.
