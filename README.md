# Taxi Fare Prediction

We shall explore a past Kaggle Playground competition called the New York City Taxi Fare Prediction. A subset of the original dataset has been taken from DataCamp to reduce the data size. The dataset is located in the data directory.

The aim of the competition is to predict the fare amount of a taxi ride in New York City using the given information about the number of passengers, the pickup and drop off locations, etc. The evaluation metric for this competition is the root mean-squared error (RMSE). In this project, we perform the following tasks:

* Data preprocessing
* Feature engineering
* Selecting base-models and tuning their hyperparameters
* Creating a stacked ensemble model
* Evaluating the performance of the stacked model using RMSE metric.

## Installation

* **Python**

Install Python 3.9 or higher. Create a virtual environment with:

```
python3 -m venv <virtual-environment-name>
```

Example: To create a virtual environment called `ML-project`, use

```
python3 -m venv ML-project
```

Activate the virtual environment with:
```
source <path-to-virtual-environment>/bin/activate
```

The virtual environment can be deactivated with:
```
deactivate
```

* **Jupyter Notebook**

Install Jupyter Notebook with:
```
pip install notebook
```
To run the notebook:
```
jupyter notebook
```
* **Additional Requirements**

Install the necessary packages listed in `requirements.txt` via:
```
pip install -r requirements.txt
```