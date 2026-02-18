# DesafioAluraTeleconXpart2

![Status](https://img.shields.io/badge/Status-Concluído-green) ![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![Lib](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)

## 🎯 Objetivo do Projeto
Este projeto tem como missão desenvolver um **pipeline de Machine Learning** completo para prever o **Churn** (evasão de clientes) numa empresa de telecomunicações.

O objetivo estratégico é identificar antecipadamente os clientes com maior probabilidade de cancelamento, permitindo que a empresa tome ações preventivas de retenção, reduzindo prejuízos e aumentando a fidelidade.

## 🛠️ Tecnologias Utilizadas
O projeto foi desenvolvido em **Python**, utilizando as seguintes bibliotecas:

* **Pandas & NumPy:** Manipulação e limpeza de dados.
* **Seaborn & Matplotlib:** Visualização de dados (EDA).
* **Scikit-Learn:** Construção dos modelos, pré-processamento e avaliação.
* **Imbalanced-Learn (SMOTE):** Técnica de balanceamento de classes.

## 📂 Estrutura do Pipeline
O desenvolvimento seguiu uma metodologia rigorosa de Ciência de Dados:

1.  **Limpeza de Dados:** Remoção de IDs, conversão de tipos (objetos para numéricos) e tratamento de nulos.
2.  **Análise Exploratória (EDA):** Estudo de correlações e visualização de padrões (ex: Clientes com contratos mensais tendem a evadir mais).
3.  **Pré-processamento:**
    * *One-Hot Encoding* para variáveis categóricas.
    * *SMOTE* (Synthetic Minority Over-sampling Technique) para corrigir o desbalanceamento de classes no treino.
    * *StandardScaler* para normalização de dados em modelos sensíveis à escala.
4.  **Modelagem:** Treinamento de dois algoritmos distintos:
    * **Regressão Logística:** Modelo linear, útil para interpretar coeficientes de risco.
    * **Random Forest:** Modelo de ensemble (árvores de decisão), robusto e de alta performance.
5.  **Avaliação:** Análise focada não apenas na Acurácia, mas principalmente no **Recall** (capacidade de detectar quem vai cancelar) e na Matriz de Confusão.

## 📊 Resultados e Insights

A análise indicou que incentivar a migração para contratos de longo prazo é a estratégia mais eficaz para retenção.

## ✒️ Autor

**Gabriel Mendes**
* [LinkedIn](https://www.linkedin.com/in/gabrielvmendes-dev/)
---
*Este projeto foi desenvolvido como desafio final do curso de Ciencia de dados da Oracle Next Education (ONE) em parceria com a ALURA.*
