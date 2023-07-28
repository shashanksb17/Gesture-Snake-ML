# Machine Learning Snake Game 


## Introduction

"Gesture Snake" is a web-based snake game where players can control the movement of the snake using hand gestures detected through a webcam. The game is built using HTML, JavaScript, and TensorFlow.js for the machine learning part.

## Project Components

The project consists of the following components:

1. HTML:
   - index.html: The main HTML file containing the layout and structure of the game interface.

2. CSS:
   - style.css: The stylesheet containing the visual styling of the game interface.

3. JavaScript:
   - index1.js: The main JavaScript file responsible for controlling the game logic and interactions.

4. Machine Learning Model:
   - TensorFlow.js and Teachable Machine Pose Model: The machine learning model is trained using Teachable Machine to detect hand gestures and map them to specific movements for controlling the snake in the game.

## How the Game Works

1. **Game Controls**:
   - The game can be controlled using hand gestures captured through the webcam.
   - Gestures include thumbs up, thumbs down, pointing right, pointing left, and showing the palm towards the camera.
   - The gestures are mapped to specific movements for the snake: up, down, right, left, and pause.

2. **Game Interface**:
   - The game interface displays the snake board, score, and hi-score information.
   - The snake board consists of a grid where the snake and food are displayed.

3. **Game Logic**:
   - The game uses an array to store the positions of the snake's body parts and the food.
   - The snake moves according to the player's gestures and attempts to eat the food to increase the score.
   - If the snake collides with the wall or itself, the game ends, and the player can restart by pressing any key.

4. **Machine Learning Integration**:
   - The machine learning model is loaded using TensorFlow.js and Teachable Machine Pose Model.
   - The webcam captures frames, and the pose estimation is done using the Teachable Machine model.
   - The machine learning model predicts the gesture made by the player, and the corresponding movement is mapped to control the snake.

## Dependencies

The project relies on the following libraries and APIs:

- [TensorFlow.js](https://www.tensorflow.org/js): A JavaScript library for machine learning in the browser.
- [Teachable Machine Pose Model](https://github.com/googlecreativelab/teachablemachine-community/tree/master/libraries/pose): A model provided by Teachable Machine for pose estimation.

## Getting Started

To play the "Gesture Snake" game:

1. Ensure that your computer has a webcam connected.

2. Open the `index.html` file in a web browser that supports webcam access.

3. Click on the "Start" button to initialize the webcam and start playing.

4. Make hand gestures as instructed in the game interface to control the snake.

5. Eat the food, avoid collisions, and aim for the highest score possible!

## Conclusion

The "Gesture Snake" project demonstrates the integration of machine learning into a classic snake game, allowing players to control the snake's movements using hand gestures captured through the webcam. The game showcases the potential of machine learning technologies in creating novel and interactive gaming experiences.

**Note**: Before running the project, ensure that all necessary files, including the machine learning model files, are correctly linked and accessible. Additionally, make sure your web browser supports webcam access for the game to function properly.
