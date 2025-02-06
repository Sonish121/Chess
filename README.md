
# Chess Game in C++

This project is a console-based chess game implemented in C++

## Features

- **Two-Player Mode**: Play against another human opponent on the same machine.
- **Console Interface**: Interact with the game through a text-based console interface.
- **Standard Chess Rules**: Implements the standard rules of chess, including valid moves for each piece, check, and checkmate conditions.

## Getting Started

### Prerequisites

- A C++ compiler (e.g., GCC)
- CMake (optional, for building the project)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Chess-game-cpp/chess-game.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd chess-game
   ```

3. **Build the project**:

   - Using CMake:

     ```bash
     mkdir build
     cd build
     cmake ..
     make
     ```

   - Without CMake:

     ```bash
     g++ -o chess main.cpp
     ```

4. **Run the game**:

   ```bash
   ./chess
   ```

## How to Play

- The game starts with the standard chessboard layout.
- Players take turns entering their moves in coordinate notation (e.g., `e2e4` to move a piece from e2 to e4).
- The game checks for the validity of each move and updates the board accordingly.
- The game continues until a checkmate, stalemate, or draw condition is reached.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.


## Acknowledgments

- Inspired by various open-source chess implementations in C++.
- Special thanks to the contributors of the [Chess Console Game in C++](https://www.codeproject.com/Articles/1214018/Chess-Console-Game-in-Cplusplus) for their insights.

For more information, visit the [project repository](https://github.com/Chess-game-cpp/chess-game).
# Chess
