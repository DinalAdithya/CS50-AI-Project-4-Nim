# Nim Game with AI

This project implements the classic game of Nim, where players take turns removing objects from heaps. The AI learns to play optimally using reinforcement learning, specifically Q-learning, to develop strategies over repeated games.

## Features

- **Q-Learning**: The AI agent uses reinforcement learning to improve its strategy through self-play.
- **Human vs AI**: Test your skills against the trained AI agent.
- **Customizable Gameplay**: Configure the initial heap sizes and number of heaps.

## How It Works

1. **Game Rules**:
   - Nim starts with a set of heaps containing objects.
   - Players take turns removing any number of objects from a single heap.
   - The player forced to take the last object loses.

2. **AI Training**:
   - The AI plays multiple games against itself.
   - It uses Q-learning to update its Q-values based on the outcomes of its actions.
   - Over time, the AI learns the optimal moves for different game states.

3. **Play Against the AI**:
   - Once trained, the AI can play against a human or another AI.

## Project Files

- `nim.py`: Contains the implementation of the Nim game and AI.
- `play.py`: Allows humans to play against the trained AI or observe AI vs AI games.
- `README.md`: Documentation for the project.

