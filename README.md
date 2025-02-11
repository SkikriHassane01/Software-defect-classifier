# Software Defect Classifier

## Project Overview
This project is designed to classify software defects using machine learning techniques. It leverages various data manipulation, visualization, and model tuning libraries to provide accurate predictions and insights into software reliability.

## Requirements
This project depends on the following libraries:
- **numpy**
- **pandas**
- **scikit-learn**
- **matplotlib**
- **seaborn**
- **autofeatselect**: Automatically selects the best features for your model.
- **lazypredict**: Quickly compares baseline performance of multiple machine learning models.
- **lightgbm**: A fast, high-performance gradient boosting framework.

In addition, refer to the `requirements.txt` file for version-specific dependencies.

## Setup and Installation
1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   ```
2. **Navigate to the project directory:**
   ```sh
   cd Software-defect-classifier
   ```
3. **Install the required libraries:**
   ```sh
   pip install -r requirements.txt
   ```
4. **Set the runtime if needed:**
   Refer to the `runtime.txt` file for runtime configuration.

## Troubleshooting
- **Installation Issues:**
  Ensure your Python version matches the one specified in `runtime.txt`.
- **Dependency Conflicts:**
  Consider using a virtual environment.
- **Performance:**
  If the model training is slow, verify that your machine has sufficient resources, and consider tuning model parameters or reducing dataset size.
- **General:**
  In case of unexpected errors, review the configuration files and check for any missing dependencies in `requirements.txt`.

## Conclusion 
In this project we acheaved an accuracy of 0.79321 using the LightGBM model. This model is fast and efficient, making it ideal for large datasets. We also used LazyPredict to compare the performance of multiple models and select the best one. Finally, we used AutoFeatSelect to automatically select the best features for our model, reducing thes need for manual feature engineering.