🫀 Heart Failure Prediction with Random Forest
📌 Overview
This project is a binary classification task to predict whether a patient is likely to develop heart failure based on medical data such as age, resting blood pressure, cholesterol, and more. The model is trained using a Random Forest Classifier for its accuracy, interpretability, and ability to handle both categorical and numerical features.

📂 Dataset
Source: [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/data)
Format: CSV file
Target column: HeartDisease (1 = heart disease present, 0 = no disease)

🛠 Tools & Technologies
Python
pandas, numpy
scikit-learn (RandomForestClassifier, train_test_split, evaluation metrics)
matplotlib, seaborn (for visualizations)
Jupyter Notebook

⚙️ Workflow
1. Data Loading
  Load and inspect the heart failure dataset.
2. Data Preprocessing
  One-hot encoding of categorical features
  Handling missing values (if any)
  Feature/target separation
3. Model Training
  Train a Random Forest Classifier on 80% of the dataset.
4. Model Evaluation
  Accuracy Score
  Confusion Matrix
  Classification Report (Precision, Recall, F1-Score)
5. Feature Importance
  Visualize which features contribute most to the model’s prediction.

📊 Results
Metric	Value
- Accuracy	0.88
- Precision (0)	0.85
- Recall (0)	0.86
- F1 Score (0)	0.85
- Precision (1)	0.90
- Recall (1)	0.89
- F1 Score (1)	0.89

🧠 Key Takeaways
- Random Forest performs well on health classification tasks.
- Feature importance helps explain which medical indicators matter most.
- One-hot encoding is essential for handling categorical variables in scikit-learn.

🚀 How to Run
- Clone the repo
- Open the notebook in Jupyter or Google Colab
- Run all cells in order
- Optional: Download the dataset from the UCI link above
