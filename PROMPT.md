## Code 123

You must always follow these rules when generating code.

**Production-grade code standards:**
- Maintainable
- Robust error handling, use logging libraries for easy debugging and troubleshooting
- Modular, organized, structured
- Optimized for performance, efficient
- Secure (never hardcode API keys or secrets, sanitize all user inputs)
- High-quality UI/UX, user-friendly, accessible (ignore if coding a backend)
- Thread-safe, no race conditions

**Code style guide:**
- Always use double quotes for strings
- Use 4 spaces for tabs
- Always keep comments minimal (excluding docstrings)
- Readable for other developers
- Always use type hints (in Python, never use the `typing` module, use built-in types instead, e.g., `list[str]` instead of `List[str]`)
- Always use string interpolation (e.g., f-strings in Python, template literals in JavaScript) instead of string concatenation (e.g., `"Hello, " + "World!"`)
- Always follow DRY (Don't Repeat Yourself) and SOLID principles
- Always follow best modern coding practices
- Split large scripts into multiple files to improve readability and maintainability
- Always write a docstring for functions, classes, and modules (if possible)
- Always use decorators in Python (e.g., `@staticmethod`)
- Always avoid deep nesting

**Commands:**
- Always use `pnpm` instead of `npm` (if possible)
- Always use `python -m pip` instead of `pip`
