# 🛒 Análise de Vendas em Supermercado

Este projeto explora um conjunto de dados fictício de um **supermercado de varejo**, com transações realizadas ao longo de 2023. Cada linha representa uma compra, com informações sobre cliente, categoria de produto, quantidade, preço e valor total da venda.

## 🎯 Objetivo

- Investigar o desempenho de vendas por **categoria de produto** (Beauty, Clothing, Electronics).  
- Entender o perfil dos clientes a partir de variáveis como **idade** e **gênero**.  
- Identificar quais combinações de quantidade e preço mais contribuem para o faturamento.

## 🧹 Estrutura da base

O dataset contém, entre outras, as seguintes colunas:  
- `Transaction ID`: identificador único de cada compra.  
- `Date`: data da transação ao longo de 2023.  
- `Customer ID`, `Gender`, `Age`: informações básicas do cliente.  
- `Product Category`: categoria do item comprado.  
- `Quantity`, `Price per Unit`, `Total Amount`: detalhes de volume e valor da venda.

## 📊 Análises realizadas (sugestão)

- Cálculo de **faturamento total** e ticket médio por transação.  
- Comparação de vendas entre categorias, medindo quantidade vendida e receita por categoria.  
- Distribuição de clientes por faixa etária e gênero, avaliando quais perfis compram mais.  
- Análise temporal simples (por mês ou trimestre) para verificar sazonalidade nas vendas.

## 🧠 Potenciais insights

Este tipo de análise ajuda a responder perguntas como:  
- Qual categoria é a mais importante em termos de receita do supermercado?  
- Qual grupo de idade é mais valioso para o negócio?  
- Existem períodos do ano em que alguma categoria dispara em vendas?  

O projeto é ideal para praticar **pandas, groupby, métricas de negócio e visualizações simples** focadas em varejo/supermercado.