# Japanese Flashcards App

Welcome to the Japanese Flashcards App repository! This application is an educational tool aimed at helping users learn Japanese by practicing with flashcards that show Japanese words, their English translations, and Romaji (the Romanization of Japanese words). Built with Python and Tkinter for the graphical user interface (GUI), along with Pandas for data handling, it offers a user-friendly and effective way to enhance your language skills. The application features a curated set of 100 words, providing a focused and manageable approach to beginning or supplementing your Japanese language journey.

## Features

- **Interactive Flashcards**: Learn Japanese words along with their English translations and Romaji.
- **Spaced Repetition**: Focus on words you're less familiar with by removing known words from the rotation.
- **Random Selection**: Words are chosen at random to test your memory and enhance learning.
- **Automatic Flip**: Each card automatically flips after 4 seconds to reveal the English translation, encouraging quick recall.
- **Progress Tracking**: Your progress is saved, so you only learn the words you don't know yet.

## How to Use

The Japanese Flashcards App is designed to be intuitive and easy to use. Here’s how to get started:

1. **Start the App**: After installation, run the app by executing `main.py` in your terminal or command prompt.
2. **Learning Mode**: Upon starting, the app presents you with a flashcard showing a word in Japanese. Try to recall its English translation and Romaji (Romanization).
3. **Reveal the Answer**: Wait for 4 seconds, or click the ❌ button if you're ready to see the answer sooner. The card will flip, revealing the English translation and Romaji.
4. **Rate Your Knowledge**: 
   - If you knew the word, click the ✅ button. This word will be removed from your study list.
   - If you didn't know the word, click the ❌ button to keep it in the rotation for more practice.
5. **Progress**: The app tracks the words you know and focuses on those you need to practice, tailoring your learning experience.

For more detailed usage instructions and customization options, please see the sections below.


## Installation

To run this application, you'll need Python installed on your computer. If you don't have Python installed, download and install it from [python.org](https://www.python.org/).

Clone this repository to your local machine:

```bash
git clone https://github.com/singhkailash9/jp-flashcard-py.git
cd jp-flashcard-py
```

Install the required dependencies:
```bash
pip install pandas
```

## Data Files
- `flashcards.csv`: A default list of Japanese words with their English translations and Romaji.
- `words_to_learn.csv`: Dynamically generated based on your learning progress. If this file exists, the app will use it instead of `flashcards.csv` to continue from where you left off.


## Customization

You can add more words to the flashcards.csv file to expand your learning. Ensure the format is consistent:

Japanese,Romaji,English

日本語,Nihongo,Japanese

## Contributing

Contributions to the Japanese Flashcards App are welcome! Feel free to fork the repository, make improvements, and submit pull requests.


## Acknowledgments

- Inspired by the Complete Python Pro Bootcamp by Dr. Angela Yu.
