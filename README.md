# Memory Game

TA fun and interactive memory matching game built with React. The goal is to match pairs of cards by flipping them over, testing your memory skills. Keep track of the number of turns and try to improve with each game!

![image](https://github.com/user-attachments/assets/b3364808-1fad-4418-874b-98ca1e2780a3)


## Features
- ard Matching: Flip over two cards and match their images.
- Turn Counter: Keeps track of the number of turns taken.
- New Game: Shuffle the cards and start a new game anytime.
- Interactive UI: Responsive and dynamic design for a great user experience.

### Technologies Used

- React: For creating reusable components and managing state.
- CSS: Custom styling for the game layout and animations.

# Project Structure

```
.
├── public                # Static assets (e.g., images)
├── src
│   ├── components
│   │   └── SingleCard.js # Card component
│   ├── App.js            # Main application file
│   ├── App.css           # Styles for the application
│   └── index.js          # Entry point for the React app
├── package.json          # Project metadata and dependencies
└── README.md             # Project documentation
```.

# Component Overview

- App.js: The main component that handles the game logic, card shuffling, and state management.
- SingleCard.js: A reusable card component that handles flipping and displaying card images.

# How to Play

1. Start a Game: Click the New Game button to shuffle the cards and reset the game.
2. Flip Cards: Click on two cards to flip them over.
3. Match Cards: If the two flipped cards match, they remain visible. If not, they flip back after a short delay.
4. Track Turns: The number of turns is displayed at the bottom of the screen. Try to match all pairs in as few turns as possible.


## Project setup

1. Clone the repository:

```
git clone https://github.com/your-username/memory-game.git
cd memory-game
```
2. Install dependencies:
   
```
npm install
```

3. Run the app:
```
npm run serve
```

The app will now be running on http://localhost:3000.

# Customization

- Card Images: Update the cardImages array in App.js to use different images for the cards. Add images to the /public/img directory and update the src paths.
- Styling: Modify the CSS in App.css or SingleCard.css to change the appearance of the cards and layout.
