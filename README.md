🎮 Simon Says Web Game

An interactive, responsive, memory-based web game built using HTML5, CSS3, and JavaScript (ES6+). The app challenges players to memorize and replicate increasingly complex sequences of colors.

⚡ Live Demo

Live Demo: Click Here to Play 

Repository: GitHub Source Code

🚀 Key Features

Dynamic Level Generation: Dynamically creates new random color patterns at each level.

Visual & Sensory Feedback: Uses custom CSS transitions to highlight button flashes on visual clicks and automated sequences.

Instant Fail & Reset Logic: Provides visual feedback (screen flash) upon game over and resets state seamlessly for replayability.

Fully Responsive: Centered grid layout adaptable for mobile, tablet, and desktop viewports.

🛠️ Tech Stack & Concepts Applied

HTML5: Semantic structure (<h1>, <h2>, <h3>, nested container layouts).

CSS3: Flexbox layout positioning, custom button sizing, dynamic CSS helper classes (.flash, .userFlash), and custom RGB colors.

JavaScript (ES6+):

DOM Manipulation: Accessing and updating element text nodes dynamically (querySelector, innerText, innerHTML).

Event Handling: Event listeners for keyboard triggers (keypress) and button user interactions (click).

State Management: Arrays to manage game sequences (gameSeq) and user input sequences (userSeq).

Browser Storage API: Utilizing sessionStorage with numeric parsing (parseInt) for tracking top scores per session.

Timing Events: Executing asynchronous visual delay triggers using setTimeout.

📂 Project Structure

simon-says-game/
│
├── index.html       # Primary HTML structure and content layout
├── style.css        # CSS stylesheets and UI button designs
├── app.js           # Core JavaScript game loops, sequence logic, and state handling
└── README.md        # Comprehensive project documentation



🕹️ How to Play

Start Game: Press any key on your keyboard to initiate Level 1.

Watch the Pattern: The game will automatically flash one colored box (Red, Yellow, Green, or Purple).

Repeat the Pattern: Click on the matching colored box.

Advance Levels: Each round adds a new random color to the end of the previous sequence. Repeat the full sequence correctly.

Game Over: If you click the wrong color in the sequence, the background will flash red, your final score will display, and the highest score updates if beaten. Press any key to start fresh!

💻 Local Installation & Setup

To run this project locally on your machine:

Clone the Repository:

git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git



Navigate to Project Directory:

cd YOUR_REPO_NAME



Run the Game:

Double-click index.html to open it directly in any browser.

Or use the VS Code extension Live Server to preview locally.

📝 License

This project is open-source and available under the MIT License.
