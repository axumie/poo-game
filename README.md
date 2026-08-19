# Poo Game

A small 2D C++ game developed with the **Chili Framework** as part of my work through ChiliTomatoNoodle's C++ game programming tutorials.
The project started from the tutorial's Poo Game and evolved as I continued experimenting with the codebase and applying the concepts covered throughout the series. The repository preserves the original tutorial history while also containing my extensions and modifications.

## 🎮 About the Game

Poo Game is a simple arcade-style 2D game centered around a player-controlled character (`Dude`) and randomly positioned obstacles/enemies (`Poo`).
The original project was introduced in **Tutorial 8** of ChiliTomatoNoodle's Beginner C++ Game Programming series. The tutorial covers game entities, movement, collision detection, screen boundaries, random number generation, and basic game states.
This project was subsequently used as a foundation for exploring additional C++ and game-programming concepts.

## 👾 GamePlay
<img width="986" height="733" alt="image" src="https://github.com/user-attachments/assets/fe46be5a-604c-4b50-8c87-67d59de24807" />


## 🛠️ Technologies

* **C++**
* **Chili Framework**
* **DirectX-based rendering**
* **Visual Studio**
* **Windows**
* Standard C++ library

## ✨ My Work

In addition to the original tutorial foundation, I continued developing the project and implemented/refactored several features:

* Introduced a custom `Vec2` type for 2D vector mathematics.
* Implemented vector addition, subtraction, scalar multiplication, length, and normalization operations.
* Migrated game/entity movement code to use `Vec2`.
* Added delta-time based entity updates to make movement independent of frame rate.
* Implemented movement toward the mouse cursor.
* Added a toggleable cursor-directed movement mode.
* Fixed diagonal movement so that its speed remains consistent with horizontal and vertical movement.
* Continued refactoring the existing entity and movement code while working through the tutorial series.

The Git history documents this progression, from the original tutorial code through the later vector, timestep, and movement work.

## 📚 Learning Focus

This project has been particularly useful for practicing:

### C++

* Classes and object-oriented design
* Constructors and member initialization
* References and `const` correctness
* Operator overloading
* `static` and `constexpr`
* Standard library utilities
* Random number generation
* `std::chrono`
* Basic vector mathematics

### Game Programming

* Game loops
* Entity updates
* Frame-rate independent movement
* Delta time
* 2D positions and directions
* Vector normalization
* Collision detection
* Screen-boundary handling
* Mouse and keyboard input
* Basic game-state logic

### Graphics / Framework

* 2D rendering
* Sprite-based drawing
* Input handling
* Working with the Chili Framework
* Building and debugging a Windows C++ game in Visual Studio

## 🎓 Tutorial & Credits

This project is based on the **Beginner C++ Game Programming** series by **ChiliTomatoNoodle**.
The original Poo Game is introduced in Tutorial 8 and is subsequently revisited throughout the series to demonstrate additional C++ and game-programming concepts.

* [ChiliTomatoNoodle's Poo Game repository](https://github.com/planetchili/poo_game)
* [Beginner C++ Game Programming Series](https://wiki.planetchili.net/index.php/Beginner_C%2B%2B_Game_Programming_Series)

The original tutorial code and commits remain part of the repository history. My subsequent work is represented by the later commits on the development branch.

## 📌 Project Status

This is a learning project and an evolving codebase rather than a finished commercial game.
The main purpose of the project is to practice C++, game-programming fundamentals, vector mathematics, timing, input handling, and incremental codebase refactoring while building on a working game.

## 🚀 Building

The project is intended to be built on **Windows using Visual Studio** with the Chili Framework.
Open the Visual Studio solution and build the project using the appropriate configuration.

> The exact build requirements depend on the version of the Chili Framework used by the project.
