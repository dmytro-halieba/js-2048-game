# 2048 Game 🧩

A logic-based puzzle game built with Pure Vanilla JavaScript and Object-Oriented Programming (OOP) principles. The challenge? Merge your way up to the legendary 2048 tile using pure logic, slick matrix manipulation, and modern web development skills. Can you beat the grid?

## Live Demo 🚀

[👉 Play 2048 Here](https://dmytro-halieba.github.io/js_2048_game/)

## Features ✨

* **Logic-Driven Architecture:** Implements a strict separation of concerns between the core game logic (state management via the Game class) and the UI rendering layer (DOM manipulation), ensuring highly maintainable code.
* **Matrix Manipulation:** Features robust and efficient algorithms for handling a 4x4 grid, tracking empty cells, and sliding/merging tiles (ensuring a maximum of one merge per move per tile). Includes the classic 10% probability constraint for spawning a "4" tile instead of a "2".
* **Dynamic UI & State Management:** Delivers real-time score calculations, seamless layout updates, and accurate Win/Game Over status messaging.
* **Responsive Keyboard Support:** Fluid and responsive keyboard controls utilizing arrow keys for intuitive gameplay.
* **Modern JavaScript:** Architected cleanly utilizing ES6 Classes and Modules for optimal code organization and encapsulation.

## Tech Stack 🛠️

* **HTML5:** Semantic structuring.
* **CSS3:** Styled cleanly using the BEM (Block Element Modifier) methodology for modular and predictable UI rendering.
* **Vanilla JavaScript (ES6+):** Pure JS logic leveraging classes and modern syntax, completely framework-free.
* **Clean Code Practices:** Emphasizes readability, OOP principles, and testable logic.

## Installation & Setup 💻

Want to run this locally? Follow these simple steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dmytro-halieba/js-2048-game.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd js-2048-game
   ```
3. **Run the game:**
   Open `index.html` in your browser. For the best development experience, open it utilizing a tool like **Live Server** in VS Code.

## Usage & Gameplay 🎮

* **How to Move:** Use your keyboard's **Arrow Keys** (Up, Down, Left, Right) to slide the tiles across the 4x4 grid.
* **How to Score:** When two tiles with the same number crash into each other, they merge into a single tile containing the sum of their values! Every merge dynamically adds to your total score.
* **The Goal:** Keep strategically merging tiles to reach the elusive **2048** tile and win the game. If the grid fills up and no more valid moves or merges are possible, it's Game Over. Plan your strategy carefully!

---

**Author:** Dmytro Halieba
