# Heart Disease Prediction Project

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features and Workflow](#features-and-workflow)
3. [Technologies Used](#technologies-used)
4. [Results](#results)
5. [How to Run](#how-to-run)
6. [Dataset](#dataset)
7. [Acknowledgments](#acknowledgments)
8. [Future Improvements](#future-improvements)
9. [Conclusion](#conclusion)
10. [Contact](#contact)

## Project Overview
A heart attack (cardiovascular disease) occurs when the flow of blood to the heart muscle suddenly becomes blocked. According to the World Health Organization (WHO), approximately 17.9 million people die each year from heart attacks. Medical studies indicate that human lifestyle is a significant contributing factor to heart problems. Additionally, there are many key factors that can signal whether a person is at risk of experiencing a heart attack.

This project utilizes a dataset containing medical information about patients, aiming to predict whether an individual has a higher or lower risk of heart disease. Through data exploration, preprocessing, and applying various machine learning models, the goal is to classify the target variable and identify the most suitable algorithm for this dataset.

![Heart Disease Prediction Overview](Picture/heart-disease.webp)

## Features and Workflow
1. **Data Preprocessing:**
   - Handled missing values and imbalanced data.
   - Scaled and normalized features for better model performance.

2. **Exploratory Data Analysis (EDA):**
   - Explored relationships between features and heart disease.
   - Visualized data distributions using libraries like Matplotlib and Seaborn.

3. **Feature Engineering:**
   - Selected relevant features to improve model accuracy.
   - Engineered new features to capture important patterns in the data.

4. **Model Implementation:**
   - Tested various algorithms, including Logistic Regression, Decision Trees, Random Forest, SVM, and KNN.
   - Evaluated model performance using metrics like accuracy, precision, recall, F1 score, and AUC-ROC.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Torch, D-Tale, Sweetviz
  - **Sweetviz:** Generates interactive and beautiful data analysis visualizations, displayed in the default web browser.
  - **D-Tale:** Provides an interactive experience for exploring and analyzing data.
- **Platform:** Jupyter Notebook

## Results
- The best-performing model achieved high accuracy and strong AUC-ROC scores, demonstrating its effectiveness in predicting heart disease.
- Visualizations and metrics are included in the project to highlight the models' performance.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Rich-kaM/.git
   ```
2. Navigate to the project folder:
   ```bash
   cd heart-disease-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Run the notebook step by step to see data preprocessing, EDA, and model results.
6. For Sweetviz visualizations, ensure a default web browser is available to display the reports automatically after execution.

## Dataset
The dataset used for this project can be found on [Kaggle](https://www.kaggle.com/datasets/dileep070/heart-disease-prediction-using-logistic-regression?resource=download). Ensure you download the dataset and place it in the appropriate folder before running the notebook.

## Acknowledgments
- Kaggle for providing the dataset.
- Open-source libraries and tools for enabling seamless development.

## Future Improvements
- Integrate the model into a web-based interface for real-time predictions.
- Explore advanced algorithms like neural networks for improved accuracy.

## Conclusion
This project highlights the potential of machine learning in predicting heart disease risks based on patient data. Key takeaways include:
1. Best-Performing Model: Extreme Gradient Boosting (XGBoost) delivered the highest accuracy among the machine learning models evaluated, proving to be the most effective for this dataset.
2. Key Risk Factors: Features such as exercise-induced angina and chest pain were identified as significant indicators of heart attack risk, aligning with medical research.
3. Impact of Ensembling Techniques: Ensembling methods, like Random Forest and XGBoost, demonstrated enhanced accuracy compared to standalone algorithms, underscoring the value of combining models.
4. Technology-Driven Insights: The project highlights the importance of leveraging machine learning and data analysis tools to aid in early detection and risk assessment of heart disease.
5. Practical Applications: The results can assist healthcare professionals by providing predictive insights, potentially improving patient outcomes through early interventions.
6. Future Scope: Incorporating advanced algorithms like deep learning and integrating real-time data can further enhance predictive capabilities.

These findings emphasize the importance of data-driven approaches in healthcare, aiding early detection and prevention of heart-related diseases.

## Contact
For questions or feedback, please reach out to me at:
- **Email:** [richardmukulu73@gmail.com](mailto:richardmukulu73@gmail.com)
- **GitHub:** [My GitHub Profile](https://github.com/Rich-kaM)
