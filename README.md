# Frequency Analysis of English and Russian Texts

Hi! This is a small project where I analyzed two short texts — one in English and one in Russian — and looked at the most frequent words in each. I used Python and a few libraries we learned to work with, like NLTK, spaCy, pymorphy2, matplotlib, and wordcloud.
I didn’t use anything complicated — no machine learning or advanced NLP models — just basic tools for working with texts.

## Why I Did This Project
I wanted to better understand how to work with texts in Python and practice simple frequency analysis. It was also interesting to compare English and Russian — how often certain words appear, and what kinds of words are common.
This project was more about applying what I’ve learned and getting comfortable working with real text data.

## Basic steps

- Downloaded texts from Project Gutenberg — I picked a short English poem and a Russian poem.

- Cleaned the texts: I removed punctuation, made everything lowercase, and split the text into words.

- For English, I used NLTK for tokenization.

- For Russian, I used spaCy and pymorphy2 for lemmatization (to get the base form of each word).

- Then I used Counter from Python’s collections to count how often each word appeared.
- 
- After that, I selected the top 10 most frequent words and then created bar charts to visualize these words.

And finally, I generated word clouds - just for fun and to make the results more visual.

I also saved the word cloud images as .png files.


## Tools and Libraries used:

- Python (Jupyter Notebook)
- NLTK
- spaCy
- pymorphy2
- matplotlib
- wordcloud

## What’s in This Repo

### frequency_analysis_project.ipynb – the notebook with all the code
### english_wordcloud.png – word cloud image for English
### russian_wordcloud.png – word cloud image for Russian


