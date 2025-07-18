# 🌀 Tilting Maze Game

A browser-based physics maze game where you guide rolling balls into the center using a **virtual joystick**. Navigate through the maze, avoid obstacles, and master the tilt mechanics!

🔗 **[Play the Game](https://github.com/user-attachments/assets/369de212-a814-4c2d-af47-876534aff86b)**

---

## 🎮 About the Game

**Tilting Maze Game** simulates the experience of physically tilting a maze to guide balls into a central target zone.  
Designed with smooth physics, dynamic collisions, and a hard mode with black holes for extra challenge!

> 💡 Built with pure **HTML**, **CSS**, and **Vanilla JavaScript** — no external game engines!

---

## 🚀 Features

- 🎯 **Tilt-Based Gameplay**: Rotate the maze with a joystick to influence ball movement.
- 🧠 **Physics Simulation**: Gravity, acceleration, friction, and collision detection.
- 🏁 **Objective**: Get all balls into the central dashed circle.
- ⚫ **Hard Mode**: Black holes appear — avoid them or restart!
- 🎮 **Joystick Interface**: Drag the joystick to simulate tilting.
- 🖱️ **Mouse Control**: Mouse drag translates to game physics.

---

## 🧪 Controls

| Action         | Input                      |
|----------------|----------------------------|
| Start Game     | 🖱️ Click & drag the joystick |
| Reset Game     | ␣ Press the `Spacebar`     |
| Hard Mode      | 🔥 Press `H` or `h`         |
| Easy Mode      | 🌱 Press `E` or `e`         |

---

## 🧰 Built With

| Tech      | Description                        |
|-----------|------------------------------------|
| HTML5     | Page structure                     |
| CSS3      | Styling and animations             |
| JavaScript | Game logic, physics, event handling |
| DOM APIs  | UI manipulation and event listeners |

---

## 📂 Project Structure

```
Tilting-Maze-Game/
│
├── index.html       # Main HTML page
├── style.css        # Styling (maze, balls, joystick)
├── script.js        # Game logic & physics engine
├── Ej Logo.png      # Favicon
└── README.md        # Project documentation
```

---

## 📚 How It Works

### 🔄 Maze Tilting

The maze is rotated using mouse drag on a joystick element, and this rotation simulates tilt using basic trigonometry.

```js
const rotationY = mouseDeltaX * 0.8;
const rotationX = mouseDeltaY * 0.8;
```

These angles are used to calculate **gravity vector components** and update ball velocities.

### ⚙️ Ball Physics

Each ball has:

- `x`, `y` position
- `velocityX`, `velocityY`
- Collisions with maze walls and endpoints
- Friction that slows it down over time

### 🎯 Win Condition

All balls must land in the central dashed circle to win.

### ☠️ Hard Mode (Black Holes)

If any ball enters a black hole, the game ends with an error message and red highlight.

---

## 🔄 Resetting & Difficulty

- Press `Spacebar` to reset the game.
- Press `H` to enter **Hard Mode** (adds black holes).
- Press `E` to return to **Easy Mode**.

---

## 📦 Deployment

To run this project locally:

```bash
git clone https://github.com/Owais41111/Tilting-Maze-game/settings/pages
cd Tilting-Maze-Game
open index.html  # or double click
```

> This is a static project. You can host it via GitHub Pages, Netlify, Vercel, etc.

---

## 🧠 Learning Highlights

This game covers:

- Manual **collision detection** (walls, caps, corners)
- **Trigonometry** for angle & vector math
- Mouse-based **joystick mechanics**
- DOM-based rendering (no canvas!)
- Advanced use of **event listeners** & physics updates

---

## 🧑‍💻 Author

**Ejaz Ahmed**  
🔗 [LinkedIn](https://www.linkedin.com/in/ejaz-ahmed-602a02321/)  
💻 [GitHub](https://github.com/Owais41111)

---

## 📜 License

This project is open source and free to use under the [MIT License](LICENSE).

---

> 🚧 *Looking for enhancements? Add sound effects, score tracking, or mobile touch controls!*

Made with ❤️ using HTML, CSS, and JavaScript
```
