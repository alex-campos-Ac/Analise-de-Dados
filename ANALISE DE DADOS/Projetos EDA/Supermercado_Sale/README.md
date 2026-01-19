# 🧾 Análise de Vendas de Supermercado

Este projeto utiliza o clássico dataset **Supermarket Sales**, com registros de compras realizadas em três filiais de um supermercado, incluindo informações de clientes, produtos, valores e avaliações de atendimento.

## 🎯 Objetivo

- Entender o desempenho de vendas por **filial**, **linha de produto** e **tipo de cliente**.  
- Analisar métricas financeiras como **faturamento**, **custo**, **impostos** e **lucro (gross income)**.  
- Relacionar **métodos de pagamento** e **avaliações de satisfação (Rating)** com o comportamento de compra.

## 🧹 Estrutura da base

Principais colunas do dataset:
- `Branch`, `City`: identificação da loja e da cidade.  
- `Customer type`, `Gender`: perfil básico do cliente.  
- `Product line`: categoria de produto adquirida.  
- `Unit price`, `Quantity`, `Tax 5%`, `Total`, `cogs`, `gross income`: detalhes financeiros de cada venda.  
- `Date`, `Time`: data e horário da transação.  
- `Payment`: forma de pagamento utilizada.  
- `Rating`: nota dada pelo cliente ao atendimento.

## 📊 Análises realizadas (sugestão)

- Comparação de vendas entre **filiais** (faturamento total, ticket médio, lucro).  
- Desempenho das **linhas de produto**, identificando quais geram mais receita e melhor margem.  
- Distribuição de **métodos de pagamento** e seu impacto em volume de vendas e receita.  
- Exploração de **Rating** por filial e por linha de produto, avaliando a satisfação do cliente.

## 🧠 Possíveis insights

Com esse projeto é possível responder perguntas como:  
- Qual filial é mais lucrativa e qual tem melhor avaliação dos clientes?  
- Quais linhas de produto são “campeãs” de faturamento e quais precisam de atenção?  
- Há preferência clara por algum método de pagamento em cada loja?  

Projeto que trabalha **pandas, agregações, métricas de negócio e visualizações** em um cenário próximo à realidade de varejo físico.
