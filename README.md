# Turtle Crossing Game 🐢🚗



![5151521](https://github.com/user-attachments/assets/d470f53e-82b8-4c9e-b5e4-c87cbb058c49)

You can check out the demo on [YouTube](https://www.youtube.com/watch?v=j5UCbcqZXks)

<hr>

**About the Project**
This is a simple turtle crossing game, similar to Frogger. The player, a turtle, must cross a busy road without being hit by cars. When the turtle successfully crosses to the other side, the game levels up and the cars speed up, increasing the difficulty. The game ends if the turtle collides with a car.

---

## How to Play

* **Use the up arrow key** (or the **w** key, depending on your key binding) to move the turtle forward.
* The goal is to cross the screen to the finish line at the top.
* Avoid the cars!

---


## Project Structure

* **`main.py`:** This is the heart of the game. It contains the **main game loop**, sets up the screen, and manages the overall game flow. Its responsibilities include checking for **collisions** and **level progression** and calling methods from the other classes as needed.
* **`player.py`:** This file defines the **`Player` class**, which controls the turtle's movement and handles its **reset logic** after it crosses the finish line or collides with a car.
* **`car_manager.py`:** This file defines the **`CarManager` class**. It's in charge of creating, moving, and accelerating all the **car objects** in the game.
* **`scoreboard.py`:** This file defines the **`Scoreboard` class**, which is responsible for displaying the **current level** and showing the **"Game Over" message**.

---
