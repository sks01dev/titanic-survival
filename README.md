

# 🚢 **Titanic Survival Analysis (Project from Udacity Nanodegree Program)**

![Titanic](https://upload.wikimedia.org/wikipedia/commons/f/fd/RMS_Titanic_3.jpg)

## **📋 Project Overview**
This project analyzes the survival patterns of passengers aboard the RMS Titanic using a machine learning model. By leveraging features like age, gender, ticket class, and fare, the model predicts whether a passenger would survive based on historical data.

---

## **💡 Key Features**
- **Exploratory Data Analysis (EDA):**
  - Visualized survival rates by gender, passenger class, and age.
  - Addressed missing values in critical columns like `Age` and `Embarked`.
- **Machine Learning:**
  - Built and evaluated a Decision Tree Classifier.
  - Tuned hyperparameters to optimize accuracy.
- **Performance Metrics:**
  - **Training Accuracy:** High precision in predicting survival for training data.
  - **Test Accuracy:** Generalized well to unseen data.

---

## **📂 Dataset Description**
The dataset consists of 891 rows and 12 columns, providing comprehensive details about passengers:

| Feature       | Description                               |
|---------------|-------------------------------------------|
| `Survived`    | Target variable (1 = Survived, 0 = Died)  |
| `Pclass`      | Ticket class (1st, 2nd, 3rd)              |
| `Sex`         | Gender of the passenger                  |
| `Age`         | Age of the passenger (some missing)      |
| `SibSp`       | Number of siblings/spouses aboard        |
| `Parch`       | Number of parents/children aboard        |
| `Fare`        | Fare paid for the ticket                 |
| `Embarked`    | Port of embarkation (C, Q, S)            |

---

## **🔍 Methodology**
1. **Data Preprocessing:**
   - Handled missing values in `Age` (imputation) and `Embarked` (mode replacement).
   - Normalized numerical features to improve model performance.
2. **Feature Engineering:**
   - Created new features like `FamilySize` and categorized ages into bins.
3. **Model Training:**
   - Used a Decision Tree Classifier for classification.
   - Tuned hyperparameters like `max_depth` and `min_samples_split`.
4. **Evaluation:**
   - Analyzed accuracy metrics for both training and testing datasets.

---

## **📈 Results**
| Metric               | Value  |
|-----------------------|--------|
| **Training Accuracy** | 100%   |
| **Test Accuracy**     | 80%    |

> **Note:** Further improvements in test accuracy are achievable using techniques like cross-validation, pruning, or ensemble methods and from tuning hyperparams we've achieved 85% accuracy.

---

## **🌟 Visualizations**
- **Survival by Gender:**
  ![Survival by Gender](https://example.com/survival_gender_chart.png)
- **Age Distribution:**
  ![Age Distribution](https://example.com/age_distribution_chart.png)

*(Replace placeholders with your actual visualizations)*

---

## **🚀 How to Run**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic-survival-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```bash
   jupyter notebook Titanic_survival_data.ipynb
   ```

---

## **🛠 Tools & Technologies**
- **Languages:** Python
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Tools:** Jupyter Notebook

---

## **📬 Contact**
Have questions or feedback? Reach out:
- **Email:** [your-email@example.com](mailto:your-email@example.com)
- **GitHub:** [yourusername](https://github.com/yourusername)

---

This README should provide a clear, professional, and visually appealing overview of your project. Let me know if you'd like to customize further or add actual visualizations!
