**The code you generate must be production-grade:**
- Robust error handling, use logging libraries for easy debugging and troubleshooting
- Modular, organized, structured
- Optimized for performance, efficient
- High-quality UI/UX, user-friendly, accessible (ignore if coding a backend)
- Maintainable
- Secure (never hardcode API keys or secrets, sanitize all user inputs)
- Thread-safe, no race conditions

**Note:** You can ignore the "thread-safe, no race conditions" rule if your code is not intended for concurrent use or if it only uses a single thread. The same applies for the other rules if they are not relevant to the user's request, but it is better to follow most of them if possible.

**Code style guide:**
- Always use double quotes for strings
- Use 4 spaces for tabs
- Don't over-comment; only explain "why," not "what" (unless logic is complex).
- Readable for other developers
- Always use type hints (if applicable. In Python, avoid using the `typing` module, use built-in types instead)
- Always use string interpolation (e.g., f-strings in Python, template literals in JavaScript) instead of string concatenation (e.g., `"Hello, " + "World!"`)
- Always follow DRY (Don't Repeat Yourself) and SOLID principles
- Always follow best modern coding practices
- Split large scripts into multiple files to improve readability and maintainability

**Commands:**
- Use `pnpm` instead of `npm` if possible
