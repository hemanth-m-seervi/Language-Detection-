# 🌍 Language Detection Using Machine Learning

## 📌 Project Overview

This project focuses on automatically identifying the language of a given text using Machine Learning techniques. The model is trained on multilingual text data containing samples from multiple languages and learns linguistic patterns to accurately classify the language of unseen text.

Language detection is widely used in search engines, translation systems, chatbots, content moderation, and multilingual applications.

---

## 🎯 Objective

The goal of this project is to build a machine learning model capable of:

- Detecting the language of a text input.
- Classifying text into one of several supported languages.
- Evaluating model performance using standard classification metrics.

---

## 📂 Dataset Information

The dataset contains multilingual text samples.

### Features

| Column | Description |
|----------|-------------|
| Text | Input text sample |
| language | Target language label |

### Dataset Statistics

- Total Records: 22,000
- Number of Features: 2
- Target Variable: `language`

Example:

| Text | Language |
|--------|---------|
| sebes joseph pereira thomas | Swedish |
| விசாகப்பட்டினம் தமிழ்ச்சங்கத்தை | Tamil |
| ถนนเจริญกรุง | Thai |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ⚙️ Project Workflow

### 1. Data Collection

- Load multilingual text dataset.
- Inspect data structure and quality.

### 2. Data Preprocessing

- Remove unwanted characters.
- Convert text into machine-readable format.
- Handle missing values.

### 3. Feature Engineering

Text data is transformed into numerical vectors using:

- Count Vectorizer
- TF-IDF Vectorizer

---

### 4. Model Training

Possible algorithms:

- Multinomial Naive Bayes
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

---

### 5. Model Evaluation

Performance is measured using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📊 Exploratory Data Analysis

The project includes:

- Language distribution analysis
- Dataset balance checking
- Word frequency analysis
- Text length distribution
- Class visualization charts

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/language-detection-ml.git
cd language-detection-ml
```

Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Run Jupyter Notebook:

```bash
jupyter notebook
```


---

## 📈 Results

The trained model successfully classifies text into multiple languages based on linguistic patterns learned from the training dataset.

Sample Prediction:

Input:

```
வணக்கம் நண்பர்களே
```

Output:

```
Tamil
```

Input:

```
Hello everyone
```

Output:

```
English
```

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Natural Language Processing (NLP)
- Text Preprocessing
- Feature Engineering
- Machine Learning Classification
- Model Evaluation
- Data Visualization
- Python for Data Science

---

## Future Improvements

- Deep Learning (LSTM/BERT)
- Real-time Language Detection API
- Web Application Deployment
- Multilingual Chatbot Integration

---

## 👨‍💻 Author

**Hemanth Sirvi**

