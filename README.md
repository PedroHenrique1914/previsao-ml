# Descrição do projeto
O objetivo deste projeto consiste em criar modelos de machine learning que sejam capazes prever os clientes que irão se desligar do banco com base nas informações fornecidas.

Para isso, utilizei 4 algoritmos para criar modelos distintos e comparar suas taxas de precisão. Os algoritmos utlizados foram Naive Bayes, Random Forest, Árvore de Decisão e Regressão Logística.
Tendo em vista que o tratamento da base de dados é uma etapa fundamental antes da implementação de qualquer modelo ou análise, me dediquei inicialmente em preparar os dados de maneira adequada, para só depois realizar análises exploratórias mais aprofundadas e implementar os modelos preditivos.
# Explicação da base de dados
  - customer_id: identificador exclusivo para cada cliente.
  - vintage: A duração do relacionamento do cliente com a empresa.
  - age: Idade do cliente.
  - gender: gênero do cliente.
  - dependents: Número de dependentes que o cliente possui.
  - occupation: A ocupação do cliente.
  - city: Cidade em que o cliente está localizado.
  - customer_nw_category: categoria de patrimônio líquido do cliente.
  - branch_code: Código que identifica a agência associada ao cliente.
  - current_balance: Saldo atual na conta do cliente.
  - previous_month_end_balance: Saldo da conta no final do mês anterior.
  - average_monthly_balance_prevQ: Saldo médio mensal do trimestre anterior.
  - average_monthly_balance_prevQ2: Saldo médio mensal no segundo trimestre anterior.
  - current_month_credit: valor do crédito no mês atual.
  - previous_month_credit: Valor do crédito no mês anterior.
  - current_month_debit: valor do débito no mês atual.
  - previous_month_debit: valor do débito no mês anterior.
  - current_month_balance: Saldo da conta no mês atual.
  - previous_month_balance: Saldo da conta no mês anterior.
  - churn: a variável de destino que indica se o cliente abandonou (1 para desligamento, 0 para não desligamento).
  - last_transaction: carimbo de data/hora da última transação do cliente.

A base de dados se encontra disponível em: [https://www.kaggle.com/datasets/pentakrishnakishore/bank-customer-churn-data/data]
