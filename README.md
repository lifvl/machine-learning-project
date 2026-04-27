# machine-learning-project

# Car Evaluation using Machine Learning

## Overview

This project aims to build a Machine Learning model that evaluates the quality of cars based on their features such as price, safety, and passenger capacity.

---

## Objective

To predict the car acceptability class:

* Unacceptable (unacc)
* Acceptable (acc)
* Good (good)
* Very Good (vgood)

---

## Dataset

* Source: UCI Machine Learning Repository
* Dataset link: https://archive.ics.uci.edu/dataset/19/car+evaluation
* Number of rows: 1728
* Number of columns: 7

### Features:

* buying (buying price)
* maint (maintenance cost)
* doors (number of doors)
* persons (capacity in terms of persons)
* lug_boot (luggage boot size)
* safety (safety level)

### Target:

* class (car evaluation)

---

## Workflow

### 1. Data Loading

The dataset is loaded directly from the UCI repository using a URL.

### 2. Data Preprocessing

* All categorical features were converted into numerical values using Label Encoding.

### 3. Train/Test Split

* 80% training data
* 20% testing data

### 4. Model Building

The following models were trained and compared:

* Decision Tree
* Random Forest
* Logistic Regression

### 5. Evaluation

Models were evaluated using Accuracy Score.

---

## Results

Model performance:

* Decision Tree Accuracy: 0.97
* Random Forest Accuracy: 0.97
* Logistic Regression Accuracy: 0.66

Random Forest achieved the best performance among all models.

---

## Insights

* Safety is the most influential feature in determining car evaluation.
* The dataset is slightly imbalanced, with more "unacceptable" cars than others.

---

## Project Summary

### Use Case for Machine Learning

* **Difference:** Automates car evaluation with fast, consistent predictions instead of manual judgment.
* **Cost:** Low development cost, reduces ongoing manual effort.
* **Expertise:** Basic Python, data preprocessing, and ML knowledge.
* **Maintenance:** Minimal; retraining only when new data is available.

---

### ART Test

* **Availability:** Publicly available (UCI dataset).
* **Representativeness:** Covers multiple feature combinations.
* **Trust:** Reliable academic source.

---

### Data Overview

* **Quantity:** 1,728 records.
* **Quality:** Clean dataset, no missing values, slight class imbalance.

---

###  Features

* No new features engineered.
* Used Label Encoding for categorical variables.

---

###  Key Predictive Features

* Safety (most important)
* Persons (capacity)
* Buying price

---

###  Model Prediction & Decision

* Predicts: Unacceptable, Acceptable, Good, Very Good
* Used for decision-making:

  * Unacceptable → reject
  * Acceptable → normal listing
  * Good → recommend
  * Very Good → highlight

---

###  Model Metrics

* Decision Tree: 0.97
* Random Forest: 0.97 (best)
* Logistic Regression: 0.66

---

###  Success Criteria

* Accuracy ≥ 95%
* Good performance across all classes

###  Failure Criteria

* Accuracy < 90%
* Poor classification performance

---

## # machine-learning-project

# Car Evaluation using Machine Learning

## Overview

This project aims to build a Machine Learning model that evaluates the quality of cars based on their features such as price, safety, and passenger capacity.

---

## Objective

To predict the car acceptability class:

* Unacceptable (unacc)
* Acceptable (acc)
* Good (good)
* Very Good (vgood)

---

## Dataset

* Source: UCI Machine Learning Repository
* Dataset link: https://archive.ics.uci.edu/dataset/19/car+evaluation
* Number of rows: 1728
* Number of columns: 7

### Features:

* buying (buying price)
* maint (maintenance cost)
* doors (number of doors)
* persons (capacity in terms of persons)
* lug_boot (luggage boot size)
* safety (safety level)

### Target:

* class (car evaluation)

---

## Workflow

### 1. Data Loading

The dataset is loaded directly from the UCI repository using a URL.

### 2. Data Preprocessing

* All categorical features were converted into numerical values using Label Encoding.

### 3. Train/Test Split

* 80% training data
* 20% testing data

### 4. Model Building

The following models were trained and compared:

* Decision Tree
* Random Forest
* Logistic Regression

### 5. Evaluation

Models were evaluated using Accuracy Score.

---

## Results

Model performance:

* Decision Tree Accuracy: 0.97
* Random Forest Accuracy: 0.97
* Logistic Regression Accuracy: 0.66

Random Forest achieved the best performance among all models.

---

## Insights

* Safety is the most influential feature in determining car evaluation.
* The dataset is slightly imbalanced, with more "unacceptable" cars than others.

---

##  Project Summary

###  Use Case for Machine Learning

* **Difference:** Automates car evaluation with fast, consistent predictions instead of manual judgment.
* **Cost:** Low development cost, reduces ongoing manual effort.
* **Expertise:** Basic Python, data preprocessing, and ML knowledge.
* **Maintenance:** Minimal; retraining only when new data is available.

---

###  ART Test

* **Availability:** Publicly available (UCI dataset).
* **Representativeness:** Covers multiple feature combinations.
* **Trust:** Reliable academic source.

---

###  Data Overview

* **Quantity:** 1,728 records.
* **Quality:** Clean dataset, no missing values, slight class imbalance.

---

###  Features

* No new features engineered.
* Used Label Encoding for categorical variables.

---

###  Key Predictive Features

* Safety (most important)
* Persons (capacity)
* Buying price

---

###  Model Prediction & Decision

* Predicts: Unacceptable, Acceptable, Good, Very Good
* Used for decision-making:

  * Unacceptable → reject
  * Acceptable → normal listing
  * Good → recommend
  * Very Good → highlight

---

###  Model Metrics

* Decision Tree: 0.97
* Random Forest: 0.97 (best)
* Logistic Regression: 0.66

---

###  Success Criteria

* Accuracy ≥ 95%
* Good performance across all classes

###  Failure Criteria

* Accuracy < 90%
* Poor classification performance

---

##  How to Run

1. Install dependencies:

```bash
pip install pandas scikit-learn matplotlib seaborn jupyter
```

2. Open the project folder in VS Code.

3. Make sure you have the **Jupyter extension** installed.

4. Open the notebook file:

```
project.ipynb
```

5. Select a Python kernel and run all cells.

---

## Conclusion

The model successfully predicts car evaluation with high accuracy and can support decision-making in selecting cars.

---

## Future Work

* Use a more recent dataset
* Handle class imbalance
* Deploy the model as an API
 How to Run

1. Install dependencies:

```bash
pip install pandas scikit-learn matplotlib seaborn jupyter
```

2. Open the project folder in VS Code.

3. Make sure you have the **Jupyter extension** installed.

4. Open the notebook file:

```
project.ipynb
```

5. Select a Python kernel and run all cells.

---

## Conclusion

The model successfully predicts car evaluation with high accuracy and can support decision-making in selecting cars.

---

## Future Work

* Use a more recent dataset
* Handle class imbalance
* Deploy the model as an API