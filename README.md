# Flashcard-Generator

Has two files, each of which has a constructor for a different kind of flash card. One is for basic cards, which ask a question and have an answer. The other is for cloze cards, which have a statement with something omitted, which is the answer. 

Basic cards are constructed by passing in the question and answer as strings.

Cloze cards are constructed by passing in the full statement and the wording to be removed. If the wording is not contained in the statement, it will display an error. 
