# SMS Spam Detection using LSTM

A simple deep learning project to classify SMS messages as spam or ham using LSTM neural networks.

## Project Description

This project uses a Recurrent Neural Network with LSTM layers to detect spam messages in SMS texts. The model processes text sequences and learns patterns that distinguish spam from legitimate messages.

## Dataset

- **Source**: SMS Spam Collection Dataset from Kaggle
- **Size**: 5,574 messages
- **Classes**: 
  - Ham (legitimate): 4,825 messages (86.6%)
  - Spam: 749 messages (13.4%)

## Model Architecture

```
Input → Embedding → LSTM → Dense → Output
```

- **Embedding Layer**: Converts words to vectors
- **LSTM Layer**: Processes sequences and captures context
- **Dense Layer**: Final classification

## Requirements


pip install tensorflow pandas numpy matplotlib seaborn scikit-learn


## Usage

1. Place `spam.csv` in your project directory
2. Run the code to:
   - Load and explore the data
   - Preprocess text messages
   - Train the LSTM model
   - Evaluate performance
   - Make predictions on new messages

## Results

Typical performance metrics:
- **Accuracy**: 98%+
- **Precision**: 97%+
- **Recall**: 94%+

## Features

- Text preprocessing and tokenization
- LSTM model for sequence classification
- Performance visualization
- Real-time message prediction

## Example Prediction


message = "Congratulations! You won a $1000 prize!"
prediction = predict_message(message)  # Returns "SPAM" or "HAM"


This project demonstrates how deep learning can effectively solve text classification problems like spam detection.
