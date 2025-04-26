# Thai Summarizer (Formal Documents)

This project implements a formal Thai document summarization model from scratch.
It uses PyThaiNLP, FastAI, and custom Seq2Seq modeling.

## Features
- Strict formal language enforcement
- Custom Thai tokenizer
- LSTM-based Encoder-Decoder
- ROUGE evaluation metrics
- Designed for government/military style summarization


## Colab Notebook: Inference
[👉 Open the full training notebook here](https://colab.research.google.com/drive/1agNwO2T-ZZZmANmUUvJbfZuuJr-C7MoB?authuser=1)


## Requirements
- Python 3.8+
- fastai
- torch
- pythainlp
- rouge-score
- pandas
- numpy

## How to Train
1. Prepare your dataset (`formal_thai.csv`) with `text` and `summary` columns.
2. Run the notebook.
3. Evaluate using ROUGE metrics.


