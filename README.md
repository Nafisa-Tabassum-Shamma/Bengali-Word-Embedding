# Bengali Word Embedding

This repository contains the code, resources, and thesis for the Bengali Word Embedding project, which focuses on developing and evaluating word embedding models tailored for the Bengali language. This research contributes to natural language processing (NLP) for low-resource languages by providing robust models and detailed comparative analyses.

---

## Overview

Word embeddings are a key component in NLP, representing words in a continuous vector space to capture semantic relationships. This project focuses on:

- Developing Bengali word embeddings using **Gensim** and the **BanglaLM corpus**.
- Evaluating embeddings with **CNN** and **RNN** architectures.
- Comparing performance metrics against industry-standard models like **Facebook’s FastText**.

The project results, including the authored thesis, provide valuable insights into improving NLP applications for the Bengali language.

---

## Key Features

- **Thesis Book:** A detailed explanation of research, methodology, and findings, available in PDF format.
- **Custom Word Embeddings:** Trained using Gensim with BanglaLM corpus for robust linguistic representation.
- **Model Evaluation:** CNN and RNN models test embeddings for contextual accuracy and generalization.
- **Benchmarking:** Performance compared with FastText to highlight improvements and limitations.

---

## Project Structure

```plaintext
├── data/
│   ├── raw_data/         # Unprocessed datasets used for training
│   ├── processed_data/   # Preprocessed datasets ready for embedding models
├── models/
│   ├── gensim_model/     # Trained word embedding models
│   ├── cnn_rnn_models/   # Evaluation models using CNN and RNN
├── notebooks/
│   ├── training.ipynb    # Training scripts for word embeddings
│   ├── evaluation.ipynb  # Evaluation and benchmarking scripts
├── thesis/
│   ├── Bengali_Embedding_Thesis.pdf  # Full thesis document
├── README.md             # Project documentation
