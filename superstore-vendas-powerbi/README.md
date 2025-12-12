📊 Projeto Power BI — Análise de Vendas (Superstore)
📌 Visão Geral

Este projeto tem como objetivo analisar o desempenho de vendas de uma empresa fictícia de varejo utilizando o dataset Sample Superstore, amplamente utilizado em projetos de Business Intelligence.

O foco está na construção de um dashboard interativo no Power BI, explorando indicadores de vendas, lucro, performance por região, categorias de produtos e comportamento ao longo do tempo.

🗂️ Base de Dados

Fonte: Kaggle — Tableau Sample Superstore

Link: https://www.kaggle.com/datasets/truongdai/tableau-sample-superstore

Formato: CSV

Período: Dados históricos de pedidos

Principais colunas

Order ID, Order Date, Ship Date

Customer ID, Customer Name, Segment

Product Name, Category, Sub-Category

Region, State, City

Sales, Profit, Quantity, Discount

🏗️ Modelagem de Dados

Foi aplicada uma modelagem dimensional (Star Schema) para melhor desempenho e clareza analítica:

🔹 Tabela Fato

Fato_Vendas

Sales

Profit

Quantity

Discount

Chaves de relacionamento (Data, Produto, Cliente, Região)

🔹 Tabelas Dimensão

Dim_Tempo (Order Date, Year, Month, Quarter)

Dim_Produto (Categoria, Subcategoria, Produto)

Dim_Cliente (Cliente, Segmento)

Dim_Região (Região, Estado, Cidade)

📐 Métricas Criadas (DAX)

Algumas medidas utilizadas no projeto:

Total de Vendas

Total de Lucro

Margem de Lucro (%)

Quantidade Vendida

Ticket Médio

Vendas YTD

Lucro YTD

Crescimento em relação ao período anterior

📊 Dashboards Desenvolvidos

O relatório é composto por múltiplas páginas, incluindo:

Visão Geral

KPIs principais

Evolução de vendas e lucro

Comparativos temporais

Análise por Produto

Performance por categoria e subcategoria

Produtos mais vendidos

Produtos com maior e menor lucro

Análise Geográfica

Vendas e lucro por região e estado

Comparação regional

Análise de Clientes

Segmentos

Clientes mais rentáveis

Distribuição de vendas por perfil

🎯 Objetivos do Projeto

Aplicar conceitos de Business Intelligence

Praticar modelagem dimensional

Desenvolver medidas DAX

Criar dashboards claros, interativos e orientados à tomada de decisão

Construir um projeto sólido para portfólio profissional

🛠️ Ferramentas Utilizadas

Power BI Desktop

Power Query

DAX

Kaggle

📌 Conclusões

O projeto permite identificar:

Regiões mais lucrativas

Categorias com melhor desempenho

Produtos com alto volume e baixa margem

Tendências de vendas ao longo do tempo

Essas análises apoiam decisões estratégicas relacionadas a mix de produtos, estratégia comercial e expansão regional.

📎 Observações

Este projeto é educacional e demonstrativo, utilizando dados públicos e fictícios, com foco em aprendizado e apresentação de habilidades em BI e análise de dados.
