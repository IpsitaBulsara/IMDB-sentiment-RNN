# 🎭 IMDB Sentiment Analyzer using SimpleRNN

This project focuses on building a sentiment analysis model using the IMDB movie review dataset. The objective is to classify movie reviews as either **positive** or **negative**. The project demonstrates two different approaches using **SimpleRNN** in **TensorFlow Keras**.

---

## 🧠 Models Used

We have implemented two models using **SimpleRNN**:

1. **Without Embedding Layer** – Implemented in `main.ipynb`.
2. **With Embedding Layer** – Implemented in `embedding.ipynb`, where the embedding layer is used for better representation of words.

---

## 📁 File Structure

| File Name         | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| `main.ipynb`      | Sentiment analysis using SimpleRNN **without** the embedding layer.        |
| `embedding.ipynb` | Sentiment analysis using SimpleRNN **with** an embedding layer.            |

---

## 🛠 Technologies Used

- Python
- TensorFlow Keras
- SimpleRNN
- IMDB Dataset (available through Keras datasets)
- Jupyter Notebook

---



## 📊 Results

- The embedding-based model (`embedding.ipynb`) showed improved performance.
- The model without embeddings (`main.ipynb`) performed decently but lacked semantic understanding.

---

## 📌 Conclusion

This project highlights how incorporating word embeddings significantly improves the performance of RNNs in natural language processing tasks like sentiment analysis.

