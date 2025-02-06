# React.js Tic-Tac-Toe Application

A feature-rich Tic-Tac-Toe game built with React.js, following React's official tutorial with enhancements. Perfect for learning React fundamentals and state management.

## Features

- **Classic Tic-Tac-Toe Gameplay**: 
  - 3x3 grid interface
  - Alternate turns between "X" and "O"
  - Instant win detection (horizontal, vertical, diagonal)
  - Draw detection when board is full

- **Enhanced Features**:
  - **Game History**: Track all moves with timestamp
  - **Time Travel**: Jump to any previous game state
  - **Win Highlight**: Visual indication of winning combination
  - **Sortable History**: Toggle move list order (ascending/descending)
  - **Responsive Design**: Works on desktop & mobile devices
  - **Reset Button**: Start new game at any point

- **Developer-Friendly**:
  - Clean component structure
  - Prop-type validation
  - State management using React hooks
  - Semantic HTML markup
  - CSS Flexbox & Grid layout

## Installation

1. **Clone Repository**
   bash
   git clone https://github.com/Abram-Emad/react.js-tic-tac-toe-application.git
   

2. **Install Dependencies**
   bash
   cd react.js-tic-tac-toe-application
   npm install
   

3. **Start Development Server**
   bash
   npm start
   

4. **Open in Browser**
   
   http://localhost:3000
   

## Usage

1. **Start Game**
   - Click any empty square to begin
   - Player X always starts first

2. **Game Controls**
   - **Move History**: Click previous moves to time-travel
   - **Sort Toggle**: Switch between ascending/descending move order
   - **Reset Game**: Start fresh with "New Game" button

3. **Winning Condition**
   - First player with 3 matching symbols in a row wins
   - Game automatically detects and announces winner

## Technologies

- **Core**
  - React.js (Functional Components)
  - React Hooks (useState)
  - JavaScript (ES6+)
  - HTML5 Semantic Elements
  - CSS3 (Flexbox, Grid, Animations)

- **Tooling**
  - Create React App (Boilerplate)
  - npm (Package Management)
  - Git (Version Control)

## Project Structure

- plaintext
- /src
- ├── components
- │   ├── Board.js      # Game board component
- │   ├── Game.js       # Main game logic
- │   └── Square.js     # Individual grid cells
- ├── App.js            # Root component
- ├── index.js          # Entry point
- ├── styles
- │   ├── index.css     # Global styles
- │   └── utils.css     # Utility classes
- └── index.html        # Base HTML template


## Contributing

Contributions welcome! Follow these steps:

1. Fork the repository
2. Create feature branch:
   bash
   git checkout -b feature/your-feature
   
3. Commit changes:
   bash
   git commit -m 'Add some feature'
   
4. Push to branch:
   bash
   git push origin feature/your-feature
   
5. Open Pull Request

## Acknowledgments

- Based on [React's Official Tutorial](https://react.dev/learn/tutorial-tic-tac-toe)
- Enhanced with additional features by Abram Emad
- UI inspired by modern web design principles

---

**Developed by Abram Emad**  
[GitHub Profile](https://github.com/Abram-Emad)  
[Report Issues](https://github.com/Abram-Emad/react.js-tic-tac-toe-application/issues)

