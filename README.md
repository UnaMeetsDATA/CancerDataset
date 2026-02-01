# CancerDataset

🩺 Breast Cancer Classification Using Support Vector Machine (SVM)
1. Project Overview

This project focuses on the application of Machine Learning techniques to classify breast cancer tumors as Benign or Malignant using a Support Vector Machine (SVM). The study aims to develop a reliable predictive model based on clinical measurement data to support early diagnosis and decision-making.

A supervised learning approach was implemented, including data preprocessing, feature scaling, model training, and performance evaluation.

2. Dataset Description

The dataset consists of clinical features extracted from breast tissue images.

Total Samples: 569

Number of Features: 30 numerical attributes

Target Variable: diagnosis

Benign (B → 0)

Malignant (M → 1)

Data Cleaning

Removed irrelevant columns: id and Unnamed: 32

Verified absence of missing values

Confirmed appropriate data types

3. Tools and Technologies

The following technologies and libraries were used:

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

These tools supported data manipulation, visualization, model development, and evaluation.

4. Exploratory Data Analysis

Exploratory analysis was performed to understand data distribution and class balance. A count plot was used to visualize the proportion of benign and malignant cases, indicating moderate class balance.

Statistical summaries and structural inspections were also conducted.

5. Data Preprocessing

Several preprocessing steps were applied to improve model performance:

Label Encoding

Malignant → 1

Benign → 0

Train-Test Split

Training Set: 70%

Testing Set: 30%

Random State: 42

Feature Scaling

Standardization using StandardScaler

Ensured features had zero mean and unit variance

6. Model Development

A Support Vector Machine classifier with a linear kernel was implemented.

Algorithm: Support Vector Classification (SVC)

Kernel: Linear

Library: Scikit-learn

The model was trained on the standardized training dataset and used to predict outcomes on the test dataset.

7. Model Evaluation

Model performance was evaluated using the confusion matrix and classification report.

Performance Results

Accuracy: 98%

Precision: 0.97 – 0.98

Recall: 0.97 – 0.98

F1-Score: 0.97 – 0.98

Confusion Matrix
[[106   2]
 [  2  61]]


The results indicate high predictive accuracy and minimal classification errors.

8. Project Structure
├── untitled1.ipynb
└── README.md

9. How to Run the Project
Step 1: Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

Step 2: Mount Google Drive (Google Colab Users)
from google.colab import drive
drive.mount('/content/drive')

Step 3: Execute the Notebook

Run all notebook cells to perform data loading, preprocessing, model training, and evaluation.

10. Key Contributions

Cleaned and prepared a real-world medical dataset

Applied feature scaling for optimal model performance

Developed a high-accuracy classification model

Evaluated results using standard metrics

Produced reproducible and well-documented analysis

11. Author

Una Netshizwa
Computer Science Graduate 
Special Interest: Data Science and Machine Learning | software development 
