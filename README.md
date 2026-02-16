# 🐰 Hare-y Situation

**Hare-y Situation** is a fast-paced, "Whack-a-Mole" style browser game. Test your reflexes by saving bunnies while avoiding dangerous bombs! This project features custom **Lottie (JSON) animations** for a high-quality visual experience.

## 🚀 Live Demo
**[PLAY THE GAME HERE](https://abir-abc.github.io/Hare-y-Situation/)**
---

## 🎮 How to Play
* **🐹 Bunny:** Whack them to gain **1 point**.
* **👑 Gold Bunny:** Rare! Whack for a **+5 point bonus** and a fullscreen celebration.
* **💣 Bomb:** Avoid these! Hitting a bomb costs you **1 Heart**.
* **Goal:** Get the highest score possible before you run out of hearts!

## ✨ Custom Features
* **Lottie Animations:** Uses high-performance JSON-based animations for the "Poof," "Explosion," and "Gold Sparkle" effects.
* **Responsive Design:** Playable on both desktop and mobile devices.
* **Haptic Feedback:** Includes vibration effects for Android devices when hitting bonuses or bombs.
* **High Score Tracking:** Your best score is saved locally in your browser.

## 🛠️ Built With
* **HTML5** - Structure and layout.
* **CSS3** - Styling and custom animations.
* **JavaScript (ES6)** - Game logic and coordination.
* **LottieFiles** - Vector-based JSON animations.

## 📁 Project Structure
```text
Hare-y-Situation/
│
├── index.html        # Main game entry point
├── style.css         # Visual styling and layout
├── script.js         # Game mechanics and Lottie triggers
├── README.md         # Project documentation
└── effects/          # Folder containing JSON animations
    ├── bunny.json    # Poof animation for bunnies
    ├── explosion.json # Blast animation for bombs
    └── sparkle.json  # Fullscreen bonus animation
