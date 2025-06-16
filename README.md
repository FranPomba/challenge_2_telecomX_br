# 📉 Telecom X – Análise de Evasão de Clientes (Churn)

Este repositório contém o projeto desenvolvido como parte do desafio da formação **Alura ONE – Data Science**, no módulo **“Aprendendo a Fazer ETL”**.

O objetivo principal é apoiar a empresa fictícia **Telecom X**, que enfrenta um alto índice de cancelamentos, identificando os fatores que levam os clientes à evasão (churn). Esta análise é o primeiro passo para que a equipe de Data Science avance com modelos preditivos e estratégias de retenção.

## 📌 Objetivos do Desafio

✅ Importar e manipular dados de uma API ou arquivo `.json`.  
✅ Aplicar os conceitos de **ETL (Extração, Transformação e Carga)**.  
✅ Criar visualizações estratégicas para descobrir padrões e tendências.  
✅ Realizar uma **Análise Exploratória de Dados (EDA)**.  
✅ Gerar um relatório com **insights valiosos para o negócio**.

---

## 📦 Tecnologias Utilizadas

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook

---



## 🔧 ETL: Extração, Transformação e Carga

- **Extração:** Os dados foram importados de um arquivo `.json`.
- **Transformação:**
  - Conversão de colunas como `TotalCharges` para `float`.
  - Normalização de variáveis categóricas (`Churn`, `gender`).
  - Remoção de valores ausentes.
  - Criação da variável derivada `Contas_Diarias = Charges_Monthly / 30`.
- **Carga:** Dados prontos para análise e uso em futuros modelos preditivos.

---

## 📊 Análise Exploratória de Dados (EDA)

As análises incluíram:

- Distribuição geral do churn.
- Comparação entre clientes que saíram e que permaneceram.
- Evasão por gênero, tipo de contrato, método de pagamento, idade, etc.
- Relação entre tempo de contrato (`tenure`), gastos mensais e totais com a evasão.
- Estatísticas descritivas (média, mediana, desvio padrão...).

**Exemplo de Insight:**  
📌 Clientes com contratos mensais representam **mais de 42%** dos cancelamentos, enquanto clientes com contratos de dois anos têm evasão abaixo de **3%**.

---

## 📸 Visualizações

As visualizações incluem gráficos de:

- Barras
- Pizza
- Dispersão
- Barras empilhadas
- Boxplot

---