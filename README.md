# Car Racing Game Readme

This is a simple car racing game implemented using HTML, CSS, and JavaScript.

## Features

* **Car Selection:** Choose from a selection of cars before starting the race. Some cars may be locked.
* **Dynamic Racing:** Race against the clock and avoid obstacles.
* **Obstacles:** Watch out for tractors, school buses, and pickup trucks!
* **Controls:** Use left and right arrow keys (or on-screen buttons) to control your car.
* **Game Stats:** Track your time, points, and speed during the game.
* **Upgrades:** The game features a rudimentary upgrade system, showing Speed, Handling, and Acceleration. These appear to be randomly generated.
* **Game Over:** The game ends if you crash or take too long without crashing.
* **Game Over Modal:** Displays your final stats (points, time, speed) and provides options to play again or return to the main menu.
* **Responsive Design:** The game adapts to different screen sizes.

## How to Play

1.  **Car Selection:**
    * The game starts with a car selection screen.
    * Select an available car. Locked cars cannot be chosen.
    * A preview of the selected car is displayed.
    * The stats for the selected car are shown (Speed, Handling, Acceleration).
2.  **Start Game:**
    * Click the "PLAY" button.
    * The car selection screen will disappear, and the game canvas will appear.
3.  **Controls:**
    * Use the left ("⬅️") and right ("➡️") arrow keys to steer your car.
    * On-screen buttons are also provided for touch controls.
4.  **Game Play:**
    * Avoid obstacles (tractors, school buses, and pickup trucks).
    * Your time, points, and speed are displayed at the top left.
    * The game speed increases over time.
5.  **Game Over:**
    * The game ends if you crash into an obstacle. A "crash-effect" is briefly displayed.
    * The game also ends if you take too long without a collision (30 seconds).
    * A "Game Over" modal appears, showing your final stats.
6.  **Game Over Modal Options:**
    * **Play Again:** Restarts the game.
    * **Main Menu:** Returns to the car selection screen.

## Technical Details

* **HTML:** Provides the structure of the game, including the car selection screen, game canvas, controls, and modals.
* **CSS:** Styles the game, including the layout, car selection, game screen, buttons, and modals. The game is responsive, adapting to different screen sizes using media queries.
* **JavaScript:** Implements the game logic, including:
    * Car selection and preview.
    * Game initialization and reset.
    * Car movement and obstacle generation.
    * Collision detection.
    * Scoring, timing, and speed increase.
    * Game over handling and modal display.
    * Animation using `requestAnimationFrame`.

## Assets

* Car images are located in the `images/car_select/` folder.
* Obstacle images are located in the `images/` folder
* Collision effect image is `images/collision.webp`
