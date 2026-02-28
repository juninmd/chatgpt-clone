```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines are designed to ensure the development of high-quality, maintainable, and robust AI coding agents. Adherence to these principles is crucial for long-term project success.

## 1. DRY (Don't Repeat Yourself)

*   All code should be self-contained and reusable. Avoid duplicating functionality across multiple files or components.
*   Implement common patterns and abstractions in separate files.
*   Refactor code to eliminate redundancy.

## 2. KISS (Keep It Simple, Stupid)

*   Favor simple, readable code over overly complex solutions.
*   Minimize code complexity.
*   Strive for clarity and understandability.
*   Avoid unnecessary abstractions.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or module should have a single, well-defined responsibility.
*   **Open/Closed Principle:** The system should be open for extension but closed for modification.  New functionality should be added through API interfaces.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be forced to implement interfaces they do not use.
*   **Dependency Inversion Principle:**  High-level modules (classes) should be dependent on low-level modules (interfaces), not vice-versa.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement features that are currently required and absolutely essential.
*   Avoid premature implementation of features.
*   Refactor to remove unnecessary code.

## 5. Code Structure and Formatting

*   **File Size Limit:** Each file must not exceed 180 lines of code.
*   **Naming Conventions:** Use descriptive and consistent naming conventions.
*   **Comments:**  Provide clear and concise comments explaining non-obvious logic or decisions.
*   **Code Structure:** Use logical grouping and separation of concerns.
*   **Error Handling:** Implement basic error handling to prevent crashes and provide informative messages.

## 6. Testing & Verification

*   **Unit Tests:** All code must be thoroughly tested with unit tests. Aim for 80% code coverage.
*   **Test Coverage:**  Tests must cover all core functionalities and edge cases.
*   **Test Data Management:** Utilize realistic test data that simulates real-world scenarios.
*   **Test Driven Development (TDD) considerations:**  Consider writing unit tests *before* implementing the functionality.

## 7. Development Practices

*   **Version Control:**  Use Git for version control.
*   **Code Review:**  All code should undergo peer review.
*   **Documentation:** Provide clear documentation for API endpoints, data structures, and any significant design decisions.
*   **Error Logging:** Implement robust error logging to facilitate debugging and monitoring.
*   **Maintainability:** Prioritize code that is easily understandable and adaptable.


## 8.  Specific Considerations for AGENTS.md (Example - Adapt to your specific project)

*   **Data Structures:** Define clear and documented data structures for agents, knowledge, and interactions.
*   **Communication Protocols:** Specify communication protocols and message formats.
*   **State Management:**  Implement a well-defined state management strategy.
*   **API Design:**  Consider API design principles early.

## 9.  Compliance & Standards

*   Follow established coding standards (e.g., PEP 8 for Python).
*   Adhere to any specific project requirements or guidelines.


These guidelines are intended to guide the development process and ensure the creation of a high-quality, maintainable, and reliable AI coding agent.  Continuous monitoring and refinement of these principles are recommended.
```