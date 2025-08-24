# Slot Machine Game (Python)

A simple command-line slot machine game written in Python. Users can deposit money, choose the number of lines to bet on, place bets, and spin the slot machine to try their luck!

## Features

- Deposit money to play
- Choose number of lines to bet (up to 3)
- Set your bet per line (between Rs1 and Rs100)
- Random slot machine spin with symbols A, B, C, D
- Win based on matching symbols per line
- Displays winnings and current balance

## How to Run

1. **Clone or Download the Repository**

2. **(Optional) Create and Activate a Virtual Environment**
   ```sh
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Run the Game**
   ```sh
   python main.py
   ```

## Game Rules

- You can bet on 1 to 3 lines.
- Each line costs your chosen bet amount.
- If all symbols in a line match, you win according to the symbol's value.
- Your balance updates after each spin.

## Example Gameplay

```
what would you like to deposit? Rs100
enter the number of lines to bet on (1-3)?2
what would you like to bet on each line?Rs10
You are betting Rs10 on 2 lines. Total bet is equal to: Rs20
A | B | C
B | D | A
C | B | D
you won 0.
you won on lines
your current balance is80
```

## Requirements

- Python 3.x
