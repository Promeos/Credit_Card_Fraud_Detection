# Credit Card Fraud Detection Project

This is a data science project that aims to predict fraudulent credit card transactions using machine learning techniques. The dataset used in this project contains transactions made by European cardholders in September 2013. The dataset is highly imbalanced, with only 0.172% of transactions being fraudulent. Therefore, we use the Area Under the Precision-Recall Curve (AUPRC) metric to evaluate the performance of our models.

# Dataset

The dataset used in this project can be downloaded from Kaggle. It contains a total of 284,807 transactions, with 492 frauds. The dataset contains only numerical input variables, which have been transformed using PCA to ensure confidentiality. The only non-transformed features are 'Time' and 'Amount'.
Requirements

To run this project, you will need the following libraries:

    NumPy
    Pandas
    Matplotlib
    Scikit-learn

You can install them using the following command:

pip install numpy pandas matplotlib scikit-learn

# Workflow

The project is organized into the following steps:

    Data exploration and preprocessing
    Model selection and evaluation
    Handling class imbalance
    Model interpretation and feature importance

Each step is described in detail in the Jupyter Notebook files included in this repository.

# License

This project is licensed under the MIT License. See the LICENSE file for details.

# Acknowledgments

We would like to thank Kaggle and the ULB Machine Learning Group for providing the dataset used in this project.

# Conclusion
