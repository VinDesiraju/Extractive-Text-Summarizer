# Extractive Text Summarization with NLTK

## Overview

This Python script utilizes the Natural Language Toolkit (NLTK) library to perform extractive text summarization. Extractive summarization involves selecting key sentences from a text to create a concise summary. The algorithm here weighs words based on their frequency in the main text relative to their frequency in both text and title, while also considering the presence of title words in each sentence.
Rogue and BLEU scores are calculated for the model.

## Requirements

- Python 3.x
- NLTK library (`nltk`)
- Google Colab (for the provided Google Drive integration)

## Execution
Upload the ipynb file and text file to Google Colab and run all cells.

## Example
An example usage is provided in the script for summarizing the "gift-of-magi.txt" story.

## Acknowledgments
The NLTK library: https://www.nltk.org/
Google Colab: https://colab.research.google.com/
