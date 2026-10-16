# Phishing URL Detection Using Machine Learning

## 📌 Project Overview

Phishing URL Detection Using Machine Learning is a cybersecurity project that identifies phishing and legitimate URLs using a Decision Tree Classifier. The project uses the PhiUSIIL Phishing URL Dataset to train and evaluate a machine learning model.

The main goal is to help identify potentially malicious URLs and improve awareness of phishing threats.

## 🎯 Objectives

- Detect phishing and legitimate URLs using Machine Learning.
- Explore and preprocess the dataset.
- Train a Decision Tree Classification model.
- Visualize the decision tree and confusion matrix.
- Evaluate model performance using multiple classification metrics.

## 📂 Dataset

**Dataset Name:** PhiUSIIL Phishing URL Dataset

The dataset contains URL-related features used to classify URLs.

The target column is `label`, which is converted into the following classes:

- `1` – Phishing
- `0` – Legitimate

The notebook preprocesses the data, handles missing and infinite feature values, and selects numerical features for model training.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## 🤖 Machine Learning Algorithm

**Decision Tree Classifier**

A Decision Tree is a supervised Machine Learning algorithm that learns decision rules from training data to make predictions.

### Model Configuration

- Maximum Depth: 5
- Class Weight: Balanced
- Random State: 42
- Training Data: 80%
- Testing Data: 20%

## ⚙️ Project Workflow

1. Import the required Python libraries.
2. Load the PhiUSIIL Phishing URL Dataset.
3. Explore the dataset and examine its features.
4. Handle missing and infinite values.
5. Encode the target labels.
6. Select numerical features for training.
7. Split the dataset into training and testing sets.
8. Train the Decision Tree Classifier.
9. Predict the labels for the test data.
10. Visualize the decision tree and confusion matrix.
11. Evaluate the model using classification metrics.

## 📊 Model Evaluation Metrics

The model is evaluated using the following metrics:

- **Accuracy:** Measures the overall proportion of correct predictions.
- **Precision:** Measures how many URLs predicted as phishing are actually phishing.
- **Recall:** Measures how many actual phishing URLs are correctly detected.
- **F1-score:** Balances Precision and Recall.
- **Specificity:** Measures how many legitimate URLs are correctly identified.

These metrics provide a broader understanding of the model's classification performance.

## 📈 Visualizations

The project includes:

- Decision Tree Visualization
- Confusion Matrix
- Model Evaluation Results

These visualizations help explain the model's decision-making process and performance.

## 🚀 How to Run the Project

### Step 1: Download the Repository

Download or clone the project repository to your computer.

### Step 2: Install Dependencies

Run the following command:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

### Step 3: Extract the Dataset

Extract the PhiUSIIL Phishing URL Dataset ZIP file and locate the CSV file.

### Step 4: Update the Dataset Path

Make sure the CSV file path in the notebook matches its actual location.

### Step 5: Open the Notebook

Open `ML_6.ipynb` using Jupyter Notebook or Google Colab.

### Step 6: Run the Code

Execute all cells in order to preprocess the dataset, train the model, generate visualizations, and display the evaluation results.

## 💡 Applications

- Phishing URL identification
- Cybersecurity education and research
- Machine Learning-based URL classification
- Phishing awareness and prevention support

## 🔮 Future Enhancements

- Compare multiple Machine Learning algorithms.
- Improve feature selection and model performance.
- Add additional evaluation metrics and cross-validation.
- Develop a web application for URL prediction.
- Explore real-time URL classification.

## ⚠️ Limitations

The model's predictions depend on the dataset, selected features, and training process. High evaluation scores alone do not guarantee that the model will correctly classify unseen URLs. Further testing on independent data is necessary.

## 🔒 Disclaimer

This project is developed for educational and research purposes. It should not be used as the sole method for determining whether a URL is safe or malicious.

## 👩‍💻 Project Information

**Project Title:** Phishing URL Detection Using Machine Learning

**Notebook:** `ML_6.ipynb`

**Dataset:** PhiUSIIL Phishing URL Dataset

**Primary Algorithm:** Decision Tree Classifier

