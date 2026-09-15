# 🎮 Arkanoid Game Clone

A 2D game inspired by the classic Arkanoid, developed with Unity and C# as a personal project to practice game development fundamentals and gameplay programming.

The project recreates the core brick-breaker mechanics while implementing player movement, ball physics, collision handling, lives, multiple levels, sound effects, and game-over logic.

🕹️ About the Game
The player controls a paddle horizontally and must keep the ball in play while destroying all the bricks in the level.
When the ball reaches the dead zone, the player loses a life and the level is reset. After losing all available lives, the game transitions to a Game Over scene.
Destroying all the bricks advances the player to the next level.

✨ Features
Paddle movement using keyboard input
Ball physics using Rigidbody2D
Collision detection with paddle, bricks, walls, and dead zone
Destructible bricks
Life system
Level progression
Game Over scene
Player and ball reset system
Sound effects for different collision types
Scene management

🛠️ Built With
Unity
C#
Unity 2D Physics
Unity Scene Management
Unity Audio System

🎮 Controls
Left / Right Arrow Keys or A / D — Move the paddle

🧠 Gameplay Systems

The project is divided into several gameplay components:

Player.cs — Handles paddle movement and reset behavior.
Ball.cs — Controls ball initialization, physics, collision sounds, and reset behavior.
Brick.cs — Handles brick destruction and level-completion checks.
GameManager.cs — Manages player lives, level resets, and level progression.
GameOverScene.cs — Handles restarting the game after Game Over.

📚 What I Learned

This project helped me practice fundamental concepts of game development with Unity and C#, including:

Working with MonoBehaviour
Player input
2D physics and Rigidbody2D
Collision detection
Game object interaction
Scene management
Basic game-state logic
Audio feedback
Organizing gameplay logic into separate scripts

It was one of my first complete projects using Unity and helped me understand how different gameplay systems interact inside a game.

🚀 Running the Game

You can play the game directly without opening the Unity project.

Open the exe folder.
Run Arkanoid.exe.
The game will start immediately.

No additional installation or Unity setup is required to play the game.



Opening the project in Unity

If you want to inspect or modify the source project:

Clone this repository.
Open Unity Hub.
Select Add project from disk.
Select the repository folder.
Open the project using a compatible Unity version.

📂 Project Structure
Assets/
├── Scenes/
├── Scripts/
├── Sprites/
├── Audio/
└── ...

Packages/
ProjectSettings/

🔮 Possible Future Improvements

Possible improvements for future versions could include:
Power-ups
Different brick types
Score system
Difficulty progression
Improved UI
More levels
Visual effects
High-score system

👨‍💻 Author
Franco Fiuri

Personal project developed as part of my learning process in software and game development.
