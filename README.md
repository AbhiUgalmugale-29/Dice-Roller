# Dice Roller

A simple web-based dice roller built with HTML, CSS, and JavaScript. This app allows users to roll a virtual six-sided dice, displaying a random result from 1 to 6, with an automatic reset after 3 seconds.

## How It Works

1. The page starts with a default dice image (`dice.png`).
2. When the "Roll Dice" button is clicked, the JavaScript function `rollDice()` generates a random number between 1 and 6.
3. Based on the random number, the corresponding dice image (`1.png` to `6.png`) is displayed.
4. After 3 seconds, the dice resets back to the default image (`dice.png`).

## Technologies Used

- **HTML**: For the structure and layout of the webpage.
- **CSS**: For styling the dice roller (inline within the HTML file).
- **JavaScript**: For implementing the dice roll logic, random number generation, and image switching.
- **Images**: Dice face images (`1.png` to `6.png`, and `dice.png` for the default state) are used to display the result of the dice roll.
