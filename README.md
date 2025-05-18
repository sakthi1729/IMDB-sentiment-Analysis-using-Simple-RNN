# IMDB-sentiment-Analysis-using-Simple-RNN

This repository contains a Streamlit web application for sentiment analysis on movie reviews using a pre-trained SimpleRNN model trained on the IMDb dataset. The app classifies user-input movie reviews as **Positive** or **Negative** based on the text content.

---

## Features

- Load a pre-trained Keras SimpleRNN model for sentiment classification.
- Preprocess raw text reviews into padded sequences suitable for the model.
- Interactive Streamlit interface for easy user input and real-time predictions.
- Display sentiment label along with prediction confidence score.

---

## Repository Structure

- `simple_rnn_imdb.h5`: Pre-trained SimpleRNN Keras model file.
- `main.py`: Streamlit application script for loading the model and making predictions.
- `README.md`: Project documentation.

---

## Requirements

- Python 3.7+
- TensorFlow 2.x
- Streamlit

Install dependencies via pip:

```bash
pip install -r requirements.txt

```


