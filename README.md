**Research Title: Unidirectional Models vs Stacked Models for Football Match Prediction**

**Overview**

This project aims to develop and evaluate predictive models for football
match outcomes, comparing the performance of unidirectional models (such
as LSTM and RNN) against stacked models (such as stacked LSTM and RNN).
The goal is to achieve the highest accuracy in predicting match goals
while also assessing the efficiency of these models in terms of training
time. By leveraging advanced deep learning techniques, this research
seeks to identify the most effective approach for football match
prediction.

**Project Structure**

1. Introduction
Overview of challenges in predicting football match outcomes.
Aim and objectives of the research.
Research question.

2. Literature Review
Examination of football match prediction using machine learning models.
Overview of recent studies in football match prediction.
Identification of the research gap.

3. Methodology
Justification for selecting LSTM and RNN models.
Detailed steps involved in data preprocessing, model training, and evaluation.
Consideration of ethical, legal, professional, and social issues.

4. Experiment
Application of unidirectional models and their performance metrics.
Application of stacked models and comparison with unidirectional models.

5. Discussion
Analysis of the performance of unidirectional vs stacked models.
Insights into the efficiency and accuracy of the models.

6. Conclusion
Summary of findings and conclusion on the superiority of stacked models.
Suggestions for future work.

**Requirements**
Programming Language: Python
Libraries Used:
TensorFlow/Keras for building and training neural network models.
Pandas for data manipulation.
Matplotlib and Seaborn for data visualization.
Scikit-learn for model evaluation metrics and data preprocessing.

**Dataset**
The dataset used in this project is sourced from (https://www.kaggle.com/code/saife245/football-match-prediction/input?select=final_dataset.csv)
 and consists of historical data from the English Premier League (EPL) spanning over twenty years. The data includes 
 match dates, teams, full-time scores, and various performance metrics.

**Features**

-   **Model Implementation**: Includes both unidirectional and stacked
    recurrent neural networks (RNNs) for prediction.

-   **Optimization**: Various optimizers such as Adam, RMSprop, and
    Adamax are tested to find the most effective one for each model.

-   **Evaluation Metrics**: Performance is measured using accuracy, R2
    score, MAE, MSE, and RMSE.

-   **Data Visualization**: Includes histograms, scatter plots, and
    heatmaps to analyze and visualize data trends and model performance.

**Key Findings**
Stacked LSTM models achieved the highest accuracy of 99.99%, outperforming unidirectional models in both prediction accuracy and training loss reduction.
Unidirectional models, while effective, were more prone to variations in performance depending on the optimizer and the number of epochs.
Stacked models demonstrated superior generalization capabilities and faster convergence during training.

**Future Work**
Developing models that can make real-time predictions using live match data, which could be 
valuable for in-game decision-making or betting applications.
Integrating additional features like real-time player statistics and environmental conditions.
Developing real-time prediction models for live match applications.

**Code and Documentation**
The full codebase, along with detailed comments and explanations, is available in the https://github.com/AkhilKumarMatala/21073209_Football_Prediction_Project directory. 
This includes data preprocessing, model implementation, and evaluation scripts.
