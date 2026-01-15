# **📊 Telecom X – Análise de Evasão de Clientes (Churn)**
### 📌 **Introdução**

Este projeto foi desenvolvido como parte do desafio “Telecom X – Análise de Evasão de Clientes”, cujo objetivo é compreender os fatores que levam ao cancelamento de clientes (Churn) em uma empresa de telecomunicações.

A partir da análise exploratória dos dados, buscamos gerar insights estratégicos que possam apoiar decisões de negócio e servir de base para a construção de modelos preditivos voltados à retenção de clientes.

### 🎯 Objetivo da Análise

Identificar padrões e comportamentos associados à evasão de clientes

Analisar variáveis demográficas, contratuais e de serviços

Gerar insights que apoiem estratégias de retenção

Preparar os dados para etapas futuras de modelagem preditiva

## 🧰 Tecnologias e Bibliotecas Utilizadas


![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-orange?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?logo=matplotlib)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

## 📂 Estrutura do Projeto

**README.md**: Arquivo com a explicação do projeto, objetivos da análise e instruções básicas de uso

**TelecomX_Data.json**: Base de dados original utilizada no desafio

**TelecomX_dicionario.md**: Dicionário de dados com a descrição de cada coluna.
 
**Solucao_TelecomX_NayaraBueno.ipynb**: Notebook com todo o passo a passo do projeto, incluindo:
	- Importação dos dados
	- Limpeza e tratamento
	- Análise exploratória
	- Criação de gráficos e insights

**📌 Observação:**
Todo o trabalho foi desenvolvido dentro do notebook, que contém explicações em texto e código para facilitar o entendimento do processo de análise.

## 🔄 Etapas do Projeto

**1️⃣ Coleta e Preparação dos Dados**

Leitura de dados em formato JSON

Normalização de estruturas aninhadas

Padronização de colunas

Conversão de tipos de dados

Tratamento de valores ausentes

**2️⃣ Análise Exploratória de Dados (EDA)**

Análise da distribuição do Churn

Comparações por perfil do cliente

Avaliação de contratos, serviços e formas de pagamento

Análise de tempo de contrato e valores cobrados

**3️⃣ Visualizações Estratégicas**

Foram criados gráficos para facilitar a identificação de padrões, como:

Gráficos de barras comparando Churn por variáveis categóricas

Distribuição de clientes por tipo de contrato

Comparação de evasão por serviços contratados

Análise de variáveis numéricas associadas ao Churn

### 📊 Exemplos de Insights Obtidos

Clientes com contrato mensal (Month-to-month) apresentam maior taxa de evasão

Clientes com menor tempo de permanência cancelam mais

Valores mensais elevados, sem serviços adicionais, aumentam o risco de Churn

Serviços como suporte técnico e segurança online atuam como fatores de retenção

Forma de pagamento influencia o comportamento de cancelamento

### 🚀 Como Executar o Projeto
Google Colab

Faça o upload do notebook e do arquivo TelecomX_Data.json, abra o notebook no Google Colab e execute as células em ordem.
