# Octodle

Octodle is a terminal-based word-guessing game inspired by Wordle, but with an eight-letter challenge. Test your vocabulary and deduction skills as you try to guess the daily word within six attempts.

## About the Game

Octodle presents players with a new eight-letter word challenge every day. You have six attempts to guess the correct word, with feedback provided after each guess to help narrow down the possibilities.

## Features

- **Daily Word Challenge**: A new eight-letter word is selected each day based on the date
- **Intelligent Feedback**: After each guess, you'll see:
  - Letters placed in their correct positions
  - A list of all correct letters that appear in the target word
- **Word Validation**: Only valid eight-letter words are accepted as guesses
- **Simple Terminal Interface**: Clean, easy-to-use command-line gameplay

## How to Play

1. Run the game in your terminal
2. Enter your eight-letter guess
3. Receive feedback on your guess:
   - Correctly positioned letters will appear in the displayed word
   - All correct letters (regardless of position) will be listed below
4. Use the feedback to refine your next guess
5. Try to guess the word within six attempts!

## Setup Instructions

### Prerequisites
- Python 3.x

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/username/octodle.git
   cd octodle
   ```

2. Make sure you have the required files:
   - `Octodle.py` (Main game file)
   - `wordList.txt` (Contains 365 possible daily answers)
   - `allWords.txt` (Contains all valid guessing words)

### Running the Game

```
python Octodle.py
```

## Game Rules

- Each guess must be a valid eight-letter word
- After each guess, you'll see which letters are in the correct position
- You'll also see a list of all the correct letters that appear in the word
- You have six attempts to guess the word
- A new word is selected each day

## Example Gameplay

```
Welcome To Octodle!:
The 8-letter, Wordle Rip-Off Game
What is your guess? trustees
The correct letters are: e, r, t
1: t_____e_
2: ________
3: ________
4: ________
5: ________
6: ________
What is your guess? throttle
The correct letters are: e, h, r, t
1: t_____e_
2: thr__t__
3: ________
4: ________
5: ________
6: ________
What is your guess? threaten
The correct letters are: a, e, h, n, r, t
1: t_____e_
2: thr__t__
3: threaten
4: ________
5: ________
6: ________
You Win!
The Word Was "threaten
It Took You 3 Guesses!"
```

## Files Explanation

- **Octodle.py**: Main game logic including word validation, board display, and game flow
- **wordList.txt**: Contains 365 words that serve as possible answers (one for each day of the year)
- **allWords.txt**: Contains all valid eight-letter words that can be used as guesses

## Acknowledgments

- Inspired by the popular word game Wordle