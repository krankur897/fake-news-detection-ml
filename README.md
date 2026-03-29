# 📰 Fake News Detection using Machine Learning

## 📌 Overview

With the rapid growth of digital platforms, news spreads faster than ever before. While this has made information easily accessible, it has also increased the spread of fake and misleading content. Many people share news without verifying its authenticity, which can lead to confusion and misinformation.

This project focuses on building a machine learning model that can classify news articles as **real or fake** based on their textual content. The goal is to create a simple system that helps users quickly assess the credibility of news.

---

## 🎯 Objective

The objectives of this project are:

* To build a machine learning model for fake news detection
* To apply Natural Language Processing techniques on text data
* To compare multiple classification algorithms
* To create an easy way to test the model using user input

---

## 🧠 How It Works

### 1. Dataset

Two datasets are used:

* `Fake.csv` → Fake news articles
* `True.csv` → Real news articles

Only the **text** column is used for prediction.

---

### 2. Data Cleaning

The text data is preprocessed by:

* Converting text to lowercase
* Removing punctuation and special characters
* Removing URLs and unwanted patterns

---

### 3. Feature Extraction

The cleaned text is converted into numerical form using **TF-IDF Vectorization**.

---

### 4. Model Training

Multiple machine learning models are used:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting

---

### 5. Prediction System

The system takes user input and predicts whether the news is:

* **Real News**
* **Fake News**

---

## 📊 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~98%     |
| Decision Tree       | ~99%     |
| Gradient Boosting   | ~99%     |
| Random Forest       | ~98%     |

---

## 💻 Interface

A simple interactive interface is created using **ipywidgets**, allowing users to:

* Enter news text
* Click a button
* View prediction instantly

---

## 🚀 How to Run

### 1. Install Dependencies

```
pip install pandas numpy scikit-learn ipywidgets
```

### 2. Clone Repository

```
git clone https://github.com/krankur897/fake-news-detection-ml.git
```

### 3. Open Project

Open the folder in Jupyter Notebook or VS Code.

### 4. Run Notebook

Run all cells step by step.

### 5. Test the Model

Enter news text and check prediction.

---

## 🧪 Example

**Input:**

```
NEW YORK (Reuters) - The company reported strong quarterly growth.
```

**Output:**

```
Real News
```

---

## ⚠️ Limitations

* Performance depends on the dataset
* Works best on structured news articles
* Not reliable for short or informal text
* Does not verify facts, only detects patterns

---

## 🔮 Future Scope

* Use more diverse datasets
* Apply advanced models like BERT or LSTM
* Build a web application
* Improve real-world performance

---

## 📚 Learning Outcomes

* Text preprocessing techniques
* TF-IDF feature extraction
* Training and comparing ML models
* Understanding dataset limitations
* Building an end-to-end ML system

---

## 📁 Project Structure

```
fake-news-detection-ml/
│
├── Fake.csv
├── True.csv
├── fake_news.ipynb
├── README.md
├── LICENSE
```

---

## 🔗 Repository

https://github.com/krankur897/fake-news-detection-ml.git

---

## ⭐ Final Note

This project demonstrates how machine learning can be used to detect fake news. While the model performs well on the dataset used, further improvements can make it more effective for real-world applications.
