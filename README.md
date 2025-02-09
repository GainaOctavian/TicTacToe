
# Tic Tac Toe - C# WPF Implementation

**Project by Aurelian-Octavian Găină**  
*Classic Tic Tac Toe Game developed using C# and WPF*

## 🎮 Overview

This project is a Windows Presentation Foundation (WPF) application that implements the classic Tic Tac Toe game. The project leverages the C# programming language for the game logic and XAML for designing the user interface.

## 🚀 Features

- **Two-Player Mode:** Play locally with a friend.
- **Simple and Intuitive UI:** Clean interface designed using XAML.
- **Win Detection:** Automatic detection of win conditions and tie scenarios.
- **Score Tracking:** Keeps track of the current scores between players.

## 🛠️ Technologies Used

- **C# (.NET Framework 4.7.2)**
- **WPF (Windows Presentation Foundation):** For building the graphical user interface.
- **XAML:** For UI layout and design.

## 📂 Project Structure

```
TicTacToe/
├── App.xaml                # Application configuration and startup
├── App.xaml.cs             # Application logic
├── MainWindow.xaml         # Main game window layout
├── MainWindow.xaml.cs      # Game logic (handling player moves, win conditions)
├── GameState.cs            # Manages game state transitions
├── Player.cs               # Player model
├── GameResult.cs           # Win/Loss/Draw result handling
├── WinInfo.cs              # Details about win conditions
├── Assets/                 # Game assets (icons, images)
└── TicTacToe.sln           # Visual Studio solution file
```

## ⚙️ How to Run

### Prerequisites
- **.NET Framework 4.7.2 or later**
- **Visual Studio 2019 or later** with WPF support

### Running the Application

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/GainaOctavian/TicTacToe.git
   cd TicTacToe
   ```

2. **Open the Solution:**
   - Launch **Visual Studio**.
   - Go to `File -> Open -> Project/Solution` and select `TicTacToe.sln`.

3. **Build and Run:**
   - Press `F5` to build and run the application.

## 🎯 Gameplay Instructions

- **Player 1 (X)** and **Player 2 (O)** take turns marking the cells in a 3x3 grid.
- The first player to align three marks horizontally, vertically, or diagonally wins.
- If all cells are filled without any winning combination, the game ends in a draw.

## 📈 Future Improvements

- Add an AI opponent for single-player mode.
- Implement different board sizes (e.g., 4x4, 5x5).
- Enhance UI with animations and sound effects.

## 🙌 Credits

This project was developed by Aurelian-Octavian Găină as a practical exercise in C# programming, WPF development, and game logic implementation.
