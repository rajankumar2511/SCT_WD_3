# 🔥 Tic-Tac-Toe Web Application

Live Site: [https://rajankumar2511.github.io/SCT_WD_3/](https://rajankumar2511.github.io/SCT_WD_3/)

## 📌 Overview

This project is a clean, interactive **Tic-Tac-Toe** game developed as part of my **third internship task**. It now supports **both two-player and Player vs Computer modes**, with responsive gameplay, glowing highlights, and dynamic win/draw detection.

Built using **HTML**, **CSS**, and **Vanilla JavaScript**, it’s visually engaging and works across all devices.

---

## 🧠 Features

- 🎮 **Two Modes**:  
  - X vs O (two-player mode)  
  - Play against a basic AI (random move logic)  

- 🧠 **Game Logic**:  
  - Handles clicks, tracks game state, and checks for win/draw  
  - Supports all 8 win conditions (rows, columns, diagonals)  
  - Winning cells are highlighted visually  

- 🏆 Win & Draw Detection:  
  - Trophy icon and colored messages  
  - Glowing green background for winning cells  
  - Draw status with proper icon and message  

- 🔁 Reset Button:  
  - Smooth animated reset  
  - Clears board, status, and active player

- 🌗 Dark Themed UI:  
  - Smooth transitions  
  - Color-coded X (blue) and O (red)  
  - Shadows, glow effects, and responsive layout

- 📱 Mobile Friendly:  
  - Works perfectly on phones and tablets  
  - Responsive grid and text sizes

- 🎨 Font Awesome Icons:  
  - For trophy, reset, draw, and mode switch buttons

---

## 📂 Technologies Used

- **HTML5**
- **CSS3** (modern transitions and layout)
- **Vanilla JavaScript**
- **Font Awesome** (for icons)

---

## 📋 How to Use

### ▶️ Live Version
👉 [Play Now](https://rajankumar2511.github.io/SCT_WD_3/)

### 💻 Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/rajankumar2511/SCT_WD_3.git
Open index.html in your browser.

🛠 Mode Switching
Click the "Play vs Computer" button to toggle between:

PvP mode: two humans play (default)

PvC mode: Player is X, computer plays O with random moves

Switching mode automatically resets the board.

🧩 Winning Conditions
The game checks for wins using these combinations:


[0, 1, 2] → top row  
[3, 4, 5] → middle row  
[6, 7, 8] → bottom row  
[0, 3, 6] → left column  
[1, 4, 7] → middle column  
[2, 5, 8] → right column  
[0, 4, 8] → diagonal TL to BR  
[2, 4, 6] → diagonal TR to BL  
If any 3 cells match the same player, those cells are highlighted in green and a trophy icon + win message is shown.

📌 Internship Context
This project was built as Task 03 of my web development internship at Skill Craft. The objective was to build a visually polished and functional web-based game using front-end technologies only.

📃 License
This project is open-source and available for educational and personal use.
Feel free to fork, improve, and customize it.

✨ Created with ❤️ by Rajan Kumar
