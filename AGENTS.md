```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines outline the principles and rules for development of AGENTS.md, ensuring code clarity, maintainability, and robust testing. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   All logic, data structures, and utility functions should be encapsulated within individual files and reused across multiple modules.
*   Avoid duplicating code snippets or entire functions.
*   When a function or data structure is used in multiple places, consider creating a common, reusable component.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize simplicity in design and implementation.
*   Favor straightforward solutions over overly complex ones.
*   Ensure each component has a clear and understandable purpose.
*   Avoid unnecessary abstractions or layers of indirection.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one, and only one, reason to change.
*   **Open/Closed Principle:** Classes/modules should be open for extension but closed for modification.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be forced to implement interfaces they don’t use.
*   **Dependency Inversion Principle:** High-level modules should be dependent on interfaces, not concrete classes.

## 4. YAGNI (You Aren't Gonna Need It)

*   Implement only the functionality strictly necessary for the current task.
*   Avoid introducing unnecessary features or complexities that are unlikely to be utilized in the future.
*   Refactor code to remove legacy elements or unused functionality.

## 5. Testing & Coverage

*   All development must be productive. Do not use mocks or fake implementations.
*   All testing must be included and justified through unit tests.
*   Test coverage should be maintained at a minimum of 80%.
*   Unit tests should cover all critical logic and edge cases.
*   Each file shall have a maximum of 180 lines of code.
*   All code must be documented using clear and concise comments.

## 6. File Structure & Organization

*   **Modules:** Group related code into modules with clear responsibilities.
*   **Data Structures:** Define clear data structures for efficiency and readability.
*   **Classes:** Encapsulate data and behavior, promoting modularity and reusability.
*   **File Names:** Use descriptive file names that indicate the purpose of the file.
*   **Naming Conventions:** Follow a consistent naming convention (e.g., camelCase, snake\_case).
*   **Comments:** Write clear and concise comments explaining the purpose and logic.

## 7.  Code Standards & Style

*   Use consistent indentation and spacing.
*   Follow the established code style guidelines (see [link to style guide if applicable]).
*   Employ whitespace appropriately for readability.

## 8.  Specific Considerations for AGENTS.md

*   The file should contain comprehensive documentation explaining the purpose of each module and function.
*   Error handling should be implemented consistently.
*   Data flow should be clearly illustrated.

## 9.  Development Workflow

*   Implement code in a clear and organized manner.
*   Use version control (Git) to track changes and collaborate effectively.
*   Regularly review and refactor code to improve maintainability.
*   Conduct thorough testing after each change.

## 10.  Maximum Code Length: 180 lines

## 11.  Test Coverage Target: 80% Minimum

## 12.  Documentation: Clear, Concise, and Informative.

This guideline document will serve as the primary reference for all development activities within AGENTS.md.  Any deviations from these guidelines must be documented and approved by the lead developer.
```