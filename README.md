# Chatbot Psychological Support model

This project helps former prisoners receive psychological support through an AI-powered chatbot using NLP and deep learning.

##  Objectives

- Load and clean Arabic conversational data
- Remove punctuation, numbers, diacritics, and stop words
- Tokenize text and build a vocabulary
- Convert text to sequences and pad them to fixed length
- Encode emotion labels
- Train a classification model to predict emotions
- Decode ..

## Preprocessing Steps

1. Remove punctuation, numbers, dates, and diacritics (tashkeel)
2. Normalize text and remove common Arabic stop words (via NLTK)
3. Tokenize the text and build word-to-index mappings
4. Convert sentences to numerical sequences and apply padding
5. One-hot encode emotion labels


## Model Used

A simple deep learning model using Keras with the following architecture:

- Embedding Layer (for word representation)
- Bidirectional LSTM Layer (captures context from both directions)
- Dropout Layer (to reduce overfitting)
- Dense Layer with Softmax activation (for multi-class classification)

This model is trained on a cleaned Arabic empathetic conversations dataset.

---

## Output

- The model predicts emotional classes for Arabic responses
- Evaluation includes accuracy score and classification report on test set

---

##  Technologies Used
- Python
- Transformers
- scikit-learn
- pandas / numpy
- Arabic NLP preprocessing tools

---


##  Repository Structure
- Project documentation (PDF)
- pretrained models/ — pre-trained expirements (from Hugging Face)
- From Scratch / — NLP from Scratch expirements (.ipynb)
---

##  Authors

- Hamza Alaedi
- Eyad bargouth 


