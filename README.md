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
    The most challenging part was implementing the 9x9 Sudoku grid using CSS Grid. I had to ensure the 3x3 subgrids had thicker borders while the internal cells had thinner borders to mimic a real Sudoku board. Additionally, implementing the `readonly` attribute for the pre-filled numbers required careful CSS styling to visually distinguish them from the user-input cells.

* **How long did this assignment take?**
    This assignment took me approximately 12 hours to complete.

### 2. Mobile-Friendly Design Decisions
* **What decisions did you make when you made your site mobile friendly?**
    My primary decision was to completely change the navigation layout based on the device size. On desktop, the navbar is a fixed sidebar on the left for easy access. On mobile (screens smaller than 768px), I used `@media` queries to move the navbar to the bottom of the screen, similar to native mobile apps. I also ensured the Sudoku grid shrinks proportionally so users don't have to scroll horizontally.

### 3. Design & Branding
* **What did you take into account when you developed the design?**
    I chose a clean color palette to create good contrast for intuitive operation for the user. I focused heavily on "User Experience" (UX) by using the `readonly` HTML attribute for the puzzle clues, ensuring users can't accidentally delete the puzzle numbers. I also styled these fixed numbers with a grey background and bold text to make the board easy to read at a glance.

### 4. Future Features
* **Given more time or resources, what additional features would you add?**
    In the future, I would add more games for user to play. And linked the player score to the highscore page.

### 5. Time Spent
* **Total Hours:** 12 hours

---

## Reference

Logo image source: https://commons.wikimedia.org/wiki/File:NYT_Sudoku_Logo.png
