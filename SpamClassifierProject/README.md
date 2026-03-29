# 📧 Spam Email Classifier using Machine Learning

---

## 🔍 Project Overview

Spam messages are unwanted and often harmful messages that can contain advertisements, scams, or malicious content. Detecting spam manually is inefficient and time-consuming.

This project presents a machine learning-based solution that automatically classifies SMS messages into **Spam** or **Not Spam (Ham)** using Natural Language Processing (NLP) techniques and the **Naive Bayes algorithm**.

---

## 🎯 Objectives

* To build a machine learning model for spam detection
* To understand text preprocessing using TF-IDF
* To implement a classification model using Naive Bayes
* To evaluate the model using accuracy and confusion matrix

---

## 📂 Dataset Description

The dataset used contains SMS messages labeled as:

* **Spam** → unwanted or promotional messages
* **Ham** → normal messages

Each entry consists of:

* Label (spam/ham)
* Message content

The dataset is widely used for spam classification tasks and provides a good balance of spam and non-spam messages.

---

## ⚙️ Methodology

### 1. Data Loading

The dataset is loaded using the Pandas library.

### 2. Data Preprocessing

Text messages are converted into numerical form using **TF-IDF (Term Frequency-Inverse Document Frequency)**, which captures the importance of words in the dataset.

### 3. Train-Test Split

The dataset is split into:

* 80% training data
* 20% testing data

### 4. Model Training

The **Multinomial Naive Bayes** algorithm is used because it is highly effective for text classification problems.

### 5. Prediction

The trained model predicts whether a message is spam or not.

---

## 📊 Results

* The model achieved an accuracy of approximately **95%+**
* The confusion matrix shows that most messages are correctly classified
* The model performs well on both spam and non-spam messages

---

## 🧪 Example

**Input:**
Congratulations! You have won a free lottery ticket

**Output:**
Spam

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* VS Code / Jupyter Notebook

---

## 🚀 How to Run the Project

1. Clone the repository or download files
2. Install required libraries:

   ```
   pip install pandas numpy scikit-learn
   ```
3. Open the notebook (`spam_classifier.ipynb`)
4. Run all cells
5. Test with custom messages

---

## 💡 Future Scope

* Improve accuracy using advanced algorithms like Random Forest or Deep Learning
* Deploy the model as a web application
* Integrate with email or messaging platforms

---

## 📌 Conclusion

This project successfully demonstrates how machine learning can be applied to real-world problems such as spam detection. The Naive Bayes algorithm proved to be efficient, fast, and accurate for text classification tasks.

---

## 👨‍💻 Author

Developed as part of Fundamentals of AI and ML course project.
