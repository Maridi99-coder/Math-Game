# 🎯 Match Game

A fast-paced memory and matching game built using React. This app challenges players to quickly find matching images before time runs out. Built with reusable components, timer logic, and category-based filtering, it's a great example of intermediate React development.

---

## 🔗 Live Demo

[View Live Game](https://MaridiMathGame.ccbp.tech)

---

## 📸 Preview

### Scorecard View

![Scorecard](https://assets.ccbp.in/frontend/content/react-js/match-game-score-card-lg-output.png)

---

## 🚀 Features

- 🧠 Match the correct image from multiple thumbnails
- ⏱️ Countdown timer starting from 60 seconds
- 🎯 Score tracking based on correct matches
- 🧭 Category-based filtering (Fruits, Animals, Places)
- 🔁 Replay option on game over
- 🎨 Responsive UI across devices
- 📷 Game assets with correct alt tags for accessibility

---

## 📁 Folder Structure

src/
├── components/
│ ├── Header/
│ ├── MatchGame/
│ ├── TabItem/
│ ├── ThumbnailItem/
│ └── ScoreCard/
├── App.js
└── index.js


---

## 🧪 Test Requirements (Passes All)

- "Image to match" has `alt="match"`
- All thumbnails have `alt="thumbnail"`
- Scorecard assets follow specified `alt` values:
  - `alt="reset"` for play again
  - `alt="trophy"` for trophy image
  - `alt="website logo"` for logo
  - `alt="timer"` for timer image

---

## 🛠️ Tech Stack

- React
- JavaScript (ES6+)
- CSS3
- React State & Props
- React Lifecycle Methods
- setInterval for Timer Logic

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/match-game.git
cd match-game
npm install
npm start


---

## 🧪 Test Requirements (Passes All)

- "Image to match" has `alt="match"`
- All thumbnails have `alt="thumbnail"`
- Scorecard assets follow specified `alt` values:
  - `alt="reset"` for play again
  - `alt="trophy"` for trophy image
  - `alt="website logo"` for logo
  - `alt="timer"` for timer image

---

## 🛠️ Tech Stack

- React
- JavaScript (ES6+)
- CSS3
- React State & Props
- React Lifecycle Methods
- setInterval for Timer Logic

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/match-game.git
cd match-game
npm install
npm start

🧠 Gameplay Instructions
Game starts with a score of 0 and 60 seconds.

Match the main image with the correct thumbnail.

Each correct match gives +1 score and new image.

If incorrect thumbnail is clicked or time runs out:

Game ends

Scorecard is shown

Click "PLAY AGAIN" to restart the game.

📦 Assets & Resources
All assets are pre-provided:

Backgrounds, logo, icons, and UI elements

Assets Folder & URLs

Resources
Match Image: alt="match"

Thumbnail Images: alt="thumbnail"

Timer Image: alt="timer"

Logo: alt="website logo"

Reset Button Image: alt="reset"

Trophy Image: alt="trophy"

🎨 Design References
Small Screens Output

Large Screens Output

🌈 Colors & Typography
Colors:

Purple: #2c0e3a

Yellow: #fec653

Pink: #cf60c8

White: #ffffff

Font Family:

Roboto

🙋‍♂️ Author
GitHub: @Maridi Kumar Koneti

LinkedIn: https://www.linkedin.com/in/maridikumarkoneti/
