# Wandering Paw

Wandering Paw is a 2D adventure game built using the libGDX framework. The player controls a character navigating through various levels, avoiding obstacles, and collecting items. This project demonstrates principles of object-oriented programming (OOP) and game development techniques.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Usage](#usage)

## Features
- Player character control with smooth movement
- Multiple levels with increasing difficulty
- Obstacle avoidance and item collection
- Dynamic screen transitions
- Sound effects and background music

## Getting Started

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Gradle

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/ShahriarAlvi/Wandering-Paw.git
    cd Wandering-Paw
    ```

2. Import the project into your favorite IDE (IntelliJ IDEA, Eclipse, etc.).

3. Build and run the project using Gradle:
    ```sh
    ./gradlew desktop:run
    ```

## Project Structure
- **core/**: Contains the core game logic.
  - `src/com/mygdx/game/`
    - `MyGdxGame.java`: Main class initializing the game.
    - `Player.java`: Manages player attributes and behaviors.
    - `Obstacle.java`: Manages obstacle attributes and behaviors.
    - `MainMenuScreen.java`: Handles the main menu screen.

- **desktop/**: Contains the desktop-specific launcher.
  - `src/com/mygdx/game/desktop/`
    - `DesktopLauncher.java`: Entry point for the desktop version.

- **assets/**: Contains game assets like images, sounds, and maps.

## Dependencies
- [libGDX](https://libgdx.badlogicgames.com/): Game development framework.
- [Gradle](https://gradle.org/): Build automation tool.

## Usage
1. **Running the Game**:
    ```sh
    ./gradlew desktop:run
    ```

2. **Controls**:
    - Use arrow keys to move the player.
    - Avoid obstacles and collect items to score points.

