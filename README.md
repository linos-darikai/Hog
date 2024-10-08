# 🎲 Hog Game Simulator

## 🐷 About the Project

Welcome to the Hog Game Simulator! This project implements a digital version of Hog, an exciting dice game with a twist. Originally developed at UC Berkeley, this implementation challenges you to create strategies and outsmart your opponent!

## 🎯 Game Rules

- 🏁 Goal: Be the first to reach 100 points
- 🎲 Roll up to 10 dice per turn
- 🐽 Pig Out: Roll a 1, score only 1 point for the turn
- 🥓 Free Bacon: Roll 0 dice, score 1 + max digit of opponent's score
- �wild Hog Wild: If total scores are a multiple of 7, use 4-sided dice
- 🔄 Swine Swap: If your score is exactly double your opponent's, swap scores!

## 🚀 Features

- 💻 Complete game simulator
- 🤖 Implement and test various AI strategies
- 🖥️ Interactive GUI for playing against AI or another human
- 🧪 Extensive test suite for verifying your implementation

## 🛠️ Getting Started

1. Clone this repository
2. Ensure you have Python 3.x installed
3. Install required dependencies (if any)
4. Run `python3 hog_gui.py` to start the graphical interface

## 📚 Project Structure

- `hog.py`: Main game logic (implement your solutions here)
- `dice.py`: Dice rolling functions
- `hog_gui.py`: Graphical user interface
- `hog_grader.py`: Autograder for testing your implementation

## 🧠 Challenges

1. Implement core game mechanics
2. Develop winning strategies
3. Beat the baseline strategy with a win rate > 0.59

## 🏆 Acknowledgments

Based on the Hog project from UC Berkeley's CS61A course. Special thanks to John DeNero and the CS61A staff.

## 🤝 Contributing

This is an educational project, but suggestions and improvements are welcome! Feel free to fork and submit pull requests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

Happy coding and may the odds be ever in your favor! 🍀
