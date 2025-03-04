# 🎮 2D-Fighting-Game
This is a 2D fighting game built using JavaScript and HTML5 Canvas, featuring two characters—Ninja and Samurai —battling in a side-scrolling environment. The game includes animated sprites, smooth character movement, and combat mechanics such as attacks, jumps, and health depletion. 

![image](https://github.com/user-attachments/assets/693b3ebb-404d-478d-ae44-5b16d53c06e1)


## Features:

**✅ Character Animations:** Idle, running, jumping, falling, attacking, taking hits, and death animations.

**✅ Combat System:** Players can perform basic attacks and take damage when hit.

**✅ Health & Timer:** Players have a health bar, and the game ends when a player's health reaches 0 or time runs out.

**✅ Collision Detection:** Ensures attacks register only when they hit the opponent.

**✅ Dynamic Background & Objects:** The game includes an animated background and static objects like a shop.



## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/qalahmad/2D-Fighting-Game.git


2. **Open in a browser:**

Navigate to the project folder and open index.html (no server required).



## 🕹️ Controls
  **Player 1 (Samurai):**
- A: Move left

- D: Move right

- W: Jump

- Space: Attack


**Player 2 (Ninja):**
- ←: Move left

- →: Move right

- ↑: Jump

- ↓: Attack



## 🎚️ Customization
**Modify the game easily by:**

- Adding new sprites in img/samurai or img/ninja.

- Adjusting gravity/velocity in index.js:
  ```bash
  const gravity = 0.7; // Modify this value
- Changing attack damage in classes.js:
  ```bash
  takeHit() {
  this.health -= 20; // Adjust damage value
  }


## 🙌 Acknowledgments:
- Built using HTML5 Canvas and [GSAP](https://gsap.com/) for animations.
- Inspired by classic fighting games like Street Fighter and Mortal Kombat.


