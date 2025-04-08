# Sentiment Analysis on Movie Reviews 🎬🧠

This project is a basic example of binary text classification using deep learning. The goal is to determine whether a movie review is **positive** or **negative** based on its text content.

## 🚀 What I Did

- Preprocessed text data using `Tokenizer` and `pad_sequences`.
- Built a sequential neural network using:
  - `Embedding` layer to transform text into vector representations.
  - `SpatialDropout1D` to prevent overfitting.
  - `LSTM` layer to capture sequential patterns in text.
  - `Dense` layer with `sigmoid` for binary classification.
- Trained and evaluated the model using real review data.
- Created a prediction function to classify new reviews in real time.

## 🧠 What I Learned

- How to build a text classification pipeline from raw data to predictions.
- Importance of sequence padding and embeddings in NLP.
- How LSTM works and why it's powerful for sequence tasks.
- How to structure, compile, train, and evaluate a Keras model.
- Practical use of dropout layers to improve generalization.

## 🔍 Example
```python
new_review = "This movie was fantastic. I love it."
predict_sentiment(new_review)
# Output: "Positive"

📁 Tech Stack
Python

TensorFlow / Keras

NLP preprocessing
```python
new_review = "This movie was fantastic. I love it."
predict_sentiment(new_review)
# Output: "Positive"

📢 Author
Mikel Cerio Chinchurreta — LinkedIn
