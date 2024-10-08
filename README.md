# Part-of-Speech Tagging using Hidden Markov Models

## Project Overview

This project demonstrates the Pomegranate library's proficiency in building a Hidden Markov Model for part-of-speech tagging with a tagset.

## Understanding Hidden Markov Models and the Viterbi Algorithm

This project showcases the use of the Viterbi algorithm, one of the plenty applications of statistics in computing. For Hidden Markov Models (HMMs), the Viterbi algorithm is used to determine the most likely sequence of parts of speech (hidden states) given the preceeding observed words. It is one of the most basic forms of part-of-speech tagging in Natural Language Processing.

## Major Files in the Repository

- `HMM_warmup.ipynb`: Test notebook for practicing both the forward and Viterbi methods, among other things.
- `HMM_Tagger.ipynb`: Notebook using `base-hmm-tagger`, emission and transition probabilities to make next part-of-speech predictions using the Viterbi algorithm.
- `helpers.py`: Script file for additional functions and classes.

## How to Use

1. Clone this repository
2. Ensure you have all the required libraries and modules installed
3. Follow the steps in the `HMM_warmup.ipynb` notebook in your preferred environment for a base understanding
4. Implement the `n-gram models` and `base-hmm-tagger` in the `HMM_Tagger.ipynb`
5. Run the cells to reproduce the analysis

## Further Reading

For a more comprehensive explanation, refer to this [post](https://medium.com/towards-data-science/hidden-markov-models-explained-with-a-real-life-example-and-python-code-2df2a7956d65).

## Licensing

Copyright (c) 2024, Ayo

This project is for personal and educational purposes only. All rights reserved.
