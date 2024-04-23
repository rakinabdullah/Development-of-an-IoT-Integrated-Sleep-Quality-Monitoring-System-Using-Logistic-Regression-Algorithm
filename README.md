# Project Overview

In this project, I developed an innovative array of machine learning models (Logistic Regression, Support Vector Machine, Artificial Neural Network, and Random Forest) on Sleep Quality Data. The aim was to leverage machine learning techniques to analyze various sleep-related metrics and categorize sleep quality to provide personalized insights.

The following key steps and visualizations are implemented:

## Dataset Preparation

- Two separate datasets were utilized for this project.
- The datasets were merged into one comprehensive CSV file.
- Relevant feature engineering techniques were applied to enhance the dataset's informativeness.

### Dataset Links:

- __[Dataset 1 : Sleep Efficiency Dataset](https://www.kaggle.com/datasets/equilibriumm/sleep-efficiency)__
- __[Dataset 2 : Sleep Health and Lifestyle Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)__

## Data Preprocessing

- Load the sleep dataset from the CSV file.
- Define weights for each feature to calculate sleep quality scores.
- Rescale and categorize sleep quality scores.
    
## Data Exploration

The dataset containing sleep-related features such as age, gender, sleep duration, sleep efficiency, and more is loaded and explored.

### Visual Insights:

- Gender distribution pie chart
- Average sleep duration by gender pie chart
- Age distribution histogram
- Histogram of sleep duration
- Scatter plot of age vs. sleep duration colored by gender
- Distribution of sleep quality scores histogram
- Distribution of sleep quality categories bar chart
- Sleep quality score distribution by category box plot
- Sleep efficiency distribution histogram
- Scatter plot of sleep duration vs. sleep efficiency colored by sleep quality category
- Violin plot of sleep efficiency distribution by sleep quality category
- Correlation heatmap of numerical features
- Cross-tabulation heatmap of categorical features

## Feature Engineering

### Enhancing Feature Representation:

- Calculate sleep quality scores based on defined weighted numerical features.
- Rescale sleep quality scores to a standardized range.
- Categorize sleep quality scores into five categories: Very Poor, Poor, Average, Good, and Excellent.

## Model Development

### Logistic Regression Modeling:

- Logistic Regression model is trained and optimized using grid search and cross-validation.

### Support Vector Machine (SVM) Modeling:

- SVM model is trained and optimized using grid search and cross-validation.

### Artificial Neural Network (ANN) Modeling:

- ANN model is trained and optimized using grid search and cross-validation.

### Random Forest Classifier Modeling:

- Random Forest Classifier model is trained and optimized using grid search and cross-validation.

## Model Evaluation

### Performance Assessment:

- Evaluate model accuracy, precision, recall, and F1-score through classification reports.
- Assess model performance using confusion matrices.
- Analyze cross-validation scores to ensure model robustness.

## Confusion Matrix Visualization:

- A detailed confusion matrix is visualized for each model's performance assessment.

## Conclusion

### Innovation and Collaboration:

- I focused on refining the IoT-integrated sleep quality monitoring system., integrating various machine learning models for accurate sleep quality categorization.

### Future Prospects:

- The project lays the groundwork for future advancements in IoT-based healthcare applications and personalized sleep monitoring systems, enabling individuals to better understand and improve their sleep quality.
