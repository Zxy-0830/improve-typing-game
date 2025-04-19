# Typing Carnival

**Typing Carnival** is a typing game where players increase their score by typing the displayed words correctly. The game is timed, and after it ends, the player's score is shown and stored in local storage. Players can view the top 9 high scores, and the game also supports restarting the game.

## Features

- **Typing Timer**: After the game starts, players need to type the displayed words within the given time limit.
- **Scoring System**: The score increases by 1 each time a word is typed correctly.
- **History of Scores**: After the game ends, the player's score is saved, and the top 9 high scores can be viewed.
- **Local Storage**: Uses `localStorage` to store high scores, ensuring scores persist even after the page is refreshed.
- **Top Scores Sorting**: Scores are sorted by hits from high to low, and only the top 9 records are stored.
- **Stylish Design**: The game features a clean interface with a scoreboard styled using modern CSS properties and animations.

## How to play

Gameplay
Click the "Start" button to begin the game. A word will appear on the screen.

Players need to type the word as quickly as possible.

For each correct word typed, the score increases by 1, and a new word is displayed.

When the timer runs out, the final score is shown, and the score is saved to local storage.

You can click the "Restart" button to start a new game.

High Score Leaderboard
Scores are sorted by the player's score (hits), and the top 9 scores are displayed on the right side of the screen. If a player completes the game and gets a high score, their score is saved to local storage. The game keeps a maximum of 9 high scores.

Notes
Ensure your browser supports localStorage, as the game relies on it to store high scores.

You can customize the background music and word list according to your preferences.
