# 📊 Sentiment Analysis on Twitter Data (Multi-Class Classification)

## 📝 Project Overview

This project focuses on building a **multi-class sentiment analysis model** using labeled Twitter data. The goal is to classify tweets into one of four sentiment categories:

- **Positive**
- **Negative**
- **Neutral**
- **Irrelevant**

The project demonstrates the use of both **traditional machine learning** and **deep learning** techniques to achieve accurate sentiment classification.

---

## 🚀 Features

1. **Data Preprocessing**:
   - Cleaning, tokenization, and lemmatization of tweets.
   - Removal of noise such as URLs, mentions, and special characters.

2. **Feature Engineering**:
   - Text vectorization using **TF-IDF**.
   - Use of word embeddings for deep learning models.

3. **Modeling**:
   - **Logistic Regression** for traditional machine learning.
   - **LSTM (Long Short-Term Memory)** network for deep learning.

4. **Evaluation**:
   - Performance comparison using metrics like **precision**, **recall**, **F1-score**, and **accuracy**.
   - Error analysis to identify areas for improvement.

---

## 📂 Project Structure

- **`ml_sentiment_analysis.ipynb`**: Jupyter Notebook containing the entire workflow, including data preprocessing, model training, and evaluation.
- **`README.md`**: Documentation for the project.

---

## 🛠️ Tools and Libraries

- **Python**: Programming language used for implementation.
- **Pandas**: For data manipulation and analysis.
- **NLTK**: For natural language processing tasks.
- **Scikit-learn**: For machine learning models and evaluation.
- **TensorFlow/Keras**: For building and training the LSTM model.

---

## 📈 Results

### Logistic Regression (Traditional ML)
- **Accuracy**: 69%
- **Strengths**: Fast and simple to implement.
- **Limitations**: Struggles with complex relationships in text data.

### LSTM (Deep Learning)
- **Accuracy**: 78%
- **Strengths**: Captures contextual relationships and sequential dependencies.
- **Limitations**: Requires more computational resources.

---

## 🔧 Future Improvements

- Use **pre-trained embeddings** like GloVe or Word2Vec for better feature representation.
- Experiment with **Bidirectional LSTM** or **Transformer-based models** like BERT.
- Perform hyperparameter tuning to optimize model performance.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

---

## 📧 Contact

For any questions or feedback, please reach out to [samObot19](https://github.com/samObot19).