# U.S. States Game 🗺️

This is a fun Python game where the goal is to guess all 50 U.S. states! The game uses Python's `turtle` module to display a map of the United States and allows users to input state names. Any states you don't guess will be saved to a file called `states_to_learn.csv` for future practice.

---

## How It Works 🎮

1. The program displays a blank map of the United States.
2. The user types in the name of a state in the input box.
3. If the state name is correct:
   - The state's name appears on the map at its correct location.
   - The guessed state is added to the list of correct guesses.
4. If the user types **"Exit"**, the game ends, and a file named `states_to_learn.csv` is created. This file contains the names of states that were not guessed during the session.

---

## Features ✨

- **Interactive Map:** Uses the `turtle` module to display the U.S. map.
- **Dynamic Input:** User-friendly text input for guessing state names.
- **Progress Tracking:** Displays the number of correctly guessed states in real time.
- **Missed States File:** Generates a `states_to_learn.csv` file for missed states.

---

## Setup ⚙️

1. **Install Dependencies**:
   Make sure you have Python installed and the following modules:

   - `turtle` (comes pre-installed with Python)
   - `pandas` (install using `pip install pandas`)

2. **Prepare the Data**:
   Ensure the following files are in the same directory as your script:
   - `50_states.csv`: A CSV file containing the names of the states along with their x and y coordinates for map placement.
   - `blank_states_img.gif`: An image file of a blank U.S. map.

---

## How to Run 🚀

1. Open a terminal or command prompt.
2. Navigate to the folder containing the script and necessary files.
3. Run the script using:
   ```bash
   python main.py
   ```
