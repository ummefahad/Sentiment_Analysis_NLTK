# Sentiment Analysis with NLTK

This project demonstrates how to perform sentiment analysis on text data using NLTK (Natural Language Toolkit) in Python. It utilizes the VADER (Valence Aware Dictionary and sEntiment Reasoner) lexicon for sentiment analysis, along with other NLTK functionalities like tokenization, stemming, and lemmatization.

## Requirements
- Python 3.x
- NLTK (Natural Language Toolkit)
- pandas

## Setup
1. Install Python (if not already installed): https://www.python.org/downloads/
2. Install NLTK: `pip install nltk`
3. Install pandas: `pip install pandas`
4. Download NLTK data: Run Python and execute the following commands:
   ```python
   import nltk
   nltk.download('vader_lexicon')
   nltk.download('punkt')
   nltk.download('wordnet')
