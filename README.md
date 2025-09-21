📈 Tech Challenge - Ibovespa Forecasting Models
-------

This repository contains different approaches for forecasting the Ibovespa index, including a simple Naive model and more advanced alternatives such as ARIMA and Prophet.

The goal is to analyze historical data and evaluate forecasting models with different levels of complexity.

📂 Project Structure
-------

├ arima_prophet/                # ARIMA and Prophet models

├ storytelling/                 # Documentation and reports

├ naive.ipynb                   # Notebook with Naive model

├ Dados_Históricos_Ibovespa.csv # Main dataset

├ requirements.txt              # Project dependencies

├ README.md                     # This file

└── .gitignore                    # Files ignored by Git


⚠️ Note: there is also a file named Dados Históricos - Ibovespa (1) (1).csv, which is a duplicate of the main dataset. It is recommended to use only Dados_Históricos_Ibovespa.csv.

🔧 Requirements
-------

Python 3.8 or higher

pip (package manager)

It is recommended to use virtualenv or conda for environment isolation.

⚙️ Environment Setup
-------

Clone the repository
```bash
git clone https://github.com/your-repo.git
cd your-repo
```

Create and activate virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```


Install dependencies

```bash
pip install -r requirements.txt
```

▶️ Running the Models
------

Naive Model

jupyter notebook naive.ipynb


ARIMA and Prophet Models

jupyter notebook arima_prophet/<notebook-name>.ipynb


Storytelling / Reports
The storytelling/ directory contains supporting material and additional analysis.

📊 Expected Results
-------

Exploration of historical Ibovespa data

Implementation and comparison of forecasting models (Naive, ARIMA, Prophet)

Performance evaluation and graphical visualization of results

📌 Notes
--------

Make sure the dataset Dados_Históricos_Ibovespa.csv is kept in the project root.

If you prefer running on Google Colab, simply upload the .ipynb and .csv files.
