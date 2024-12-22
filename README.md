# Wordle Clone

A simple Wordle clone built using React.js and JSON Server. This project replicates the popular word-guessing game where players have six attempts to guess a five-letter word.

## Features

- **Interactive Gameplay**: Players can guess a five-letter word, and the game provides feedback for each guess.
  - Green indicates a correct letter in the correct position.
  - Yellow indicates a correct letter in the wrong position.
  - Grey indicates an incorrect letter.
- **Dynamic Word List**: Words are fetched dynamically from a JSON Server.
- **Responsive Design**: The game is optimized for desktop and mobile devices.

## Tech Stack

- **Frontend**: React.js
- **Backend**: JSON Server (for mock API)
- **Styling**: CSS

## Installation and Setup

### Prerequisites

Ensure you have the following installed:
- Node.js
- npm 

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mohdazam0786/wordle-clone.git
   cd wordle-clone
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start JSON Server**:
   JSON Server is used to provide a list of words for the game.
   ```bash
   json-server ./data/db.json --port 3001

   ```

4. **Start the React application**:
   ```bash
   npm run start
   ```

   The application will be available at `http://localhost:3000`.

## How to Play

1. Open the application in your browser.
2. Type a five-letter word in the input field and submit your guess.
3. Observe the feedback for each guess and adjust your next guess accordingly.
4. You have six attempts to guess the correct word.

## Future Enhancements

- **User Authentication**: Allow users to save their progress and track scores.
- **Leaderboard**: Add a feature to compare scores with other players.
- **Daily Challenge**: Introduce a new word every day for all players to guess.
- **Theming**: Add light and dark mode options.

## Contributions

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- Inspired by the original Wordle game by Josh Wardle.
- Thanks to the open-source community for providing tools and resources.
