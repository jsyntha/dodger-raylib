# Dodger-raylib 🎮

A simple **C++ game** built using **Raylib**, where you dodge incoming shapes as they speed up over time. The goal is to survive as long as possible and beat your high score!

## 📌 Features
- **Dodge incoming shapes**: Avoid them as they move toward you.
- **Increasing difficulty**: Shapes get faster as the game progresses.
- **Score Tracking**: The game records your highest score.
- **Fullscreen Support**: Toggle fullscreen with `Alt + Enter`.
- **FPS Display**: Show or hide FPS with `1`.

## 🎮 Controls
| Key | Action |
|-----|--------|
| `WASD` | Move the player |
| `Enter` | Start the game |
| `Alt + Enter` | Toggle fullscreen |
| `1` | Toggle FPS display |
| `Esc` | Exit game |

## 🛠 Installation & Running the Game
### ✅ **Option 1: Compiling from Source**
1. **Install Raylib**:  
   Download Raylib from [Raylib’s official website](https://www.raylib.com/) or install via vcpkg:
   ```sh
   vcpkg install raylib
   ```
2. **Add Raylib to Your Project**:
   - Add `raylib/include` to **Include Directories**.
   - Add `raylib/lib` to **Library Directories**.
   - Link `raylib.lib` and `WinMM.lib` in **Additional Dependencies**.

3. **Clone the Repository**:
   ```sh
   git clone https://github.com/jsyntha/dodger-raylib.git
   cd dodger-raylib
   ```

4. **Open in Visual Studio**:
   - Open the `.sln` file.
   - Configure dependencies as listed above.

5. **Build & Run**:
   - Press **F5** to build and start the game.
