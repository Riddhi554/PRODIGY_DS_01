# Data Science Internship Tasks 🧑‍💻

A collection of tasks and projects completed during my data science internship at Prodigy InfoTech, showcasing various technical skills, data analysis, and machine learning solutions.  

## Task 1: Visualizing Data Distribution 📊  
**Objective:** Create a bar chart or histogram to visualize the distribution of a categorical or continuous variable, such as the distribution of ages or genders in a population.  

**Key steps included:**  
- Visualizing the distribution of gender using a bar chart.  
- Analyzing the distribution of class levels (`Kelas`) with a histogram and KDE plot.  

**Dataset:**  
- Source: [Kaggle - Indonesia's Science Olympiad Dataset](https://www.kaggle.com/code/devraai/unveiling-secrets-of-indonesias-science-olympiad/input)  

---

## Task 2: Data Cleaning and Exploratory Data Analysis (Titanic Dataset) 🧳  
**Objective:** Perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset to explore relationships between variables and identify patterns and trends in the data.  

**Key steps included:**  
- Dataset overview: Checked for missing values and basic statistics.  
- Data cleaning:  
  - Filled missing `Age` with the median value.  
  - Replaced missing `Embarked` values with the mode.  
  - Dropped the `Cabin` column due to excessive missing values.  
- Exploratory analysis:  
  - Visualized survival counts, class distributions, and survival relationships by gender and class.  
  - Boxplot for age distribution by survival status.  
  - Heatmap showing correlations between numeric features.  
- Categorical encoding: Converted `Sex` and `Embarked` to numeric values for analysis.  
- Saved the cleaned dataset as `cleaned_titanic_data.csv`.  

**Dataset:**  
- Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/code/ihabsherbiny/titanic-survival-prediction-ml/input)  

---

## Task 3: Decision Tree Classifier for Predicting Customer Purchases 🌳  
**Objective:** Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data.  

**Key steps included:**  
- Dataset overview: Explored the bank marketing campaign dataset.  
- Preprocessing:  
  - Encoded categorical variables using `LabelEncoder`.  
  - Replaced 'unknown' values in some columns with 'other'.  
- Applied **SMOTE** to handle class imbalance.  
- Split data into training and testing sets.  
- Hyperparameter tuning using **GridSearchCV** to optimize the decision tree model.  
- Evaluated the model using accuracy score and classification report.  
- Implemented a prediction function for real-time customer purchase predictions.  

**Dataset:**  
- Source: [Kaggle - Bank Marketing Campaign Dataset](https://www.kaggle.com/code/janiobachmann/bank-marketing-campaign-opening-a-term-deposit)  

---

## Tasks Overview 📝  
1. **Task 1**: Visualizing Data Distribution (Gender and Class Levels).  
2. **Task 2**: Data Cleaning and EDA on Titanic Dataset.  
3. **Task 3**: Decision Tree Classifier for Customer Purchase Prediction.  

## Getting Started 🚀  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Riddhi554/Prodigy-InfoTech-DataScience.git  
