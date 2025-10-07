# 🐍 Snake Game

A simple and fun Snake Game built with **HTML, CSS, and JavaScript**.  
Play directly in the browser with features like scoring, difficulty levels, sound effects, pause/resume, and a high score tracker.

---

## 🎮 Features

- **Classic Snake Gameplay** → Eat food to grow your snake.
- **Scoring System** → Current score and persistent high score (saved in `localStorage`).
- **Difficulty Levels** → Choose between Easy, Medium, and Hard speeds.
- **Pause/Resume** → Take a break without losing progress.
- **Sound Effects** → Toggle sound on/off for eating and game-over events.
- **Responsive UI** → Works smoothly in the browser with styled buttons and overlays.
- **Game Over Overlay** → Displays your final score and restart option.

---

## 🕹️ Controls

- **Arrow Keys** → Control the snake (⬅️ ⬆️ ➡️ ⬇️).
- **Restart Button** → Reset and start a new game.
- **Pause/Resume Button** → Toggle pause mode.
- **Difficulty Select** → Change snake speed.

---

## 📂 Project Structure

```bash
snake-game/
│
├── index.html        # Main game HTML
├── style.css         # (Inline CSS included in index.html)
├── eat.mp3           # Sound effect for eating food
├── gameover.mp3      # Sound effect for game over
└── README.md         # Project documentation
```

---

## 🚀 Getting Started

1. Clone or download this repository:
   ```bash
   git clone https://github.com/yourusername/snake-game.git
   cd snake-game
```

2. Open `index.html` in your browser.

3. Enjoy playing! 🎉

---

## 🔧 Customization

* Change the **snake size** by modifying `const box = 20;`.
* Adjust **colors** of snake, food, and background in the canvas drawing logic.
* Replace `eat.mp3` and `gameover.mp3` with your own sound effects.
* Modify difficulty levels in the `<select>` dropdown.

---

## 📜 Author
Hiruni Ramanayaka

---
