# dodger-raylib
A simple C++ game using raylib where you dodge randomly spawning shapes while the difficulty increases over time. The goal is to survive as long as possible and achieve the highest score!

🎮 Gameplay

Control a red circle (the player) using WASD.

Avoid the colored shapes that spawn randomly and move toward you.

The longer you survive, the faster the shapes become.

Press Enter to start the game.

Press Alt + Enter to toggle fullscreen mode.

Press 1 to toggle FPS display.

Press Escape to quit the game.

📌 Features

Smooth movement and collision detection.

Dynamic difficulty scaling – shapes increase in speed over time.

Game over and restart system.

Custom rendering using RenderTexture2D for improved visual scaling.

Fullscreen toggle and window centering.

Score tracking with high score display.

🛠️ Dependencies

This project requires raylib. Make sure you have it installed before running the game.

Installing raylib

Windows (MSVC):

Download the latest raylib release from raylib official site.

Add raylib/include to your Additional Include Directories.

Add raylib/lib to your Additional Library Directories.

Link raylib.lib and WinMM.lib in Additional Dependencies.

🚀 Building and Running

Windows (Visual Studio)

Clone the repository:

git clone https://github.com/jsyntha/dodger-raylib.git
cd dodger-raylib

Open the Visual Studio solution (.sln) or create a new C++ project.

Add raylib.lib; WinMM.lib; to Linker -> Input -> Additional Dependencies.

Set up Include and Library directories as mentioned above.

Build and run the project!
