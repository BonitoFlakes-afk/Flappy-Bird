# Flappy Bird (Java Swing)

A classic Flappy Bird game clone built from scratch using Java's Swing library for the GUI.

## About The Project

This project is a 2D arcade-style game where the player controls a bird, attempting to fly between columns of green pipes without hitting them. It was built as a fun exercise to practice Java GUI programming, game loop mechanics, and event handling.

## Features

* Classic "flap" mechanic using the **Spacebar**.
* Dynamic, randomly generated pipes.
* Real-time score tracking.
* Collision detection.
* "Game Over" and "Restart" functionality.

## Built With

* **Java**
* **Java Swing** (for the `JFrame`, `JPanel`, and `Timer`)
* **Java AWT** (for `Graphics`, `Font`, and event listeners like `KeyListener`)

## Key Concepts Demonstrated

* **Game Loop:** A `javax.swing.Timer` running at 60 FPS (1000/60) handles game ticks.
* **Event Handling:** `KeyListener` detects the `VK_SPACE` key press to make the bird "flap".
* **2D Graphics Rendering:** All game elements are drawn using `paintComponent` on a `JPanel`.
* **OOP:** `Bird` and `Pipe` inner classes are used to manage object state and properties.
* **Collision Detection:** A simple bounding-box algorithm checks for overlap between the bird and pipes.
* **Game State Management:** A `boolean gameOver` controls the flow of the game, stopping the loops and allowing for a restart.

## How to Run

1.  Ensure you have a Java Development Kit (JDK) installed.
2.  Clone the repository.
3.  Place the following image files in the same directory as the code:
    * `flappybirdbg.png`
    * `flappybird.png`
    * `toppipe.png`
    * `bottompipe.png`
4.  Compile the Java files:
    ```bash
    javac App.java FlappyBird.java
    ```
5.  Run the application:
    ```bash
    java App
    ```
