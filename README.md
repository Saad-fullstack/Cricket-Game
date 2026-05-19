🏏 Bat Ball Stumps Cricket Game

A fun mini cricket game built with **HTML, CSS, and JavaScript** where you play against the computer using three cricket actions:

* 🏏 Bat
* ⚾ Ball
* 🪵 Stumps

Inspired by the classic **Rock Paper Scissors** game, but with a cricket twist.

🚀 Live Demo

👉 [Play the Game Here](https://cricket-game-indol.vercel.app/?utm_source=chatgpt.com)

🎮 How to Play

Choose one option:

* 🏏 **Bat**
* ⚾ **Ball**
* 🪵 **Stumps**

The computer will randomly choose one option too.

Winning Rules

| Your Choice | Defeats   |
| ----------- | --------- |
| 🏏 Bat      | ⚾ Ball    |
| ⚾ Ball      | 🪵 Stumps |
| 🪵 Stumps   | 🏏 Bat    |

If both choices are the same, the result is a "Tie".

✨ Features

✅ Random computer choice generation
✅ Instant result popup using JavaScript `alert()`
✅ Smooth hover and click button effects
✅ Simple and beginner-friendly project
✅ Clean and responsive design
✅ Easy to understand game logic

# 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript

# 🧠 How the Logic Works

The game uses:

* `Math.random()` to generate the computer's choice
* `if-else` conditions to decide:

  * Win
  * Lose
  * Tie

Example:

```js
let randomNumber = Math.random() * 3;
```

This generates a random value and assigns:

* Bat
* Ball
* Stumps

to the computer.

# 📂 Project Structure

```bash
Cricket-Game/
│
├── index.html
├── README.md
└── assets/
```

---

# ▶️ Run Locally

Clone the repository:

```bash
git clone <your-repository-link>
```

Open the folder and run:

```bash
index.html
```

in your browser.

---

# 📈 Future Improvements

* Add score tracking
* Add sound effects
* Add animations
* Store scores using Local Storage
* Add dark/light mode
* Improve mobile UI

---

# 💡 What I Learned

While building this project, I practiced:

* DOM interaction
* JavaScript conditions
* Random number generation
* Event handling
* UI styling with CSS

---

# 👨‍💻 Author

@Saad-fullsatck

# ⭐ Support

If you liked this project:

* Give it a ⭐ on GitHub
* Share it with friends
* Fork it and improve it yourself

---
