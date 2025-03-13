# Snake Game 🐍

A classic Snake Game built using Python and Turtle Graphics.

## 🖥️ Preview
A simple snake game where you control a snake using the keyboard and try to eat food to grow while avoiding collisions with the walls and yourself.

## 🎮 Controls
- **W** → Move Up
- **S** → Move Down
- **A** → Move Left
- **D** → Move Right

## 🛠️ Installation & Usage

### Windows / Linux / macOS
1. Install Python (if not installed): [Download Python](https://www.python.org/downloads/)
2. Install required dependencies:
   ```
   pip install turtle
   ```
3. Run the game:
   ```
   python snake.py
   ```

### 📱 Termux (Android)
1. Install Termux from [F-Droid](https://f-droid.org/en/packages/com.termux/) (recommended) or Play Store.
2. Update Termux packages:
   ```
   pkg update && pkg upgrade -y
   ```
3. Install required dependencies:
   ```
   pkg install python python-tkinter x11-repo tigervnc -y
   ```
4. Start VNC server:
   ```
   vncserver :1
   ```
5. Use a VNC Viewer app (like `bVNC`) to connect to `localhost:1`
6. Run the game:
   ```
   python snake.py
   ```
7. Enable Display:
   ```
   export DISPLAY=:1
   ```
## 🚀 Features
- Classic Snake Game mechanics
- Score tracking with High Score feature
- Smooth gameplay experience

## 📜 License
This project is open-source and available under the MIT License.

---

**GitHub Repository**: [@y-nabeelxd/Snake-Game.py](https://github.com/y-nabeelxd/Snake-Game.py)
