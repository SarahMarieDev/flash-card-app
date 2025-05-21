# Flash Card App

A simple flashcard app built with Python and Tkinter to help users learn new vocabulary or terms in any subject. The app displays a term on the front of a flashcard and reveals the definition or translation on the back after a short delay. Users can mark terms they know, and the app will remove them from the study set.

## Features

- Interactive flashcard interface with automatic flipping.
- Tracks and removes known terms from the study pool.
- Saves user progress locally using CSV files.
- Customizable for any two-column dataset (e.g., Language A → Language B, Term → Definition, etc.).

## Requirements

- Python 3
- Libraries:
  - `tkinter`
  - `pandas`

## Setup

1. Clone or download the repository.
2. Ensure the following files and folders are in place:
   - A CSV file at `data/initial_words.csv` or `data/words_to_learn.csv`, with two columns (e.g., `Term`, `Definition`).
   - UI images in the `images/` directory:
     - `card_front.png`
     - `card_back.png`
     - `right.png`
     - `wrong.png`
3. Install dependencies:

   ```bash
   pip install pandas
