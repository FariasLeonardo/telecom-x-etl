# 📞 Telecom X - Análise Estratégica de Churn

Este projeto consiste em um pipeline completo de **ETL (Extract, Transform, Load)** e **EDA (Exploratory Data Analysis)** focado na retenção de clientes para a empresa fictícia Telecom X. O objetivo principal foi identificar os fatores que levam à evasão de clientes (Churn) e fornecer subsídios para modelos preditivos de Data Science.

---

## 🚀 Estrutura do Projeto

O repositório está organizado da seguinte forma:

* `TelecomX_etl.ipynb`: Notebook principal com todo o desenvolvimento do código em Python.
* `TelecomX_Data.json`: Base de dados bruta utilizada na análise.
* `TelecomX_dicionario.md`: Documentação com a descrição de cada variável do dataset.

---

## 🛠️ Tecnologias e Ferramentas

* **Linguagem:** Python 3.x
* **Ambiente:** Google Colab
* **Bibliotecas Principais:** * `Pandas`: Manipulação e tratamento de dados.
    * `Seaborn` & `Matplotlib`: Visualização de dados e gráficos estatísticos.
    * `Requests`: Coleta de dados via API.
    * `Numpy`: Operações matemáticas e binarização.

---

## 📈 Desenvolvimento do Projeto (ETL & EDA)

### 1. Extração e Tratamento (ETL)
* **Normalização JSON:** Dados aninhados foram "explodidos" para transformar estruturas complexas em um DataFrame tabular.
* **Limpeza:** Conversão da coluna `Charges.Total` para float e tratamento de valores nulos e duplicados.
* **Feature Engineering:** Criação da métrica `Contas_Diarias` (faturamento mensal diluído em 30 dias).
* **Padronização:** Binarização de variáveis categóricas (Sim/Não para 1/0) e tradução das colunas para Português.

### 2. Análise Exploratória (EDA)
* **Distribuição de Churn:** Identificamos uma taxa de evasão de **25,8%**.
* **Análise Numérica:** Verificamos que clientes com faturas mais altas e menor tempo de contrato possuem maior propensão à saída.
* **Correlação:** Matriz de correlação indicando que a falta de serviços adicionais (Segurança/Suporte) aumenta o risco de churn.

---

## 🎯 Conclusões e Recomendações

* **Fidelização:** Clientes com contratos mensais são os mais voláteis; a recomendação é incentivar a migração para planos anuais.
* **Onboarding:** O foco de retenção deve ser nos primeiros 6 meses de contrato, onde ocorre o maior volume de desistências.
* **Stickiness:** Empacotar serviços de Suporte Técnico e Segurança Digital ajuda a criar barreiras de saída para o cliente.

---

## ⚙️ Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone [https://github.com/FariasLeonardo/telecom-x-churn-analysis.git](https://github.com/FariasLeonardo/telecom-x-churn-analysis.git)

---

### Autor 🧑‍💻

**Leonardo Farias Souza**  
[GitHub](https://github.com/FariasLeonardo) | [LinkedIn](https://www.linkedin.com/in/leonardo-farias-souza-265952320) | Email: nardofaris@hotmail.com  

---
