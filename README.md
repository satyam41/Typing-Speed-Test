# Typing Speed Tester Documentation

## Overview

The Typing Speed Tester is a web-based application that allows users to test and improve their typing speed and accuracy. It presents users with random quotes to type and provides real-time feedback on their performance, including words per minute (WPM), characters per minute (CPM), errors, and accuracy.

## File Structure

The application consists of three main files:

1. `html/index.html`: The main HTML structure of the application.
2. `css/style.css`: The CSS file for styling the application.
3. `js/script.js`: The JavaScript file containing the application logic.

## HTML Structure (`index.html`)

The HTML file defines the structure of the application, including:

- A container for the entire application
- A heading
- A header section displaying metrics (WPM, CPM, Errors, Time, Accuracy)
- A quote display area
- An input area for typing
- A restart button

Key elements have specific IDs and classes for JavaScript manipulation and CSS styling.

## CSS Styling (`style.css`)

The CSS file provides styling for the application, including:

- A yellow-orange background (`#fe9801`)
- Flexbox layout for the container
- Styled boxes for displaying metrics
- Formatting for the quote and input areas
- Styles for correct and incorrect characters
- Responsive design elements

## JavaScript Functionality (`script.js`)

The JavaScript file contains the core functionality of the application:

### Variables and Selectors

- Time limit and quote array
- DOM element selectors
- Game state variables (errors, accuracy, time, etc.)

### Functions

1. `updateQuote()`: Displays a new quote for typing.
2. `processCurrentText()`: Handles user input and updates metrics.
3. `startGame()`: Initializes a new game session.
4. `restValues()`: Resets all game values to their initial state.
5. `updateTimer()`: Updates the countdown timer.
6. `finishGame()`: Handles the end of the game and displays final results.
7. `setupEventListeners()`: Sets up event listeners for user interactions.

### Game Flow

1. The game starts when the user focuses on the input area.
2. A 60-second timer begins counting down.
3. The user types the displayed quote.
4. Real-time feedback is provided on accuracy and errors.
5. When the timer reaches zero, the game ends and displays final results.
6. The user can restart the game using the restart button.

## Usage

To use the Typing Speed Tester:

1. Open the `index.html` file in a web browser.
2. Click on the input area to start the game.
3. Type the displayed quote as accurately and quickly as possible.
4. View your results in real-time and after the game ends.
5. Click the restart button to play again.

## Customization

To customize the application:

- Add or modify quotes in the `quotes_array` in `script.js`.
- Adjust the time limit by changing the `TIME_LIMIT` variable in `script.js`.
- Modify the styling by editing `style.css`.

## Browser Compatibility

This application should work in modern web browsers that support ES6 JavaScript features.

---

This documentation provides an overview of the Typing Speed Tester application, its file structure, main components, and functionality. It can serve as a guide for understanding, using, and potentially extending the application.
