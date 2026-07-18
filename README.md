# 🧠 LSTM Next Word Prediction using TensorFlow

This project implements a **Next Word Prediction** model using a **Long Short-Term Memory (LSTM)** neural network built with TensorFlow/Keras. Given an input sequence of words, the model predicts the most likely next word and can generate text one word at a time.

---

## 📌 Features

- Text preprocessing and cleaning
- Tokenization using Keras Tokenizer
- Word embedding with Embedding layer
- LSTM-based language model
- Next word prediction
- Text generation from a seed sentence
- Save trained model and tokenizer for deployment

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Pickle

---

## 📂 Project Structure

```
├── rnn_lstm.ipynb          # Training notebook
├── qoute_dataset.csv       # Dataset
├── lstm_model.h5           # Trained model
├── tokenizer.pkl           # Saved tokenizer
├── max_len.pkl             # Maximum sequence length
├── README.md
```

---

## 📊 Workflow

1. Load the dataset
2. Clean and preprocess text
3. Tokenize the text
4. Create input sequences
5. Pad sequences
6. Build the LSTM model
7. Train the model
8. Save the trained model and tokenizer
9. Predict the next word
10. Generate text

---

## 🏗️ Model Architecture

```
Embedding Layer
        │
        ▼
     LSTM Layer
        │
        ▼
Dense Layer (Softmax)
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/LSTM-Next-Word-Prediction.git
cd LSTM-Next-Word-Prediction
```

Install the required packages:

```bash
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn
```

---

## ▶️ Run the Project

Open the notebook:

```bash
jupyter notebook rnn_lstm.ipynb
```

or

```bash
jupyter lab
```

---

## 💻 Example

Input:

```
what are you
```

Output:

```
what are you doing
```

*(Prediction depends on the training dataset.)*

---

## 📈 Future Improvements

- Train on a larger dataset
- Use Bidirectional LSTM
- Add GRU model comparison
- Deploy using Streamlit
- Add Beam Search text generation
- Hyperparameter tuning

---

## 📚 Learning Outcomes

- Natural Language Processing (NLP)
- Tokenization
- Word Embeddings
- Sequence Modeling
- LSTM Networks
- Text Generation
- Deep Learning with TensorFlow

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Saket Das**
