# Atividade de IA / ML - Random Forest Regressor

Este repositório contém a entrega da atividade prática da disciplina de Inteligência Artificial / Machine Learning do curso de Ciência da Computação da PUC-SP. O objetivo do projeto é explorar o algoritmo **Random Forest** da biblioteca Scikit-Learn utilizando um conjunto de dados do pacote `vega_datasets`.

## 👥 Equipe
* Hélio Masaru Sueta
* Pedro Henrique Vianna Carvalho

## 📊 Sobre o Dataset (Wheat)
Para este trabalho, selecionamos o dataset **`wheat`** (Dados históricos de William Playfair sobre o preço do trigo e salários entre 1565 e 1820). 
Como o objetivo é prever o preço do trigo (uma variável contínua) com base no ano e no salário da época, utilizamos um modelo de **Regressão** (`RandomForestRegressor`).

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Python 3**
* **Scikit-Learn** (Construção do modelo, divisão de dados e métricas)
* **Pandas** (Manipulação e limpeza dos dados)
* **Vega Datasets** (Fonte de dados)
* **Google Colab / Jupyter Notebook** (Ambiente de desenvolvimento)

## ⚙️ Estrutura do Código (Pipeline)
1. **Importação e Carga:** Carregamento do dataset `wheat` via `vega_datasets`.
2. **Pré-processamento:** Tratamento de dados ausentes (remoção de valores nulos na coluna `wages`).
3. **Divisão:** Separação das *features* (Ano e Salário) e do *target* (Preço do Trigo) na proporção de 70% para treino e 30% para teste.
4. **Treinamento:** Criação e ajuste do modelo `RandomForestRegressor` com 100 estimadores.
5. **Avaliação:** Extração das métricas de erro para avaliar o desempenho do modelo (MAE, MSE e R²).

## 🚀 Como Executar
O código foi desenvolvido em um Jupyter Notebook. Para visualizá-lo ou executá-lo:
1. Abra o arquivo `PUCSP_CS_AI_11_AI_ML_RandomForest.ipynb` diretamente aqui no GitHub.
2. Para rodar o código, clique no botão **"Open in Colab"** (se configurado) ou baixe o arquivo e abra no seu ambiente Jupyter/Google Colab.
3. Execute as células sequencialmente. Certifique-se de que a biblioteca `vega_datasets` está instalada no seu ambiente (`!pip install vega_datasets`).
