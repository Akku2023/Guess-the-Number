# 🎯 Number Guessing Game

A simple **Number Guessing Game built using Python** in which the computer randomly selects a number between 1 and 100, and the player tries to guess it.

After each guess, the program provides a hint to help the player find the correct number. Once the player guesses correctly, the game displays the secret number and the number of attempts taken.

## 📌 About the Project

This project is designed for beginners who want to practice Python programming concepts such as loops, conditional statements, user input, and random number generation.

## 🚀 Features

- Generates a random number between 1 and 100.
- Accepts guesses from the user.
- Provides hints to guess higher or lower.
- Continues until the correct number is guessed.
- Displays the total number of attempts.

## 🛠️ Technologies Used

- **Python 3**
- `random` module for generating a random number.

## 📂 Project Structure

```text
number-guessing-game/
│
├── main.py
└── README.md
```

- `main.py` — Contains the source code for the number guessing game.
- `README.md` — Contains the project description and instructions.

## ▶️ How to Run

### 1. Install Python

Make sure Python 3 is installed on your computer.

Check your Python version:

```bash
python --version
```

### 2. Clone the Repository

```bash
git clone <your-repository-url>
```

### 3. Navigate to the Project Directory

```bash
cd number-guessing-game
```

### 4. Run the Game

```bash
python main.py
```

Depending on your system, you may need to use:

```bash
python3 main.py
```

## 🎮 How to Play

1. Run the Python program.
2. Enter a number between 1 and 100 when prompted.
3. Follow the hints displayed by the program:
   - **Lower number please** — Your guess is too high.
   - **Higher number please** — Your guess is too low.
4. Continue guessing until you find the correct number.
5. View the final message showing the number of attempts.

## 💻 Example Output

```text
Guess the number: 50
Higher number please
Guess the number: 75
Lower number please
Guess the number: 60
Higher number please
Guess the number: 65
You have guessed the number 65 correctly in 5 attempts
```

*Note: This is an illustrative example. The secret number and hints will vary each time you play.*

## 🧠 Concepts Practiced

- **Random Number Generation:** Using `random.randint(1, 100)` to generate the secret number.
- **While Loop:** Repeating the game until the correct number is guessed.
- **Conditional Statements:** Comparing the guess with the secret number.
- **User Input:** Accepting guesses using `input()`.
- **Variables and Counters:** Tracking guesses and attempts.

## 🔮 Possible Improvements

- Validate input to handle non-numeric values.
- Prevent guesses outside the range of 1 to 100.
- Fix the attempt counter so it increments exactly once per guess.
- Add difficulty levels, such as easy, medium, and hard.
- Display a congratulatory message when the player wins.
- Add a replay option to start a new game.

## 👨‍💻 Author

Created as a beginner-friendly Python project to practice fundamental programming concepts.

## 📄 License

This project is intended for learning and personal use. Add a license file if you want to distribute it under a specific open-source license.
