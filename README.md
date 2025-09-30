# 💣 Minesweeper AI 💣 

This project implements an AI agent capable of playing the classic game of Minesweeper. The agent uses propositional logic to make inferences about the game state, identifying safe cells and known mines based on the information it gathers.

This project was developed as part of Harvard's CS50's Introduction to Artificial Intelligence with Python course.

## Demo

The AI intelligently identifies safe moves and flags known mines. When no safe move can be guaranteed, it makes a calculated random choice.

![Minesweeper AI in Action](minesweeperCS50.gif)

## Concepts & Technologies

- **Python**
- **Pygame** for the graphical user interface.
- **Artificial Intelligence** based on a knowledge base.
- **Propositional Logic** and **Inference Algorithms** to deduce safe moves and mines.

## How to Run

1.  **Clone the repository.**
2.  **Navigate to the project directory.**
3.  **(Optional)** Create and activate a virtual environment.
4.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
5.  **Run the game:**
    ```bash
    python runner.py
    ```

## Project Structure

- **`minesweeper.py`**: Contains all the core logic for the AI agent (`MinesweeperAI` class) and the representation of logical sentences (`Sentence` class).
- **`runner.py`**: The graphical interface provided by the course, which uses Pygame to run and visualize the game.

---

This project was developed as part of Harvard's CS50's Introduction to Artificial Intelligence with Python course. The core AI logic was implemented by me, while the graphical user interface (`runner.py`) and other utility files (`logic.py`, `util.py`) were provided by the course.
*AI developed by VeetGT.*
