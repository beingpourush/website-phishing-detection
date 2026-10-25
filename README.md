# Website Phishing Detection Using Machine Learning

## About the Project

This project focuses on detecting phishing websites using Machine Learning classification algorithms. It uses website-related features to classify websites into two categories based on the labels provided in the dataset.

The project is implemented using Python and Scikit-learn in a Jupyter Notebook / Google Colab environment.

## Machine Learning Algorithms

The following algorithms are explored in this project:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Multi-Layer Perceptron (MLP)

## Dataset

- **Number of samples:** 11,054
- **Number of input features:** 30
- **Target classes:** -1 and 1

The exact meaning of each class should be confirmed from the original dataset documentation.

**Dataset Source:** Add the original dataset URL here.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Google Colab

## Project Workflow

1. Load and inspect the dataset.
2. Separate input features and target labels.
3. Split the data into training and testing sets.
4. Train multiple Machine Learning classification models.
5. Evaluate and compare model performance.
6. Visualize the confusion matrix and feature importance.
7. Save the trained model for future use.

## How to Run

### Option 1: Google Colab

1. Download or clone this repository.
2. Open the `.ipynb` notebook in Google Colab.
3. Upload the dataset file `phishing.csv` to the Colab environment.
4. Update the dataset path if required.
5. Run the notebook cells in order.

### Option 2: Run Locally

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib joblib jupyter
```

Open the notebook using Jupyter Notebook or JupyterLab and ensure the dataset path is configured correctly.

## Evaluation Metrics

The models can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Actual evaluation results should be added after running the notebook.

## Limitations

- The current notebook works with precomputed dataset features.
- Live URL prediction requires a compatible and validated URL feature extraction pipeline.
- Results on the supplied dataset do not guarantee accurate detection of new phishing websites.

## Disclaimer

This project is intended for educational purposes only. Its predictions should not be treated as a guarantee that a website is safe or malicious.
