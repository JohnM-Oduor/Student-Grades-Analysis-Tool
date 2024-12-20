# Student-Grades-Analysis-Tool
This is a simple JavaScript program to calculate the average score, assign letter grades, and provide feedback on a student's performance based on their scores.

---
## Features

- **Calculate Average**: Computes the average score of a list of student scores.
- **Assign Grades**: Determines letter grades (`A++`, `A`, `B`, `C`, `D`, `F`) based on a grading scale.
- **Check Passing Grade**: Evaluates if a score meets the passing criteria.
- **Generate Student Message**: Provides a detailed message with the class average, individual grade, and whether the student passed or failed.

---
## Usage

To use the program, include the script in your project or execute it in a JavaScript runtime like Node.js or a browser console.

---
### Functions Overview

1. **`getAverage(scores)`**
   - Calculates the average of an array of scores.
   - **Parameters**: 
     - `scores` (Array): A list of numerical scores.
   - **Returns**: The average score.

   Example:
   ```javascript
   getAverage([90, 80, 70]); // Returns 80
