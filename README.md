# Alura---Challenge-III
Repositório do Challenge Alura Telecom- Alura ONE
# Telecom X - Análise de Evasão de Clientes (Churn)

Este projeto faz parte do **Desafio de Data Science - Programa ONE**.  
O objetivo é aplicar técnicas de **ETL (Extração, Transformação e Carga)** e **EDA (Análise Exploratória de Dados)** para compreender os fatores que levam clientes da **Telecom X** a cancelarem seus serviços (**churn**).

---

# Propósito da Análise

A empresa Telecom X vem sofrendo com **alto índice de evasão de clientes**, mas não sabe exatamente quais fatores explicam esse comportamento.  
Com esta análise, buscamos:

- Realizar **ETL** para preparar os dados provenientes da API (GitHub).  
- Explorar os dados tratados, identificando **padrões e tendências**.  
- Obter **insights práticos** que ajudem a equipe de Data Science a reduzir a taxa de churn.  

---

## 📂 Estrutura do Projeto

```bash
.
├── data/                  # Dados brutos e tratados
│   ├── TelecomX_Data.json # Base original do GitHub
│   └── telecomx_tratado.csv # Base já limpa e tratada
│
├── notebooks/             
│   └── TelecomX_ETL_EDA.ipynb # Notebook principal com ETL + análise
│
├── reports/               
│   └── TelecomX_Relatorio.pdf # Relatório final com conclusões e gráficos
│
├── README.md              # Este arquivo
