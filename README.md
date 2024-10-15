# SVM Machine Learning Project - Diabetes Diagnostic

## 1. Project Overview

This project implements a Support Vector Machine (SVM) model for classifying if a person has diabetes. SVM is a supervised learning algorithm used for classification and regression analysis. It aims to find the optimal hyperplane that maximizes the margin between different classes.

## 2. Features
- Data Preprocessing: Data cleaning, normalization, and splitting into training and testing sets.
- Model Training: Training an SVM model using scikit-learn.
- Model Evaluation: Evaluating the performance of the model using metrics such as accuracy, precision, recall, and F1-score.
- Visualization: Visualization of decision boundaries and model performance.

## 3. Project Structure
    ├── diabetes.csv                # Dataset files (if any)
    ├── diabetes_prediction.ipynb   # Jupyter notebook with end-to-end implementation
    ├── README.md                   # Project documentation
    ├── requirements.txt            # Python dependencies
    └── .gitignore                  # Files to be ignored in version control

## 4. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- numpy

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/diabetes_prediction.git
    cd diabete_svm
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook diabetes_prediction.ipynb
```
## 5. Usage

Open the diabetes_prediction.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- Data Loading and Preprocessing: Load data from data/ folder and perform necessary preprocessing.
- Model Training: Train an SVM model with adjustable hyperparameters.
- Model Evaluation: Evaluate the model using accuracy, precision, recall, and F1-score.
- Visualization: Visualize decision boundaries (if applicable) and performance metrics.

## 6. Results
| Metric    |  Value   |
|-----------|----------|
| Accuracy  |  77.2%   |
| Precision |  75.6%   |
| Recall    |  51.8%   |
| F1-Score  |  61.5%   |

## 7. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 8. License

This project is licensed under the MIT License - see the LICENSE file for details.







