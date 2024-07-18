# Set Card Game - User Guide

## Overview
Welcome to the Set card game! This guide will help you understand the game rules, how to play, and how to navigate the user interface.

## Table of Contents
- [Game Objective](#game-objective)
- [Game Setup](#game-setup)
- [Game Rules](#game-rules)
- [How to Play](#how-to-play)
- [User Interface](#user-interface)
- [Building and Running the Game](#building-and-running-the-game)
- [Troubleshooting](#troubleshooting)

### Building the Project
-install the project into your computer
- Open a terminal and navigate to the SET_CARD_Game1\out\artifacts\Set_Card_Game_jar directory
- use java -jar Set_Card_Game.jar and here you go

## Game Objective
The objective of the Set card game is to identify sets of three cards where each feature is either all the same or all different. The features include:
- Color
- Number
- Shape
- Shading

## Game Setup
- The game consists of 81 unique cards.
- Each card has four features, with each feature having three possible values.

## Game Rules
- A set consists of three cards where for each feature (color, number, shape, shading), the values are either all the same or all different.
- Players place tokens on cards to indicate their chosen set.
- The dealer checks if the sets are valid and updates the game state accordingly.

## How to Play
1. **Starting the Game:**
   - The game begins with 12 cards dealt face-up on the table.
   
2. **Finding Sets:**
   - Look for sets of three cards that satisfy the set condition.
   - Each player has a token to place on the cards they believe form a set.
   
3. **Placing Tokens:**
   - Click on the cards you want to select as a set.
   - Confirm your selection by placing your token on the third card.
   
4. **Validation:**
   - The dealer validates the set.
   - If the set is valid, the cards are removed and replaced with new ones from the deck.
   - If invalid, the tokens are removed and play continues.

5. **Winning the Game:**
   - The game continues until the deck is exhausted or no more sets are available.
   - The player with the most valid sets wins the game.

## User Interface
### Main Screen
- **Table:** Displays the cards currently in play.
- **Player Area:** Shows the players and their scores.
- **Control Buttons:**
  - **Start:** Begin a new game.
  - **Stop:** End the current game.
  - **Shuffle:** Shuffle the cards on the table.

### Selecting Cards
- Each key corresponds to a specific card position on the game board.
- Player A uses the keys in the left section of the keyboard, while Player B uses the keys in the right section.
  
### Example:
- **Player A**:
  - Pressing `Q` will select the top-left card.
  - Pressing `W` will select the card to the right of `Q`, and so on.
  
- **Player B**:
  - Pressing `U` will select the top-left card in their section.
  - Pressing `I` will select the card to the right of `U`, and so on.

### Game Status
- **Messages:**
  - The game will display messages indicating valid or invalid sets.
  - Score updates will be shown in real-time.
  
- **Timers:**
  - The game may include timers to add a challenge.

## Building and Running the Game
### Prerequisites
- Ensure you have Java and Maven installed on your system.

  
## Troubleshooting
- **Game not starting:**
  - Ensure Java and Maven are correctly installed.
  - Check for any compilation errors and resolve them.
  
- **UI issues:**
  - Ensure your system meets the graphical requirements.
  - Update your Java installation if necessary.

- **Performance problems:**
  - Close other applications to free up system resources.
  - Increase the heap size if running out of memory.

Enjoy playing the Set card game!
