# IMDB-Sentiment-Analysis-RNN
# IMDB Movie Reviews Sentiment Analysis using RNN

## 📌 Project Overview
This project performs **sentiment analysis** on the IMDB movie reviews dataset using a **Recurrent Neural Network (RNN)**.  
The goal is to classify movie reviews as **Positive** or **Negative** based on textual content.

This project demonstrates end-to-end NLP workflow including:
- Text preprocessing
- Tokenization & padding
- RNN model building
- Model training & evaluation

---

## 🧠 Problem Statement
Movie reviews contain unstructured text data.  
The challenge is to convert this text into a numerical form and build a deep learning model that can understand **context and sequence** of words to predict sentiment accurately.

---

## 📊 Dataset
- **Dataset**: IMDB Movie Reviews
- **Type**: Binary classification
- **Labels**:
  - 1 → Positive Review
  - 0 → Negative Review

---

## Technologies & Libraries Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Natural Language Processing (NLP)

---

##  Model Architecture
- Embedding Layer
- Simple RNN Layer
- Dense Output Layer with Sigmoid Activation

The RNN helps capture **sequential dependencies** in text data.

---

##  Workflow
1. Load IMDB dataset
2. Perform text preprocessing
3. Tokenize and pad sequences
4. Build RNN model
5. Train the model
6. Evaluate model performance
7. Predict sentiment for new reviews

---

## 📈 Results
- Successfully trained an RNN-based sentiment classifier
- Model is able to predict positive and negative reviews with good accuracy

---

## 🧪 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/IMDB-Sentiment-Analysis-RNN.git
