# Deep Learning – RNN, LSTM, GRU & Encoder-Decoder

## 👨‍🎓 Student Details

**Name:** Muppana Bhavani Siva Sri Harish
**Branch:** Electronics and Communication Engineering (ECE)
**University:** GITAM University
**Year:** B.Tech – 4th Year
**Semester:** 7th Semester

---

## 📌 Project Overview

This project focuses on implementing and understanding different deep learning sequence models, including **RNN, LSTM, GRU, Word Embeddings, and Encoder-Decoder architectures**.

The project covers time-series prediction, text classification, sequence modelling, and machine translation using **Python and TensorFlow/Keras**.

---

## 🎯 Objectives

* Implement a Simple RNN for sequence prediction.
* Study the effect of different hyperparameters.
* Implement text classification using word embeddings and RNN.
* Compare RNN, LSTM, and GRU architectures.
* Understand hidden states and cell states.
* Understand LSTM and GRU gates.
* Implement an Encoder-Decoder architecture.
* Perform English-to-German sequence translation.
* Evaluate models using different performance metrics.
* Study limitations and possible improvements.

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Kaggle Notebook
* GitHub

---

# 📚 Project Parts

## Part A – RNN for Sequence Prediction

A **Simple RNN** was implemented for time-series sequence prediction.

### Topics Covered

* Data preprocessing
* Data normalization
* Sliding-window sequence creation
* Simple RNN
* Hidden states
* Sequence length experiments
* Hidden-unit experiments
* Learning-rate experiments
* Batch-size experiments
* Epoch experiments

### Evaluation Metrics

* MAE – Mean Absolute Error
* MSE – Mean Squared Error
* RMSE – Root Mean Squared Error

Training-loss and actual-vs-predicted graphs were also generated.

---

## Part B – Word Embeddings and RNN

A small text-classification dataset was used to demonstrate sentiment classification.

### Steps

1. Text cleaning
2. Tokenization
3. Integer encoding
4. Padding
5. Word embedding
6. RNN classification

Different embedding dimensions were also studied.

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

The project also compares **word embeddings with one-hot encoding**.

---

## Part C – RNN vs LSTM vs GRU

Three sequence models were implemented and compared:

* Simple RNN
* LSTM
* GRU

### Comparison

| Metric        | RNN | LSTM | GRU |
| ------------- | --- | ---- | --- |
| Accuracy      | ✓   | ✓    | ✓   |
| Precision     | ✓   | ✓    | ✓   |
| Recall        | ✓   | ✓    | ✓   |
| F1 Score      | ✓   | ✓    | ✓   |
| Test Loss     | ✓   | ✓    | ✓   |
| Parameters    | ✓   | ✓    | ✓   |
| Training Time | ✓   | ✓    | ✓   |

### LSTM Concepts

* Hidden state
* Cell state
* Forget gate
* Input gate
* Output gate

### GRU Concepts

* Hidden state
* Update gate
* Reset gate

---

## Part D – Encoder-Decoder

An **Encoder-Decoder architecture** was implemented for English-to-German translation.

### Architecture

```text
English Sentence
       ↓
   Tokenization
       ↓
    Embedding
       ↓
     Encoder
       ↓
Hidden State + Cell State
       ↓
     Decoder
       ↓
   German Sentence
```

### Features

* Encoder
* Decoder
* `<start>` token
* `<end>` token
* Sequence-to-sequence learning
* Translation of unseen sentences
* Greedy decoding
* BLEU score evaluation

---

## Part E – Model Comparison and Analysis

The final part compares the models based on:

* Accuracy
* Loss
* Number of parameters
* Training time

It also discusses the relationship between:

**Text → Tokenization → Embedding → RNN/LSTM/GRU → Hidden State → Output**

and for translation:

**Source Sentence → Encoder → Hidden/Cell State → Decoder → Target Sentence**

---

## 🌍 Real-World Applications

Sequence models can be used for:

* Machine translation
* Sentiment analysis
* Speech recognition
* Text generation
* Chatbots
* Time-series forecasting
* Text summarization
* Question answering

---

## ⚠️ Dataset Note

Due to internet restrictions in the Kaggle Notebook environment, **small locally created demonstration datasets** were used for some parts of this project.

These datasets are intended for educational and experimental purposes and are **not official large-scale datasets such as IMDB or a large translation corpus**.

---

## ⚠️ Limitations

* Small demonstration datasets
* Limited training data
* Possible overfitting
* Limited translation vocabulary
* Basic greedy decoding
* BLEU limitations on very small datasets
* Higher computational requirements for larger models

---

## 🚀 Future Improvements

* Use larger real-world datasets.
* Use pretrained word embeddings.
* Implement Bidirectional RNN/LSTM/GRU.
* Implement Attention mechanisms.
* Explore Transformer architectures.
* Perform extensive hyperparameter tuning.
* Use larger translation datasets.
* Increase training data and vocabulary size.

---

## 📁 Project Structure

```text
Deep-Learning-RNN-LSTM-GRU-Sequence-Modeling/
│
├── README.md
├── Deep_Learning_Assignment.ipynb
├── requirements.txt
│
├── datasets/
│   └── README.md
│
├── results/
│   ├── rnn_results.png
│   ├── lstm_results.png
│   ├── gru_results.png
│   └── comparison.png
│
└── video/
    └── project_demo_link.txt
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Deep-Learning-RNN-LSTM-GRU-Sequence-Modeling.git
```

### 2. Open the notebook

Open:

```text
Deep_Learning_Assignment.ipynb
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

Run the notebook sequentially from **Part A to Part E**.

---

## 📈 Learning Outcomes

Through this project, I gained practical understanding of:

* Recurrent Neural Networks
* Hidden states
* Vanishing gradients
* Word embeddings
* Text preprocessing
* LSTM architecture
* GRU architecture
* Encoder-Decoder models
* Sequence-to-sequence learning
* BLEU evaluation
* Model comparison
* Deep learning experimentation using TensorFlow/Keras

## ⭐ Acknowledgement

This project was developed as part of my academic deep learning coursework to gain practical experience with sequence-based neural network architectures and their applications.
