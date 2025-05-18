# Sudoku-Game
Sudoku is a logic-based number-placement game that challenges players to fill a 9x9 grid with  digits from 1 to 9. The objective is to complete the grid in such a way that each row, each  column, and each of the nine 3x3 subgrids (also known as regions or boxes) contains all of the  digits from 1 to 9 without repetition. 
# Certainly! Here's a simplified academic explanation in English, outlining the **objectives**, **results**, and **outputs** of the provided Sudoku solver code:

---

### 🎯 **Objectives of the Code:**

1. **Build a Sudoku Game Interface:**

   * Create a graphical interface (GUI) using **Tkinter** to allow users to play Sudoku interactively.

2. **Integrate AI Techniques to Solve Sudoku:**

   * Use **Arc Consistency (AC-3)** to reduce the solution space.
   * Apply **Backtracking Algorithm** to find the final solution efficiently.

3. **Validate and Check User Input:**

   * Ensure players only enter numbers from 1 to 9.
   * Provide error messages for invalid inputs.

4. **Provide Game Features:**

   * Allow players to generate Sudoku puzzles of different difficulties (easy, medium, hard).
   * Include options to check the solution or reveal it.
   * Show a **real-time timer** to track gameplay duration.
   * Log the **Arc Consistency** steps in a readable format.

---

### ✅ **Results of Implementing This Code:**

1. **Functional Sudoku Game GUI:**

   * The user can interact with the game board, input answers, and solve puzzles.

2. **Automated Solving Using AI:**

   * The game uses AC-3 to simplify the board before applying backtracking.
   * This increases efficiency and solves complex boards faster.

3. **Educational Visualization:**

   * The log shows how the AI reduces domains using arc consistency, helping users understand constraint satisfaction processes.

4. **Dynamic Difficulty and User Experience:**

   * Difficulty levels adjust the number of empty cells.
   * Colors and fonts improve visual clarity and usability.

---

### 📤 **Outputs and Their Importance:**

| Output                 | Description                               | Importance                                   |
| ---------------------- | ----------------------------------------- | -------------------------------------------- |
| `Sudoku Board GUI`     | A 9x9 grid of input cells                 | Provides a visual interface for playing      |
| `AC-3 Log (arc_steps)` | Text box showing steps of arc consistency | Helps understand AI constraint-solving steps |
| `Timer Label`          | Displays elapsed time during the game     | Encourages performance tracking              |
| `Difficulty Buttons`   | Easy, Medium, Hard buttons                | Allows customized game challenge             |
| `Check Solution`       | Validates the user's solution using AI    | Ensures correct solving logic                |
| `Show Solution`        | Fills the board with the correct solution | Helps users learn from mistakes              |

