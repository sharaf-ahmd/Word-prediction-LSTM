# Next Word Prediction Using LSTM

An interactive web application that predicts the next word in a sentence using a Long Short-Term Memory (LSTM) model built with TensorFlow/Keras. This project demonstrates the application of deep learning in natural language processing (NLP) for real-time text prediction.

## 🚀 Live Demo

Experience the application here: [Word Prediction with LSTM](https://word-prediction-lstm-h8nht7tgiwjgptld5gd62s.streamlit.app/)

## 🧠 Model Overview

The model is trained on a dataset of text sequences, learning to predict the next word based on the preceding context. It utilizes an LSTM architecture to capture long-term dependencies in the text.

## 🛠️ Technologies Used

- **Backend**: Python, TensorFlow/Keras
- **Frontend**: Streamlit
- **Data Processing**: NumPy, Pickle
- **Text Preprocessing**: Keras Tokenizer, Padding Sequences

## 📁 Project Structure

- `model.h5`: Trained LSTM model.
- `tokenizer.pickle`: Tokenizer for text preprocessing.
- `app.py`: Streamlit application script.
- `requirements.txt`: Python dependencies.

## ⚙️ Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/next-word-prediction-lstm.git
   cd next-word-prediction-lstm
