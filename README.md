# Sentiment Classification of Goodreads Book Reviews using ANNs
> Student project exploring natural language processing and neural networks with PyTorch.

A PyTorch implementation of a sentiment classifier trained on Goodreads 
book reviews, predicting whether a review is positive, neutral, or negative.

## Overview

This project builds a feedforward neural network from scratch to classify book 
reviews by sentiment. The model is trained on Goodreads reviews from Kaggle, 
using a bag of words approach with word embeddings.

## Results

| Metric | Score |
|---|---|
| Test Accuracy | 65% |
| Classes | Positive, Neutral, Negative |
| Training samples | 38,427 |
| Test samples | 9,607 |


## Installation

```bash
pip install torch pandas scikit-learn
```

## Dataset

Download the Goodreads reviews dataset from Kaggle:
- Dataset: `goodreads_reviews_dedup.json`
- Place it in a `/data` folder at the root of the project

## Usage

Run the notebook cells in order:
1. Load and clean data
2. Tokenize and build vocabulary
3. Encode reviews
4. Train model
5. Evaluate and test predictions

## Limitations

- Bag of words cannot capture word order or context
- Struggles with irony, sarcasm and mixed sentiment reviews
- Class imbalance between positive, neutral and negative reviews

## Future Work

- Implement a transformer-based model (BERT) for better context understanding
- Train on a larger, more balanced dataset
- Add a simple web interface for live predictions

## Tech Stack

- Python
- PyTorch
- pandas
- scikit-learn

## Author
**Dimirina Ivanova**
[LinkedIn](linkedin.com/in/dimitrina-ivanova-) · ivanovav.dimitrina@gmail.com
