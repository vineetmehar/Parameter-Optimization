# SVM Optimization on Dry Bean Dataset

This project demonstrates the optimization of Support Vector Machine (SVM) on the Dry Bean dataset obtained from the UCI Machine Learning Repository. The dataset contains instances of seven different varieties of dry beans, with 16 features describing each instance.

## Dataset

The Dry Bean dataset consists of 13611 instances, with each instance having 16 features. The dataset is divided into 10 different samples for training and testing.

## Implementation

1. **Loading the Dataset**: The dataset is loaded from a CSV file using the pandas library.

2. **Splitting the Dataset**: The dataset is split into training and testing sets with a 70-30 ratio, repeated 10 times to get 10 different samples.

3. **Optimizing SVM**: SVM is optimized for each sample using cross-validation with 100 iterations. GridSearchCV is used to find the best hyperparameters.

4. **Recording Results**: The best parameters and accuracies are recorded for each sample. The sample with maximum accuracy is identified.

   ![image](https://github.com/praneykalra16/Parameter_Optimisation/assets/100370893/690f90a9-9a19-44c2-81a4-c48b7448891d)


5. **Convergence Graph**: A convergence graph is plotted for the sample with the maximum accuracy, showing how the training and testing accuracies change over iterations during the optimization process.

   ![image](https://github.com/praneykalra16/Parameter_Optimisation/assets/100370893/1cd06976-55ad-418d-8235-34a87bc30957)


## Files Included

- `dry_bean_data.csv`: CSV file containing the Dry Bean dataset.
- `parameter_optimization.ipynb`: Jupyter Notebook containing the Python code for the project.
- `README.md`: This README file providing an overview of the project.

## Requirements

- Python 3.x
- Required libraries: pandas, scikit-learn, matplotlib

## Acknowledgments

- UCI Machine Learning Repository for providing the Dry Bean dataset.
- Scikit-learn and pandas libraries for their functionalities in data preprocessing and machine learning.
