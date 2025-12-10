# Titanic EDA

Exploratory Data Analysis of Kaggle Titanic dataset.

## Run
python -m venv .venv

# activate...
pip install -r requirements.txt
jupyter notebook notebooks/titanic_eda.ipynb

# Key Findings
    •	Overall survival rate = 38.38%
	•	Females and 1st class passengers had higher survival rates
	•	Traveling alone reduced survival probability
	•	Children had comparatively higher survival rates

## Repository  Strucute

titanic-eda/
├── data/                       # Titanic dataset (from Kaggle)
│   └── train.csv
├── notebooks/                  # Jupyter notebooks
│   └── titanic_eda.ipynb       # Main EDA notebook
├── README.md                   # Project documentation
├── requirements.txt            # Python dependencies
└── .gitignore                  # Files/folders ignored by Git
