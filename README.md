
#  Final Project: EduPredi - Academic Prediction System

EduPredi (Educational Prediction System) is a comprehensive web-based system designed to analyze educational data and predict student performance utilizing advanced machine learning techniques, built as a Final Graduation Project.

---

##  Project Overview

### Problem Statement
The core challenge addressed is the need for a reliable and user-friendly system capable of predicting student performance early. This prediction assists educators in adapting their teaching methods to meet individual student needs more effectively.

### Key Objectives
1.  Develop a robust web application for processing educational data.
2.  Implement efficient Machine Learning models (Decision Trees and Linear Regression) to predict student outcomes based on historical data.
3.  Provide an intuitive user interface that facilitates data upload, feature selection, and immediate prediction results.

---

##  Key Features

* **Comprehensive Analysis:** The system employs three distinct Machine Learning algorithms (ID3, C4.5, and Linear Regression) to provide a thorough analysis of student performance across different data types.
* **Flexible Data Handling:** Users can easily upload student data files in the standard **CSV** format.
* **Model Customization:** The system allows users to explicitly select the features (variables) that will be used to train and run the prediction model.
* **User-Friendly Interface:** Built with **Django templates**, the interface ensures ease of use for educators, students, and parents.

---

##  Technologies Used

The project is built on a high-level Python framework, leveraging powerful data science and ML libraries:

* **Web Framework:** **Django**
* **Programming Language:** **Python**.
* **Data Manipulation:** **Pandas**.
* **Machine Learning:** **Scikit-Learn**.
* **Core Prediction Algorithms:**
    * Decision Tree **ID3** (Optimized for categorical data).
    * Decision Tree **C4.5** (Effective for handling mixed categorical and numerical data).
    * **Linear Regression** (For predicting continuous, numerical outcomes).
* **Database:** **SQLite**.

---

##  Model Performance Results (On Training Dataset)

The models were benchmarked on a training dataset of 400 student records. The key performance indicators are summarized below:

| Model | Performance Metric | Result | Notes |
| :--- | :--- | :--- | :--- |
| **Decision Tree C4.5** | Accuracy | **79.75%** | Highest accuracy among the decision tree models, superior for mixed data. |
| **Linear Regression** | R-squared (Coefficient of Determination) | **0.78** | Indicates that 78% of the variability in the outcome variable is explained by the model. |
| **Decision Tree ID3** | Accuracy | **55.7%** | Provides clear, interpretable rules but is less suited for the complexity of the dataset. |

---

##  Proposed Future Work

To enhance and extend the capabilities of the EduPredi system:

* **Advanced Modeling:** Integrate **Deep Learning** and Neural Network architectures.
* **Ensemble Learning:** Implement methods like **Random Forests** and Gradient Boosting.
* **Database Scalability:** Migrate the data backend to a more robust RDBMS such as **PostgreSQL** or **MySQL**.
* **Feature Expansion:** Develop a module for **Batch Predictions**.
* **Mobile Access:** Create a dedicated mobile application.

---

##  Full Project Access and Contact

** Note:** This repository serves as a **display-only** portfolio of the project's documentation, methodology, and results.

The **complete source code** and necessary setup files are maintained privately due to academic requirements. Access to the full project files, including the implementation code, may be granted upon request for academic review or professional inquiry only.

* **Developed by:** Meaad Farag Bayuosef
* **To Request Full Access:** Please contact me directly to discuss your interest in viewing the full project implementation.
```
