Naive Bayes Classifier Project
📌 Overview

This project explores the implementation of Naive Bayes Classifiers using scikit-learn. The focus is on understanding how different preprocessing techniques (Label Encoding vs One-Hot Encoding) impact model performance.

The notebook includes:

Implementation of GaussianNB and CategoricalNB

Handling categorical variables with Label Encoding & One-Hot Encoding

Model evaluation using Accuracy, Confusion Matrix, and Classification Report

Key insights on feature encoding and data distribution

⚙️ Tech Stack

Python 3.9+

NumPy

Pandas

scikit-learn

Matplotlib / Seaborn (for visualization)

Jupyter Notebook

🚀 Project Workflow

Data Preprocessing

Cleaned dataset and handled categorical variables

Applied both Label Encoding and One-Hot Encoding for comparison

Model Implementation

Trained models with GaussianNB and CategoricalNB

Compared prediction results across encodings

Model Evaluation

Accuracy score

Confusion Matrix

Classification Report

Observations

Label Encoding gave higher accuracy compared to One-Hot Encoding in this dataset

Encoding choice plays a major role in Naive Bayes performance

📊 Results

GaussianNB performed better on continuous features.

CategoricalNB worked well with label-encoded categorical data.

One-Hot Encoding led to a performance drop due to data sparsity.

📂 File Structure
📦 Naive_Bayes_Classifier
 ┣ 📜 naive_bayes.ipynb   # Jupyter notebook with full implementation
 ┣ 📜 README.md           # Project documentation
 ┗ 📜 requirements.txt    # Dependencies (optional)

🔮 Future Work

Experiment with MultinomialNB on text datasets

Apply Naive Bayes to real-world classification problems (spam detection, sentiment analysis, etc.)

Optimize preprocessing pipeline for categorical-heavy datasets

🤝 Contributing

Contributions and suggestions are welcome! Feel free to fork this repo, raise an issue, or open a pull request.
