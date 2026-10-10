# PLP Python Week 6 Assignment

## File Descriptions
- **safe_tools.py**: A Python script containing three robust functions (`safe_divide`, `safe_number`, and `get_field`) utilizing `try/except` blocks to handle runtime exceptions gracefully.

## Reflection Question
**Why can the if check not catch "abc" on its own?**
An `if` conditional check cannot anticipate all possible invalid formats or type-conversion issues without complex manual parsing. Using `try/except` allows Python to attempt the operation directly and automatically catch the `ValueError` when an incompatible input like `"abc"` is passed to `int()`.