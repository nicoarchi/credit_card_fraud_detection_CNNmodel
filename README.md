# Credit Card Fraud Detection

Use Convolutional Neural Network with Tensorflow 2.0 to recognize fraudulent credit card transactions based in a Kaggle dataset.

[Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)

## Methodology
The deep learning model was developed using Tensorflow-gpu 2.0 in a Jupyter Notebook environment.

The target was to recognize whether or not there was fraud in credit card transactions.

The dataset did not contain missing values, but was highly unbalanced.

#### Steps:
- 1- Installing and importing of packages
- 2- Balance dataset
- 3- Set X features and y target.
- 4- Split into training and validation data.
- 5- Standardize features using StandardScaler
- 6- Reshape into 3dimensional dataframes
- 7- Build CNN models
- 8- Evaluate the model

Three CNN models were developed, the last one was the one with the best performance.

#### Final metrics
##### Accuracy:
- Accuracy: 0.9174
- Validation accuracy: 0.9188
##### Loss:
- Loss: 0.2516
- Validation loss: 0.2361