# Neural Network Chatbot with NLTK

This is a simple chatbot project that utilizes a neural network and NLTK (Natural Language Toolkit) for natural language processing.

## Files

- **training.py**: Python script for training the chatbot model using the provided dataset (`intents.json`).
- **chatbot.py**: Python script for running the trained chatbot model to interact with users.
- **intents.json**: JSON file containing intents and their corresponding patterns and responses. This file serves as the dataset for training the chatbot.

## Usage

1. **Training the Model**: Run the following command to train the chatbot model using the provided dataset (`intents.json`). This script will generate a trained model file.

   ```bash
   python training.py
   ```
2.**Using the Chatbot**: After training the model, run the following command to start interacting with the chatbot.
   ```bash
   python chatbot.py 
  ```
# Requirements
- Python 3.x
- NLTK (Natural Language Toolkit)
- TensorFlow (for neural network model)
- Other dependencies as specified in requirements.txt
