# Customer Journey Prediction

**Customer Journey Prediction** is my attempt to understand how customers behave over time and predict their future actions using data-driven modeling.  
The project focuses on transforming raw transactional data into meaningful customer insights and predictive intelligence.

---

##  Project Overview

Customer Journey Prediction is a data science project designed to analyze customer purchasing behavior and predict future customer actions such as purchase likelihood and customer value.

The project involves:
- Cleaning raw transactional data  
- Engineering meaningful behavioral features  
- Building predictive models  
- Generating actionable business insights  

---

##  Key Achievements

- Transformed raw customer data into structured, analytics-ready datasets using feature engineering and validation  
- Built **classification and regression models** to predict customer behavior and value  
- Developed a **customer scoring system** to rank and prioritize customers  
- Identified key drivers of customer engagement and spending patterns  

---

##  Dataset Description

**Note:** The dataset was extensively cleaned and transformed to handle missing values, inconsistent formats, and derive meaningful customer-level features.

### Key Features:
- `customer_unique_id`
- `total_orders`
- `total_spent`
- `avg_price`
- `total_items`
- `avg_order_value`
- `days_since_last_purchase`
- `customer_tenure_days`

###  Challenge:
Raw data lacked direct indicators of customer behavior, requiring feature engineering to derive meaningful insights such as customer value and engagement.

---

##  Tech Stack

### Programming & Data Processing
- Python  
- Pandas  
- NumPy  

### Exploratory Analysis & Visualization
- Matplotlib  
- Seaborn  

### Machine Learning
- Scikit-learn  
- Logistic Regression  
- Regression Models  

---

### Workflow

### 1. Data Preparation
Cleaned and structured raw customer data
Renamed and standardized columns
Handled missing values and inconsistencies
Engineered behavioral features:
Average order value
Customer tenure
Purchase frequency

### 2. Exploratory Data Analysis (EDA)
Analyzed customer spending patterns
Studied relationships between:
Orders and total spend
Tenure and engagement
Identified key drivers of customer value

### 3. Machine Learning
#### Classification Model
Built a classification model to predict:
High-value vs low-value customers (or purchase likelihood)

#### Regression Model
Built a regression model to:
Predict continuous customer score / value

#### Why both models?
Classification → tells who is likely to act
Regression → tells how valuable they are

### 4. Customer Scoring
Generated a customer_score using model predictions
Ranked customers based on predicted value


##  Quick Start

```bash
# Clone the repository
git clone https://github.com/siddhiwanzkhade/Customer-Journey-Prediction.git
cd Customer-Journey-Prediction

# Install dependencies
pip install -r requirements.txt

# Open Jupyter Notebook
jupyter notebook customer_journey_prediction.ipynb
```
### What This Project Answers
Which customers are most valuable?
Who is likely to purchase again?
What factors influence customer spending?
How does customer engagement change over time?
