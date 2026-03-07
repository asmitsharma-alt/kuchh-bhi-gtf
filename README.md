<div align="center">
  <h1>🎬 KUCHH BHI – Guess The Frame</h1>
  <p><strong>The Ultimate Local Multiplayer Movie Trivia Experience.</strong></p>
  <p>🌍 <strong><a href="https://kuchh-bhi-podcast.netlify.app/" target="_blank">Play the Game (Live Preview)</a></strong></p>
  <p>📅 <em>Note: This repository will be updated weekly!</em></p>
</div>

KUCHH BHI is a browser-based party game designed for film enthusiasts. Built as a single-file application, it brings the excitement of a cinematic game show straight to your living room. Gather your friends, project it on a big screen, and get ready to shout out answers! With high-fidelity animations, a dynamic sound engine, and a unique "Rotating Judge" mechanic, it's the perfect game night companion for movie buffs.

---

## ✨ Key Features

### 🎮 Gameplay Mechanics
- **The "Judge" Mechanic**: Unlike standard trivia games where the fastest button press wins, KUCHH BHI relies on the chaos of the living room. Every few rounds, a player from the pool is randomly selected to act as the "Judge". It's their sole responsibility to adjudicate who shouted the correct answer first, adding a thrilling layer of social strategy and friendly arguments!
- **Dual Game Modes**: 
  - *Guess the Frame*: Identify the movie from a single iconic cinematic shot.
  - *Guess the Dialogue*: Recognize the film from a classic quote.
- **Live Leaderboard**: Real-time score tracking with continuous visual feedback to keep the competitive spirit alive.

### ⚙️ Technical Highlights
- **Single-File Architecture**: The entire game lives in a single `index.html` file written in clean Vanilla JS and CSS. **Zero dependencies**. No server, no database, no complex installation—it just runs directly in your browser.
- **Web Audio API Sound Engine**: All audio elements (ticking clocks, UI clicks, fanfares) are synthesized in real-time using the browser's native AudioContext. Absolutely no external sound assets are required, keeping the application extremely fast and lightweight.
- **Cinematic Experience**: Designed for a large screen, the app features a sleek neon aesthetic, smooth CSS transitions, and an immersive particle-based intro sequence.
- **Robust Admin Panel**: A powerful and intuitive live-configuration modal that allows you to:
  - Add, remove, and manage players and their avatars.
  - Create new game sections and inject your own custom movie frames or dialogues on the fly.
  - Adjust timers, customize scoring rules, and tweak volume levels.

---

## 🚀 How to Play

1. **Start Game & Intro**: Connect your computer to a large screen (TV or Projector). Open the game and enjoy the cinematic intro.
2. **Lobby Phase**: Enter the lobby to add the players who will be participating (minimum 2 players).
3. **The Guess**: A movie frame or dialogue appears on screen. Players race to shout out the correct answer!
4. **Judge Phase**: When the timer runs out, the spotlight shifts to the current "Judge". The Judge selects the player who they believe shouted the right answer first.
5. **Scoring & Leaderboard**: The winner's score is updated on the live leaderboard. After a set number of rounds, the Judge role automatically rotates to another player.

---

## 🛠️ Installation & Usage

Getting started couldn't be simpler:

1. **Download** the `index.html` file.
2. **Open** it in any modern web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, or Safari).
3. **Go Full-Screen** (press `F11` on Windows/Linux or `Cmd+Ctrl+F` on macOS) for the best cinematic experience.
4. *Play!*

---

## 🎨 Customization

Want to add your own movie clips, trivia, or inside jokes? 

1. Click the **Gear Icon (⚙️)** on the home screen to open the Admin Panel.
2. Navigate to the **Sections** tab.
3. Add a completely new section or edit existing questions by dropping in your own direct Image URLs or custom dialogue text.
4. *Note:* Your changes are saved dynamically in the browser's memory for the current session.

---

## 💻 Tech Stack

- **Core**: HTML5, CSS3 (Variables, Flexbox/Grid, Animations), Vanilla JavaScript (ES6+)
- **Audio**: Web Audio API (real-time Oscillators & Gain Nodes)
- **Storage**: Local State Management
- **Styling**: Modern CSS Variables for easy theming (Neon/Dark Mode layout)

---

<div align="center">
  <p><em>Created with ❤️ for movie lovers everywhere.</em></p>
</div>
