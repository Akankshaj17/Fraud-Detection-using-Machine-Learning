# 🕵️‍♂️ Fraud-Detection-using-Machine-Learning

# 🔍 Introduction

- This is a hands-on machine learning project focused on detecting fraudulent payment transactions using real-world techniques like EDA, outlier removal, SMOTE for class balancing, and multiple classification models.  

- The goal is to accurately classify whether a transaction is **fraudulent (`label=1`)** or **not (`label=0`)** — even when fraud is rare.

- This project helped me put multiple ML concepts into action, including data cleaning, EDA, class imbalance handling, and model comparison.

# 🔍 Key Steps:

🧹 Data Preprocessing:

    – Removed outliers using IQR method.
    
    – Encoded categorical features like paymentMethod using LabelEncoder.
    
    – Standardized numerical features with StandardScaler.

📊 EDA (Exploratory Data Analysis):

    – Visualized accountAgeDays, numItems, and paymentMethodAgeDays across fraud labels.
    
    – Used boxplots and violin plots to spot patterns and data imbalance.

⚖️ Handled Class Imbalance:

    – Applied SMOTE to oversample the minority class (fraud cases).

🤖 Model Training & Evaluation:

    – Trained and tested KNN, SVM, Linear Regression, and Random Forest.
    
    – Evaluated models using confusion matrix, precision, recall, F1-score, and accuracy.

🏆 Results:

   - Before SMOTE: Most models struggled to catch fraud.

   - After SMOTE: Random Forest achieved 100% accuracy and recall.

# 📌 Key Learning:

   - Handling imbalance and choosing the right preprocessing steps are just as critical as the algorithm choice.

# 🧠 This project taught me the importance of:

   - Visual exploration before modeling.

   - Proper scaling and encoding.

   - Avoiding misleading accuracy with imbalanced data.

# 🔧 Tech Stack:

  🐍 Python

  🧮 Pandas & NumPy

  📈 Matplotlib & Seaborn

  🤖 Scikit-learn

  ⚖️ imbalanced-learn (for SMOTE)

# 📌 Future Enhancements:

  🔄 Hyperparameter tuning for best model.

  🧪 Add cross-validation.

  🌐 Build a Streamlit or Flask web app for live fraud detection.

#ML #Python #FraudDetection #PortfolioProject #DataScience #SMOTE #ScikitLearn #RandomForest #ModelEvaluation #ImbalancedData #DataCleaning




