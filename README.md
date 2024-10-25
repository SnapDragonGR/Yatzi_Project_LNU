# Swedish Yatzy Game (Python)

This is a Python-based text user interface (CUI) implementation of **Scandinavian Yatzy**. This project is created as a final project for the course "Introduction to Programming"

## Table of contents
- [About the game](#about-the-game)
- [Game rules](#game-rules)
- [Features](#features)
- [How to Run](#how-to-run)
- [Game Instructions](#game-instructions)
- [Error Handling](#error-handling)
- [Credits](#credits)

## About the game
Scandinavian Yatzy is a dice game where the player rolls five dice up to three times per turn, aiming to achieve certain combinations to score points. The game ends after each scoring category is filled, and the player’s score is tallied based on these combinations.

## Game rules
- Any number of players.

- Player rolls five dice. Get to choose which dice to keep, and which to reroll. (up to 2 times on a turn).

- Player must put a score or zero into a score box each turn. The game ends when all score boxes are used. The player with the highest total score wins the game.

**Possible combinations**:
  1. **Upper section**:
    - Ones: The sum of all dice showing the number 1.
    - Twos: The sum of all dice showing the number 2.
    - Threes: The sum of all dice showing the number 3.
    - Fours: The sum of all dice showing the number 4.
    - Fives: The sum of all dice showing the number 5.
    - Sixes: The sum of all dice showing the number 6.

  - 50 point award if a player scores at least 63 in the upper section.

  2. **Lower section**:
    - One Pair: Two dice showing the same number. Score: Sum of those two dice.
    - Two Pairs: Two different pairs of dice. Score: Sum of dice in those two pairs.
    - Three of a Kind: Three dice showing the same number. Score: Sum of those three dice.
    - Four of a Kind: Four dice with the same number. Score: Sum of those four dice.
    - Small Straight: The combination 1-2-3-4-5. Score: 15 points
    - Large straight: The combination 2-3-4-5-6. Score: 20 points
    - Full House: Any set of three combined with a different pair (e.g. 5-5-5 + 6-6) Score: Sum of all the dice.
    - Chance: Any combination of dice. Score: Sum of all the dice.
    - Yatzy: All five dice with the same number. Score: 50 points.

**Max score = 374**. - 5 on the _Ones_, 
                     - 10 on the _Twos_, 
                     - 15 on the _Threes_,
                     - 20 on the _Fours_, 
                     - 25 on the _Fives_, 
                     - 30 on the _Sixes_, 
                     - the 50 point bonus, 
                     - 12 on the _One Pair_, 
                     - 22 on the _Two Pairs_, 
                     - 18 on the _Three of a Kind_, 
                     - 24 on the _Four of a Kind_, 
                     - 15 on the _Small Straight_, 
                     - 20 on the _Large Straight_, 
                     - 28 on the _Full House_, 
                     - 30 on the _Chance_, 
                     - and 50 on the _Yatzy_)
## How to Run

## Game instructions
1. Start the game by rolling all five dice.
2. Choose which dice to keep and which to re-roll, up to two additional times per turn.
3. Select a scoring category for each turn; each category can be used only once.
4. Continue until all categories are filled, then view your final score.

## Error Handling
- Ensures valid inputs for dice selection and scoring choices.
- Displays an error message and re-prompts the player for valid inputs if any input is out of range or does not match expected values.

## Credits
- Developed by: Abhinav Mugudu (Abhinav5132), Gleb Razumnyi (SnapDragonGR)
- Course: Introduction to Programming
  
