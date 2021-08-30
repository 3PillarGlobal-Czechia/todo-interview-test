# TODO Kata

The goal of this kata is to implement classes for simple TODO LIST application. The purpose is not to create a complete application with persistence and UI but to practice OOP, language, and design skills. A console application is 100% sufficient. The application doesn't need to accept any input from users. Behavior can be hardcoded in the main method of the program.

Acceptance criteria:
- We can create TODO LIST with a specific name
- We can add TODO into TODO LIST
- TODO contains unique Id, text with length min 2 and max 500, priority (low, medium, hard), deadline date, state (active, done)
- TODO can be marked as DONE
- We can obtain all items in TODO LIST
- Item in TODO LIST can be printed ordered by DATE or by PRIORITY ( - does NOT include todos marked as done)
- TODO can be updated by ID (Text, Priority, Date)
- TODO can be deleted by ID

Recommendations:
- Follow some of SOLID/CUPID principles
- Write unit tests
- Implement classes to separate class library
- There are no limitations to your own enhancements
- Use some version control system (git)
