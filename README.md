# 🎮 Simon Says Web Game

An interactive, responsive, memory-based web game built using **HTML5**, **CSS3**, and **JavaScript (ES6+)**. The app challenges players to memorize and replicate increasingly complex sequences of colors.

---

## ⚡ Live Demo

👉 **[Click Here to Play Live](https://kaushaltiwariweb.github.io/Simon-Says-Game/)**

---

## 🚀 Key Features

* **Dynamic Level Generation:** Dynamically creates new random color patterns at each level.
* **Visual & Sensory Feedback:** Uses custom CSS transitions to highlight button flashes on user clicks and automated sequences.
* **Instant Fail & Reset Logic:** Provides visual feedback (screen flash) upon game over and resets state seamlessly for replayability.
* **Fully Responsive:** Centered grid layout adaptable for mobile, tablet, and desktop viewports.

---

## 🛠️ Tech Stack & Concepts Applied

* **HTML5:** Semantic structure and nested container layouts.
* **CSS3:** Flexbox layout positioning, custom button sizing, dynamic CSS helper classes (`.flash`, `.userFlash`), and custom RGB colors.
* **JavaScript (ES6+):**
  * **DOM Manipulation:** Accessing and updating element text nodes dynamically (`querySelector`, `innerText`, `innerHTML`).
  * **Event Handling:** Event listeners for keyboard triggers (`keypress`) and button user interactions (`click`).
  * **State Management:** Arrays to manage game sequences (`gameSeq`) and user input sequences (`userSeq`).
  * **Timing Events:** Executing asynchronous visual delay triggers using `setTimeout`.

---

## 📖 How to Play

1. **Start Game:** Press any key on your keyboard to initiate Level 1.
2. **Watch the Pattern:** The game will automatically flash one colored box (Red, Yellow, Green, or Purple).
3. **Repeat the Pattern:** Click on the matching colored box.
4. **Advance Levels:** Each correct round adds one new color to the sequence. Repeat the full pattern from memory.
5. **Game Over:** Clicking an incorrect color in the sequence ends the game. Press any key to reset and try again!

---

## 📁 Project Structure

```text
simon-says-game/
├── index.html     # Primary HTML structure and content layout
├── style.css      # CSS stylesheets and UI button designs
├── app.js         # Core JavaScript game loops and sequence logic
└── README.md      # Comprehensive project documentation
