1st Step:  

Involves collecting a dataset containing credit card transaction records, 
including both fraudulent and legitimate transactions. Since financial institutions cannot 
share raw transaction data due to privacy concerns, we implement a federated learning 
approach, where multiple banks contribute to training the model without exchanging actual 
transaction details. 

Dataset link: https://drive.google.com/file/d/1XfEFyHwPwXUJmxvjEUq5N-lOJ1I4zRxI/view?usp=sharing

For Details about Receiver-operating characteristic curve (ROC) : 

      References Resource Link: https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc#:~:text=need%20different%20tools.-,Receiver%2Doperating%20characteristic%20curve%20(ROC),holdover%20from%20WWII%20radar%20detection 

🤖 Machine Learning Project - Setup and Run Guide
This section explains how to set up and run the ML part of this project using a Python virtual environment (venv). 

1. Clone the Repository (if needed)
2. Create a Virtual Environment
      python -m venv venv

3. Activate the Virtual Environment
  On Windows:
    venv\Scripts\activate

4. Install Required Python Libraries
    Install all necessary libraries using the requirements.txt file

5. Run the ML Application
       python app.py

---

## 📊 Model Performance & Evaluation

This section presents the performance evaluation of the **Credit Card Fraud Detection System**, including both **Machine Learning (ML)** and **Federated Learning (FL)** approaches.

---

### 🔹 Federated Learning Training Performance

<p align="center">
  <img src="https://raw.githubusercontent.com/abusufianrobin/Credit-Card-Fraud-Detection-using-Ml-and-Federated-Learning-for-Security/DataPreProcessing/FL%20data%20training%20loss%20and%20accuracy.png" width="700"/>
</p>

<p align="center">
  <em>Training loss and accuracy progression in Federated Learning</em>
</p>

---

### 🔹 ROC Curve Analysis (ML Model)

<p align="center">
  <img src="https://raw.githubusercontent.com/abusufianrobin/Credit-Card-Fraud-Detection-using-Ml-and-Federated-Learning-for-Security/DataPreProcessing/ML%20ROC%20Curve.PNG" width="700"/>
</p>

<p align="center">
  <em>ROC curve demonstrating classification performance of the ML model</em>
</p>

---

### 🔹 Data Splitting Strategy

<p align="center">
  <img src="https://raw.githubusercontent.com/abusufianrobin/Credit-Card-Fraud-Detection-using-Ml-and-Federated-Learning-for-Security/DataPreProcessing/ML%20Split%20Data.PNG" width="700"/>
</p>

<p align="center">
  <em>Training and testing data distribution</em>
</p>

---

### 🔹 Accuracy & Classification Report

<p align="center">
  <img src="https://raw.githubusercontent.com/abusufianrobin/Credit-Card-Fraud-Detection-using-Ml-and-Federated-Learning-for-Security/DataPreProcessing/ROC%20Accuracy%20Score%20report.PNG" width="700"/>
</p>

<p align="center">
  <em>Model accuracy, precision, recall, and F1-score evaluation</em>
</p>

---

## 🎥 Demo Video

[![Watch the Demo](https://img.youtube.com/vi/0rdVEIsVn48/0.jpg)](https://www.youtube.com/watch?v=0rdVEIsVn48)

> Click the image above to watch the full demo on YouTube.


📋 Author
Name: Abu Sufian Robin

GitHub: @abusufianrobin

Email: abusufian02robin@gmail.com

📄 License
This project is licensed under the MIT License.

