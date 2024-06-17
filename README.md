# Stick Hero Game Clone

This project is a clone of the popular Stick Hero game, developed using Object-Oriented Programming (OOP) concepts and the JavaFX library. The game includes core mechanics such as a pause menu, point collection, animations, character and scene transitions, and more.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Design Patterns](#design-patterns)
- [Setup](#setup)
- [How to Play](#how-to-play)
- [Contributions](#contributions)

## Introduction
Stick Hero Game Clone is a Java-based application created by Akshat Raj Saxena (2022054) and Vansh Agarwaal (2022558). The game replicates the Stick Hero gameplay experience using JavaFX for the user interface and animation handling.

## Features
- Home Screen with background music control and exit button.
- Gameplay Screen where the stick extends with mouse events and falls.
- Game Screen with infinite platform generation and collision checking.
- Singleton Design Pattern for Score Management.
- Observer Design Pattern for Player Handling.
- JUnit test cases for key functionalities.

## Design Patterns
### Singleton Pattern
Used for managing score throughout the game, ensuring that only one instance of the ScoreManager exists.

### Observer Pattern
Implemented for player actions, allowing the game to respond to changes in the player's state.

## Setup
### Prerequisites
- Java Development Kit (JDK) 20 or higher
- Apache Maven

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/VanshAg283/StickHeroGame.git
    ```
2. Navigate to the project directory:
    ```sh
    cd StickHeroGame
    ```
3. Build the project using Maven:
    ```sh
    mvn clean install
    ```
4. Run the application:
    ```sh
    mvn javafx:run
    ```

## How to Play
- **Extend the Stick:** Hold your mouse button to extend the stick.
- **Release the Stick:** Release the mouse button to let the stick fall.
- **Objective:** Ensure the stick reaches the next platform to keep progressing.

## Contributions
- **Akshat Raj Saxena:** Developed the HomeScreen, implemented the basic game logic, created UML diagrams, and cherry pick logic.
- **Vansh Agarwaal:** Developed GameScreen and GamePlayScreen, implemented design patterns, and created JUnit test cases.

