# High Entropy Alloys Phase Prediction

Welcome to the High Entropy Alloys Phase Prediction repository! This project explores the use of thermodynamic parameters and machine learning techniques to predict phases in high entropy alloys (HEAs). The analysis includes factors such as atomic size difference, entropy and enthalpy of mixing, free energy change, and atomic radii.

## Project Overview

The primary goal of this project is to develop a predictive model that can accurately determine the phases of various HEA compositions. The workflow in the Jupyter notebook `Explo.ipynb` includes the following key steps:

1. **Data Preprocessing**: Preparing the data by scaling and transforming the input features to ensure they are suitable for analysis.
2. **Dimensionality Reduction**: Reducing the feature space using Principal Component Analysis (PCA) to simplify the dataset while retaining essential information.
3. **Model Training**: Applying different machine learning models such as Logistic Regression, Decision Trees, Random Forest, and XGBoost to predict the phases of HEAs.
4. **Model Evaluation**: Evaluating the performance of the models using accuracy scores and generating classification reports to understand the precision, recall, F1-score, and support for each class.
5. **Hyperparameter Tuning**: Optimizing the parameters of the machine learning models using Grid Search CV to improve their accuracy and performance.

## Key Metrics

- **Accuracy Score**: Measures how often the model correctly predicts the phases of HEAs.
- **Classification Report**: Provides detailed metrics including precision, recall, F1-score, and support for each predicted class.

## Conclusion

Our metallurgical exploratory project has demonstrated the effectiveness of using thermodynamic parameters and machine learning techniques to predict phases in high entropy alloys. This approach not only enhances our understanding of phase behavior in complex alloy systems but also provides valuable insights for tailored alloy design. As we continue to refine and expand upon this methodology, the potential for transformative advancements in materials science remains promising.
