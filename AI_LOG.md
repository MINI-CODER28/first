# AI Log

**Tool used:** Claude

**Purpose of using AI:** I used Claude only to double-check the code I had written for my study deadline tracker. I did not use Claude to generate the code or build the application. I developed the project myself using HTML, CSS and JavaScript. I used Claude as an additional checking tool to help me identify potential errors and verify whether the code was working as expected.

**How I used the tool:** After writing the code, I used Claude to review specific parts of my existing code, particularly the deadline countdown, input validation, localStorage and JSON import functionality. I wanted to check whether the logic was correct and whether there were any potential issues I might have overlooked. I remained responsible for writing, understanding and testing my code.

**Testing:** I checked the main features of the application, including adding deadlines, displaying countdowns, filtering tasks by status and course, marking tasks as completed and deleting tasks. I also checked whether the deadlines remained saved after refreshing the page. I reviewed the layout on smaller screens and checked how the application handled invalid JSON files during import.

**Bugs found and fixes:**

1. **Invalid dates when importing JSON:** I checked whether the import functionality properly validated deadline dates. An imported JSON file could contain a due date in an invalid format, even if the title and course fields were present. This could cause the countdown to display an incorrect value. I used Claude to double-check the date-validation logic and considered how invalid dates should be handled.

2. **Empty input fields:** I reviewed the form validation to make sure users could not add a deadline without entering a task name, course and due date. The code uses required fields and additional JavaScript validation to check the trimmed input values. I checked whether these validations worked as intended.

3. **Saving deadlines with localStorage:** I checked whether the application saved deadlines correctly and restored them after a page refresh. I also reviewed how the application handled stored data that could not be parsed as valid JSON. I used Claude to double-check this logic and verify that the application had a fallback when stored data could not be read.

**Improvements and reflection:** I completed the coding and implementation of the application myself. Claude was used only to double-check my existing code and help me review potential problems. This gave me an additional way to evaluate my work and think about possible edge cases. I remained responsible for understanding the code, testing the application and deciding whether any changes were necessary.
