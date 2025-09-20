📈 Tech Challenge - Modelos de Previsão Ibovespa

(English version below)

Este repositório reúne diferentes abordagens de modelagem para previsão do Ibovespa, incluindo um modelo Naive e alternativas como ARIMA e Prophet.

O objetivo é analisar dados históricos do índice e avaliar modelos de previsão em diferentes níveis de complexidade.

📂 Estrutura do Projeto


├── arima_prophet/                # Modelos ARIMA e Prophet

├── storytelling/                 # Documentação e relatórios

├── naive.ipynb                   # Notebook com modelo Naive

├── Dados_Históricos_Ibovespa.csv # Dataset principal

├── requirements.txt              # Dependências do projeto

├── README.md                     # Este arquivo

└── .gitignore                    # Arquivos a serem ignorados pelo Git


⚠️ Observação: existe também o arquivo Dados Históricos - Ibovespa (1) (1).csv, duplicado do dataset principal. Recomenda-se usar apenas Dados_Históricos_Ibovespa.csv.

🔧 Requisitos

Python 3.8 ou superior

pip (gerenciador de pacotes)

Recomenda-se o uso de virtualenv ou conda para isolar o ambiente.

⚙️ Configuração do Ambiente

Clone o repositório

git clone https://github.com/seu-repositorio.git
cd seu-repositorio


Crie e ative o ambiente virtual (opcional, mas recomendado)

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


Instale as dependências

pip install -r requirements.txt

▶️ Executando os Modelos

Modelo Naive

jupyter notebook naive.ipynb


Modelos ARIMA e Prophet

jupyter notebook arima_prophet/<nome-do-notebook>.ipynb


Storytelling / Relatórios
O diretório storytelling/ contém materiais de apoio e análises complementares.

📊 Resultados Esperados

Exploração de dados históricos do Ibovespa

Implementação e comparação de modelos preditivos (Naive, ARIMA, Prophet)

Avaliação de desempenho e visualização gráfica dos resultados

📌 Observações

Certifique-se de manter o dataset Dados_Históricos_Ibovespa.csv na raiz do projeto.

Caso prefira rodar em Google Colab, basta enviar os arquivos .ipynb e .csv.


📈 Tech Challenge - Ibovespa Forecasting Models

This repository contains different approaches for forecasting the Ibovespa index, including a simple Naive model and more advanced alternatives such as ARIMA and Prophet.

The goal is to analyze historical data and evaluate forecasting models with different levels of complexity.

📂 Project Structure

├── arima_prophet/                # ARIMA and Prophet models

├── storytelling/                 # Documentation and reports

├── naive.ipynb                   # Notebook with Naive model

├── Dados_Históricos_Ibovespa.csv # Main dataset

├── requirements.txt              # Project dependencies

|── README.md                     # This file

└── .gitignore                    # Files ignored by Git


⚠️ Note: there is also a file named Dados Históricos - Ibovespa (1) (1).csv, which is a duplicate of the main dataset. It is recommended to use only Dados_Históricos_Ibovespa.csv.

🔧 Requirements

Python 3.8 or higher

pip (package manager)

It is recommended to use virtualenv or conda for environment isolation.

⚙️ Environment Setup

Clone the repository

git clone https://github.com/your-repo.git
cd your-repo


Create and activate virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


Install dependencies

pip install -r requirements.txt

▶️ Running the Models

Naive Model

jupyter notebook naive.ipynb


ARIMA and Prophet Models

jupyter notebook arima_prophet/<notebook-name>.ipynb


Storytelling / Reports
The storytelling/ directory contains supporting material and additional analysis.

📊 Expected Results

Exploration of historical Ibovespa data

Implementation and comparison of forecasting models (Naive, ARIMA, Prophet)

Performance evaluation and graphical visualization of results

📌 Notes

Make sure the dataset Dados_Históricos_Ibovespa.csv is kept in the project root.

If you prefer running on Google Colab, simply upload the .ipynb and .csv files.
