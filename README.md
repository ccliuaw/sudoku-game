# Sudoku Master - HTML & CSS Mock

This project is a website for palying Sudoku games.

## 🔗 Project Links
* **Live Website (Github Pages):** https://ccliuaw.github.io/sudoku-game/
* **Github Repository:** https://github.com/ccliuaw/sudoku-game

## 👥 Developer
* **Name:** Chun-Cheng Liu

---

## 📝 Project Writeup & Reflection

### 1. Challenges & Learning Experience
* **What was the most challenging piece of this assignment?**
    [The most challenging part was implementing the 9x9 Sudoku grid using CSS Grid. I had to ensure the 3x3 subgrids had thicker borders while the internal cells had thinner borders to mimic a real Sudoku board. Additionally, implementing the `readonly` attribute for the pre-filled numbers required careful CSS styling to visually distinguish them from the user-input cells.]
* **How long did this assignment take?**
    [e.g., This assignment took me approximately 12 hours to complete.]

### 2. Mobile-Friendly Design Decisions
* **What decisions did you make when you made your site mobile friendly?**
    [My primary decision was to completely change the navigation layout based on the device size. On desktop, the navbar is a fixed sidebar on the left for easy access. On mobile (screens smaller than 768px), I used `@media` queries to move the navbar to the bottom of the screen, similar to native mobile apps. I also ensured the Sudoku grid shrinks proportionally so users don't have to scroll horizontally.]

### 3. Design & Branding
* **What did you take into account when you developed the design?**
    [I chose a clean, professional color palette (Dark Blue #2c3e50 and Orange #e67e22) to create good contrast. I focused heavily on "User Experience" (UX) by using the `readonly` HTML attribute for the puzzle clues, ensuring users can't accidentally delete the puzzle numbers. I also styled these fixed numbers with a grey background and bold text to make the board easy to read at a glance.]

### 4. Future Features
* **Given more time or resources, what additional features would you add?**
    [In the future, I would add JavaScript to validate the user's input against the correct solution in real-time. I would also implement a "Draft Mode" where users can pencil in small numbers in the corners of the cells. Connecting the "High Scores" page to a real backend database to track player rankings would also be a priority.]

### 5. Time Spent
* **Total Hours:** [e.g., 12 Hours]

### 6. Assumptions Made (Optional)
* **Mock Selection Logic:** I assumed that for the "Selection Page," it is acceptable for multiple "Hard" puzzle titles to link to the same `game-hard/index.html` page, as this is a frontend mock without a backend database to store unique puzzles.
* **Input Validation:** Since no JavaScript is allowed, the "Check Puzzle" and "Login" buttons are visual-only and do not perform actual validation.

---

## 📚 References & Credits
* **Fonts:** Segoe UI (System Standard)
* **Images:** Sudoku Hero Image from Wikimedia Commons.
* **Puzzle Source:** The "Iron Logic" puzzle is based on a standard classic Sudoku layout.
* **Code Structure:** File organization follows the clean URL pattern (using folders with `index.html`).
