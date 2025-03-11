# Simple_Game_AI_for_Rock-Paper-Scissors_202401100300273
# Adaptive AI for Rock-Paper-Scissors

## Introduction
This project is an AI-powered **Rock-Paper-Scissors** game where the AI learns and adapts its strategy in real-time. Unlike traditional random-based AI, this version analyzes the player's move history and adjusts its future choices accordingly, making the game more dynamic and challenging.

## Features
- **Adaptive AI**: The AI improves its choices based on the user's past moves.
- **Probability-based Decision Making**: AI selects moves based on observed player patterns.
- **Interactive Gameplay**: The user can play multiple rounds, and the AI evolves as the game progresses.
- **Score Tracking**: The program keeps track of the user's and AI’s scores.

## How It Works
1. **AI starts with a random move**: Since it has no prior data at the beginning.
2. **AI tracks user choices**: It keeps a count of how many times the user selects Rock, Paper, or Scissors.
3. **AI uses probability-based learning**: If the user frequently chooses "Rock," AI increases the likelihood of choosing "Paper" to counter it.
4. **Game continues**: AI adapts as more rounds are played.

## Installation & Running the Game
### Prerequisites
- Python 3.x installed on your system.

### Steps to Run
1. Clone the repository or download the `rock_paper_scissors.py` file.
2. Open a terminal or command prompt.
3. Navigate to the project folder.
4. Run the script using:
   ```sh
   python rock_paper_scissors.py
