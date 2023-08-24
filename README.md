# Typing Assistant 

The primary goal of the Typing Assistant is to demonstrate how language models can be used to predict the next words in a sentence, providing users with potential word choices as they type. This can be particularly useful for enhancing typing speed and accuracy, and it showcases the basic principles of natural language processing.

Features
--------

-   Predictive Text: The application uses bigram and trigram frequency distributions to predict the next words based on user input.
-   Simple Interface: The web interface allows users to input text and receive word predictions in real-time.
-   Custom Corpus: The application combines words from the Brown corpus and a custom corpus named 'my_corpus.txt' to build its language models.
-   Incomplete Word Prediction: The tool can also predict potential next words for incomplete input, helping users when they're unsure about the next word.

How It Works
------------

1.  The application uses the Flask web framework to create a user interface.
2.  It computes bigram and trigram frequency distributions from a provided corpus.
3.  When users enter text, the application offers predictive suggestions based on the language models.
4.  Predictions are based on the last word or words provided by the user.
5.  The user can choose from suggested words to complete their sentences.

Usage
-----

1.  Enter text in the input field to see predictive suggestions.
2.  Choose a suggestion to complete your sentence or to get ideas for the next word.
