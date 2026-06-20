# 🎰 Python Slot Machine

A text-based slot machine game built using Python. Players can deposit money, place bets on multiple lines, spin the slot machine, and win rewards based on matching symbols.

## Features

* Deposit money before playing
* Choose up to 3 betting lines
* Place bets on each line
* Random slot machine spins
* Winning calculation based on matching symbols
* Balance tracking across multiple rounds
* Input validation for user inputs
* Play until you quit or run out of balance

## Technologies Used

* Python 3
* Built-in `random` module

## Project Structure

```text
slot-machine-python/
│
├── main.py
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Anurag10-git-hub/slot-machine-python.git
```

2. Move into the project directory:

```bash
cd slot-machine-python
```

3. Run the program:

```bash
python main.py
```

## Example Gameplay

```text
what would you like to deposit ? $100

Current balance is $100

Press Enter to spin (q to quit):

How much would you like to bet on each line ? $10
Enter the number of lines to bet on (1-3) ? 2

you are betting $10 on line 2. Total bet is = $20

A | A | A
D | C | D
C | B | C

you won $50
you won on lines 1
```

## Symbol Values

| Symbol | Value |
| ------ | ----- |
| A      | 5x    |
| B      | 4x    |
| C      | 3x    |
| D      | 2x    |

## Learning Outcomes

This project helped practice:

* Functions
* Loops
* Lists and Dictionaries
* Input Validation
* Random Number Generation
* Game Logic
* Python Project Structure
* Git and GitHub

## Future Improvements

* Save balance using JSON
* Add statistics and win rate tracking
* Add colored terminal output
* Convert to Object-Oriented Programming (OOP)
* Add unit tests with pytest

## Author

**Anurag Kanojiya**

Computer Engineering Student | Python Developer
