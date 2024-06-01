# Chess System in Java

Welcome to the Chess System project! This project implements a simple chess game using Java. The main objective is to demonstrate the application of object-oriented programming principles and to provide a playable chess game that runs in the console.

## Features

- Complete chess game implementation with all standard chess rules.
- Console-based user interface.
- Handles input errors and invalid moves.
- Supports special moves like castling, en passant, and promotion.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher.
- A text editor or an Integrated Development Environment (IDE) like IntelliJ IDEA, Eclipse, or VSCode.

### Running the Application

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/chess-system-java.git
    ```

2. Navigate to the project directory:
    ```sh
    cd chess-system-java
    ```

3. Compile the application:
    ```sh
    javac -d bin src/application/Main.java
    ```

4. Run the application:
    ```sh
    java -cp bin application.Main
    ```

## How to Play

1. The game starts by displaying the chessboard.
2. When prompted, enter the source position (e.g., `e2`) of the piece you want to move.
3. The possible moves for the selected piece will be displayed.
4. Enter the target position (e.g., `e4`) where you want to move the piece.
5. The game will handle special cases like pawn promotion, check, and checkmate.
6. The game ends when a checkmate occurs.

## Code Overview

### Main Class

The `Main` class is the entry point of the application. It handles user input and controls