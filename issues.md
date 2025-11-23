# Habit Tree – Debugging & Feature Tasks

This project contains several issues that you must fix.  
Below are the exact bugs and features required.

---

## 🐞 Bug 1 — Score Not Updating
The score tile always shows a static “Completed” text and never changes when habits are checked or unchecked.  
Fix the incorrect element selection and implement proper logic to update the score in real time.

---

## 🐞 Bug 2 — Fruit Not Removed After Unchecking
Unchecking a habit does not remove its fruit from the tree.  
The remove function targets the wrong element ID, so the fruit stays on the tree even when unchecked.  
Fix the removal logic so each fruit disappears correctly.

---

## 🐞 Bug 3 — Multiple Fruits Added for One Habit
Clicking a checkbox adds multiple fruits instead of only one.  
Missing validation causes duplicates to spawn every time the checkbox is clicked.  
Fix the logic so only one fruit appears per checked habit.

---

## ⭐ Feature 1 — Add Reset Button
Add a reset button that clears all habits, fruits, and the score.  
The tree should become empty and all progress should reset instantly.

---

## ⭐ Feature 2 — Change Fruits When >50% Habits Completed
If more than half the habits are completed, change all visible fruits from apples to mangoes.  
Revert back to apples if completion drops below 50%.

---

Good luck! Fix the bugs and implement the features to complete the Habit Tree project.
