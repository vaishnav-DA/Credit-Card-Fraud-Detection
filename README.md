# 💳 Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions using supervised learning techniques.

## 📌 Objective

To build a classification model that accurately identifies fraudulent transactions based on transaction data.

## 📂 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains transactions made by European cardholders in September 2013.
- **Total Rows**: 284,807 transactions  
- **Features**: 30 columns (anonymized due to privacy), including:
  - `Time`, `Amount`, `V1` to `V28`, and `Class` (target: 0 = Non-fraud, 1 = Fraud)

## 🧠 Techniques Used

- Exploratory Data Analysis (EDA)
- Handling Class Imbalance using SMOTE
- Feature Scaling with `StandardScaler`
- Model Building:
  - Logistic Regression
  - Random Forest Classifier
- Evaluation Metrics:
  - Confusion Matrix
  - Classification Report
  - ROC-AUC Curve

## ⚙️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- imbalanced-learn (SMOTE)

## 📈 Results

- **Random Forest** outperformed Logistic Regression on key metrics.
- **ROC-AUC Score** provided better insight for imbalanced classification.
- SMOTE helped in balancing the dataset for effective learning.

## 📌 Key Takeaways

- Fraud detection is a high-class-imbalance problem.
- Using SMOTE + ensemble models like Random Forest improves performance.
- Evaluation metrics beyond accuracy are critical for imbalanced datasets.

## 📁 Folder Structure

Credit-Card-Fraud-Detection/
├── creditcard.csv
├── Credit_Card_Fraud_Detection.ipynb
└── README.md 



## 🚀 How to Run

1. Clone the repo or upload files to Colab.
2. Upload `creditcard.csv`.
3. Run the Jupyter notebook step-by-step.

## 📬 Contact

For queries, feel free to raise an issue or reach out via GitHub.
