# 🧠 One-Hot Encoding Example in Python

This simple educational script demonstrates how **one-hot encoding** works using Python and the `pandas` library. It’s a basic, beginner-friendly introduction to one of the fundamental techniques in Natural Language Processing (NLP).

---

## 📌 What is One-Hot Encoding?

One-hot encoding is a method for representing categorical data as binary vectors. In NLP, it's used to convert words into numerical format so that machine learning algorithms can process them.

---

## 🧾 How It Works

The code performs the following steps:

1. **Define a corpus**: A simple list of words like `["cat", "dog", "fish", "cat", "dog"]`.
2. **Build a vocabulary**: Extracts unique words and sorts them.
3. **Map each word to a unique index**.
4. **One-hot encode each word**: Creates a binary vector with a `1` in the position corresponding to the word's index in the vocabulary.
5. **Display the results**: Uses `pandas.DataFrame` to present the encoded vectors in a readable format.

---

## 🧠 Learning Outcomes
- Understand how to tokenize and encode text data
- Learn how to implement one-hot encoding from scratch
- Visualize encoded data using pandas

