# ML Sentiment Analysis

---

## ℹ️ About the Project

**ML Sentiment Analysis** is project that:

- Classify Reviews based on Sentiment and evaluates Accuracy, Training Time, Testing Time, and Confusion Matrix, using:
  - fastText
  - BERT (HuggingFace)
  - gpt-4o-mini (openAI)
  - Long Short Term Memory (LSTM)
  - textCNN
  - Naive Bayes with TF-IDF
  - Logistic Regression with TF-IDF

---

## 🛠️ Built With

- [Python](https://www.python.org/) — primary programming language
- [PyCharm](https://www.jetbrains.com/pycharm/) — IDE

- [Scikit-learn](https://scikit-learn.org/stable/) — machine learning, TF-IDF, naive bayes and logistic regression
- [TensorFlow](https://www.tensorflow.org/) — Keras dependecies
- [Pandas](https://pandas.pydata.org/) — data manipulation
- [NumPy](https://numpy.org/) — number operations
- [Matplotlib](https://matplotlib.org/) — plotting
- [Seaborn](https://seaborn.pydata.org/) — data visualization
- [fastText](https://fasttext.cc/) — fastText model
- [HuggingFace Transformer](https://huggingface.co/) — BERT model
- [openAI API](https://platform.openai.com/docs/overview) — gpt-4o-mini model
- [Keras](https://keras.io/) — LSTM and CNN models

---

## 📦 Getting Started

### Prerequisites

To run the project locally, you'll need:

- PyCharm (2025.1.1.1 or newer)

---

### Installation & Setup

1. **Install the necessary libraries:**

   ```bash
   pip install scikit-learn pandas numpy matplotlib seaborn fasttext transformers openai tensorflow keras kaggle

2. **Download dataset through the terminal:**

   ```bash
   kaggle datasets download -d bittlingmayer/amazonreviews

3. **Extract the dataset zip:**

   ```bash
   with zipfile.ZipFile("amazonreviews.zip", "r") as zip_ref:
      zip_ref.extractall("amazonreviews")

4. **Run the code:**

   Run the provided `code.py`

---

## 📊 Results

![Alt text](Figure_1.png?raw=true "Title")
![Alt text](Figure_2.png?raw=true "Title")
![Alt text](Figure_3.png?raw=true "Title")
![Alt text](Figure_4.png?raw=true "Title")
![Alt text](Figure_5.png?raw=true "Title")
![Alt text](Figure_6.png?raw=true "Title")
![Alt text](Figure_7.png?raw=true "Title")
![Alt text](Figure_8.png?raw=true "Title")
![Alt text](Figure_9.png?raw=true "Title")

## 📃 License

This project is licensed under the MIT License. See the `LICENSE.txt` file for more information.
