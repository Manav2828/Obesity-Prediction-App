# Obesity Prediction App

A Machine Learning Model to predict Obesity in people. This project uses RandomForestClassifier Model to train on a given dataset. Interactive GUI is developed using PyQt6.

The dataset used is from https://www.kaggle.com/datasets/muhramasaputra/obesity-based-on-eating-habits-and-physical-cond

The file **description.txt** contains description of each and every variable in dataset.

The file **testApp.py** has the code for traiining dataset using RandomForestClassifier. It also contains the code data preprocessing, visualization, feature selection and model training.

# Installation

## Usage

- Download this git repository or clone it to your system using following command:

```
git clone
```

- Create a Virual enviroment

```
python -m venv venv
source venv/bin/activate 
# on windows: venv\Scripts\activate.bat
```

- Install required python packages from [requirements.txt](requirements.txt) file using following command:

```
pip install -r requirements.txt
```

- Double click and run [main.py](main.py) file to use the prediction model.
