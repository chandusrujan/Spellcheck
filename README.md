
# Telugu Spell Checker

## Description
This project aims to develop a comprehensive spell-checking tool for the Telugu language. Recognizing the scarcity of reliable spell-checking resources for Telugu, our goal is to enhance written communication and standardize spelling across digital platforms. The repository includes a Python spell-check script (Spell check.py) and a detailed project documentation (Spellcheck Documentation.docx), covering software requirements, system design, and testing methodologies.

## Setup and Installation
1. Ensure you have Python installed on your system. This script was developed with Python 3.
2. Clone or download this repository to your local machine.

## Usage
To use this script, follow the steps below:
1. Run the Spell check.py script to check the spelling of Telugu words.
2. Refer to the oose-gcp.docx document for detailed information on project specifications, designs, and implementation.

## How it Works
Dictionary Creation:
The script creates dictionaries and sets to store characters and words from the Indian corpus (Telugu language).

Spell Check Function:
- The spellcheck function takes a query word as input.
- It identifies characters in the word and compares them with characters in the dictionary.
- Based on character matches, it suggests possible correct words by calculating edit distances.

User Input:
- Users input a word they suspect is misspelled.

Output:
- The script provides suggestions for correct spellings based on edit distances.

## Code Structure
- spellcheck: The main function responsible for spell checking.
- query: Takes user input for the word to be checked.
- dic, dic1, dic4: Dictionaries used for storing characters, word frequencies, and edit distances.
- lit: List containing unique words from the Telugu corpus.
- s, s1: Sets to store unique characters.

## Features
- Spell checking for Telugu language text.

