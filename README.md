# Sonar: Mines vs. Rocks Prediction

This project implements a logistic regression model to classify sonar signals as either originating from a mine ("M") or a rock ("R"). The dataset used is the Connectionist Bench (Sonar, Mines vs. Rocks) dataset from Kaggle.

## Dataset

The dataset contains 208 instances, each with 60 numerical features representing the energy of the sonar signal at different frequencies, and a target variable indicating whether the object is a mine or a rock.

The dataset was loaded from the file `sonar.csv`.

## Model

A logistic regression model from the `sklearn.linear_model` library was used for classification.

## Results

The model achieved the following accuracy scores:

- Training data accuracy: 83.42%
- Testing data accuracy: 76.19%

## How to run the code

1. Clone the repository to your local machine.
2. Ensure you have the necessary libraries installed (pandas, numpy, seaborn, scikit-learn).
3. Download the `sonar.csv` dataset and place it in the same directory as the notebook.
4. Run the notebook cells sequentially to load the data, train the model, and evaluate its performance.

## Project Structure

- `sonar.csv`: The dataset file.
- `notebook.ipynb`: The Jupyter notebook containing the code for data loading, model training, and evaluation.

## Acknowledgments

- The Connectionist Bench (Sonar, Mines vs. Rocks) dataset is available on Kaggle.
