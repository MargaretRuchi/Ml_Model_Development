# ML Model Development 🚢

This project uses the Titanic dataset to predict passenger survival using various machine learning models. It demonstrates the complete machine learning pipeline including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and hyperparameter tuning.

---

## 📂 Project Structure

📁 ML_Model_Development/
│
├── data/
│ └── cleaned_titanic.csv
│
├── notebooks/
│ └── eda_plots/
│ ├── age_distribution.png
│ ├── fare_vs_class.png
│ └── survival_countplot.png
│
├── models/
│ └── logistic_model.pkl
│
├── results/
│ └── log_reg_confusion_matrix.png
│ └── model_comparison_bar_chart.png
  └── roc_curve.png
│
├── ML Model Development_analysis.ipynb
└── README.md


---

## ✅ Project Phases

### 1. Data Preprocessing & Cleaning
- Handled missing values (e.g., `Age`, `Embarked`)
- Encoded categorical features (e.g., `Sex`, `Embarked`)
- Removed irrelevant columns (e.g., `Cabin`, `Ticket`, `Name`)

### 2. Exploratory Data Analysis (EDA)
- Distribution plots for Age and Fare
- Count plots for survival rate, class, and gender
- Correlation heatmap and grouped survival rates

### 3. Descriptive Statistics
- Summary statistics (mean, median, std, etc.)
- Class balance overview
- Feature distribution insights

### 4. Feature Engineering
- Created new features like `FamilySize`
- Binned `Fare` and `Age` into categories
- One-hot encoding and label encoding used appropriately

### 5. Model Training & Evaluation
Models tested:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Classifier (SVC)

### 6. Best Model (Logistic Regression)
Using `GridSearchCV`, the best parameters found:
```python
{'C': 1, 'penalty': 'l1', 'solver': 'liblinear'}

Performance:
Test Accuracy: 0.7933

Precision: 0.7681

Recall: 0.7162

F1 Score: 0.7413

🔍 Confusion Matrix

📊 Model Comparison
The models were compared using accuracy, precision, recall, and F1 score. Results were saved in model_comparison_bar_chart.png.

🧠 Technologies Used
Python (pandas, numpy, matplotlib, seaborn, scikit-learn)

Jupyter Notebook

Machine Learning (classification)

Data Visualization

🔗 Follow My Data Science Journey **[MgTechInsights](https://mgtechinsights.framer.website)**  
🔗 Connect with me on [LinkedIn](https://www.linkedin.com/in/margaretmary-ajuruchi )
📧 Contact me for freelance data projects or portfolio reviews
