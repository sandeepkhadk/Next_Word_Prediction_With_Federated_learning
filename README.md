# Next Word Prediction With Federated Learning

This repository demonstrates a **next-word prediction model trained using Federated Learning techniques**. The aim is to build a privacy-preserving language model that predicts the next word given a sequence of text, leveraging decentralized training across simulated clients.

Federated learning allows multiple clients to collaboratively train a model **without sharing raw data with a central server**, which is especially useful for sensitive text data such as typing input from users.

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `federated_flower_gru_optimized.ipynb` | Federated training workflow using **Flower** (a FL framework) with an optimized GRU-based model. |
| `fl_reddit_data_processing.ipynb` | Data preprocessing and dataset creation (e.g., Reddit or similar text corpus) for federated training. |
| `gru_next_word_prediction.ipynb` | Baseline **GRU next-word prediction model** (centralized) used before FL. |
| `gru_next_word_prediction_optimized.ipynb` | Enhanced GRU model with tuning and preprocessing improvements. |
| `.gitignore` | Standard Git ignore rules. |

---

## 🚀 Features

- Next-word prediction using a **GRU neural network**  
- Federated learning setup with **Flower** framework  
- Data preprocessing for language modeling  
- Notebook format for easy experimentation and visualization  

---

## 🧠 What Is Next-Word Prediction?

Next-word prediction is a common **Natural Language Processing (NLP)** task where a model estimates the most likely next word given a context of previous words. It’s widely used in keyboard autocomplete, text suggestions, and language modeling systems.

---

## 🧩 Federated Learning Overview

**Federated Learning (FL)** is a decentralized machine learning approach where multiple clients collaboratively train a shared global model without sending their raw training data to a central server. Each client trains on its local dataset and shares only model updates, improving privacy. 

This is useful in scenarios like mobile keyboard prediction where user text data should remain private.

---

## 🛠️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sandeepkhadk/Next_Word_Prediction_With_Federated_learning
cd Next_Word_Prediction_With_Federated_learning
