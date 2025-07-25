# 📊 Projeto de Análise de Churn - Telecom X

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python" alt="Badge Python">
  <img src="https://img.shields.io/badge/Libraries-Pandas%20%7C%20Seaborn-red?style=for-the-badge" alt="Badge Bibliotecas">
</p>

## 🎯 1. Propósito da Análise

Este projeto realiza uma análise exploratória sobre uma base de dados da Telecom X, uma empresa fictícia de telecomunicações. O principal objetivo é investigar o churn de clientes, ou seja, a taxa de cancelamento de serviços.

A análise busca identificar os principais fatores e perfis de clientes que influenciam a decisão de cancelamento, com o intuito de gerar insights que possam ser utilizados para desenvolver estratégias de retenção mais eficazes.


## 📈 2. Principais Gráficos e Insights

A análise revelou padrões importantes sobre o comportamento dos clientes e os motivos que levam ao cancelamento.

Principais Insights:

💡 Taxa de Churn Geral: A taxa de cancelamento geral da base de clientes é de 26.54%, um número considerável que justifica uma investigação aprofundada.

💡 Tipo de Contrato é Crucial: Clientes com contrato Mês a Mês têm uma taxa de churn altíssima. A segurança de contratos de 1 ou 2 anos é um fator de retenção poderoso.

💡 Impacto do Serviço de Internet: O tipo de serviço de internet é um dos fatores mais influentes na taxa de churn. Clientes com Fibra Óptica apresentam uma taxa de cancelamento de 41.89%, significativamente maior que a dos clientes com DSL (18.96%).

💡 Lealdade vs. Tempo de Contrato (Tenure): A probabilidade de um cliente cancelar é muito maior no início de seu contrato. A taxa de churn para clientes com menos de 12 meses é altíssima, enquanto clientes com mais de 5 anos de casa raramente cancelam.

Gráficos de Exemplo

#### Taxa de Churn por Tipo de Contrato
Este gráfico mostra que contratos mensais são muito mais voláteis, enquanto contratos de longo prazo garantem a permanência do cliente.
<img width="600" alt="Gráfico de Churn por Tipo de Contrato" src="https://github.com/user-attachments/assets/627e591e-134b-4cfa-bbc3-b9747bdf4c0c" />

#### Taxa de Churn por Serviço de Internet
O gráfico abaixo ilustra a disparidade na taxa de churn entre os diferentes tipos de serviço de internet, destacando a vulnerabilidade dos clientes de Fibra Óptica.
<img width="600" alt="churn_por_internet" src="https://github.com/user-attachments/assets/0e660747-87c1-4bd9-8fb3-640812e2eb3a" />

#### Taxa de Churn por Tempo de Contrato (Tenure)
Este gráfico demonstra a forte correlação negativa entre o tempo de contrato e a taxa de churn. Clientes mais antigos são significativamente mais leais.
<img width="600" height="400" alt="churn_por_tenure_hist" src="https://github.com/user-attachments/assets/6104e6f0-eef2-4663-b497-4247ffa31054" />



## 🚀 3. Como Executar o Projeto

Para replicar esta análise, siga os passos abaixo.

Pré-requisitos

- Python 3.9 ou superior
- Jupyter Notebook ou qualquer outra IDE que suporte notebooks (.ipynb)

## Instalação de Bibliotecas

1. Abra seu terminal ou prompt de comando e instale as bibliotecas necessárias executando o seguinte comando:

pip install pandas requests matplotlib seaborn jupyter

2. Execução

Clone o repositório ou baixe os arquivos para o seu computador.

git clone (https://github.com/lilian-retori/Analise_evasao_clientes.git)

cd seu-repositorio

3. Abra o Jupyter Notebook: Navegue até a pasta do projeto pelo terminal e execute o comando:

jupyter notebook

4. Execute o Notebook: No seu navegador, clique no arquivo analise_churn.ipynb e execute as células de código em ordem, de cima para baixo.

## ✍️ 4. Autor
Análise realizada por: [Lilian Retori]
