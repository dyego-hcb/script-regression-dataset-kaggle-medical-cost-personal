# Machine Learning Regression: Previsão de Custos de Plano de Saúde

Este repositório contém um projeto de Machine Learning desenvolvido para prever os custos de planos de saúde com base em um conjunto de dados disponível em [Kaggle](https://www.kaggle.com/mirichoi0218/insurance).

## Objetivo

O objetivo deste projeto é utilizar algoritmos de regressão para prever os custos de planos de saúde com base em diferentes características dos segurados.

## Conjunto de Dados

O conjunto de dados utilizado neste projeto contém informações sobre:

- Idade do segurado
- Gênero
- IMC (Índice de Massa Corporal)
- Número de filhos/dependentes cobertos pelo plano
- Se o segurado é fumante ou não
- Região dos Estados Unidos onde o segurado reside
- Custo do seguro de saúde para o segurado

## Algoritmos Utilizados

Foram implementados os seguintes algoritmos de regressão:

1. Regressão Linear Simples
2. Regressão Linear Múltipla
3. Regressão Polinomial
4. SVR (Support Vector Regression)
5. Árvore de Decisão
6. Random Forest
7. XGBoost
8. LightGBM
9. CatBoost

## Resultados

Após a implementação e avaliação dos algoritmos, o melhor desempenho foi obtido com o algoritmo de regressão com LightGBM, apresentando um R^2 de 0.86/0.89 e um RMSE de 4093.63.

## Pastas

- `script`: Diretorio contendo o código do projeto.
- `dataset`: Diretorio contendo o conjunto de dados utilizado no projeto.
- `output`: Diretorio contendo os dados independentes do conjunto de dados, dados dependentes (custos de planos de saúde) do conjunto de dados.

***

# Machine Learning Regression: Health Insurance Cost Prediction

This repository contains a Machine Learning project developed to predict health insurance costs based on a dataset available on [Kaggle](https://www.kaggle.com/mirichoi0218/insurance).

## Objective

The objective of this project is to use regression algorithms to predict health insurance costs based on different characteristics of policyholders.

## Dataset

The dataset used in this project contains information about:

- Age of the insured
- Gender
- BMI (Body Mass Index)
- Number of children/dependents covered by the plan
- Whether the insured is a smoker or not
- Region of the United States where the insured resides
- Cost of health insurance for the insured

## Algorithms Used

The following regression algorithms have been implemented:

1. Simple Linear Regression
2. Multiple Linear Regression
3. Polynomial Regression
4. SVR (Support Vector Regression)
5. Decision Tree
6. Random Forest
7. XGBoost
8. LightGBM
9. CatBoost

## Results

After implementing and evaluating the algorithms, the best performance was achieved with the LightGBM regression algorithm, with an R^2 of 0.86/0.89 and an RMSE of 4093.63.

## Folders

- `script`: Directory containing the project code.
- `dataset`: Directory containing the dataset used in the project.
- `output`: Directory containing the independent data from the dataset, and dependent data (health insurance costs) from the dataset.
