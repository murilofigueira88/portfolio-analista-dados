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


images/star schemma.png

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
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------


📊 Power BI Project — Sales Analysis (Superstore)
📌 Overview

This project aims to analyze the sales performance of a fictional retail company using the Sample Superstore dataset, a widely adopted dataset for Business Intelligence and data visualization projects.

The main goal is to build an interactive Power BI dashboard, focusing on sales, profit, product performance, regional analysis, and time-based trends to support data-driven decision-making.

🗂️ Dataset

Source: Kaggle — Tableau Sample Superstore

Link: https://www.kaggle.com/datasets/truongdai/tableau-sample-superstore

Format: CSV

Scope: Historical order data

Main columns

Order ID, Order Date, Ship Date

Customer ID, Customer Name, Segment

Product Name, Category, Sub-Category

Region, State, City

Sales, Profit, Quantity, Discount

🏗️ Data Modeling

A dimensional data model (Star Schema) was applied to improve performance and analytical clarity.

🔹 Fact Table

Fact_Sales

Sales

Profit

Quantity

Discount

Foreign keys (Date, Product, Customer, Region)

🔹 Dimension Tables

Dim_Date (Order Date, Year, Month, Quarter)

Dim_Product (Category, Sub-Category, Product)

Dim_Customer (Customer, Segment)

Dim_Region (Region, State, City)

📐 DAX Measures

Some of the key measures created in this project include:

Total Sales

Total Profit

Profit Margin (%)

Total Quantity Sold

Average Ticket Size

Sales YTD

Profit YTD

Period-over-Period Growth

📊 Dashboards Developed

The report consists of multiple pages, including:

Executive Overview

Main KPIs

Sales and profit trends

Time-based comparisons

Product Analysis

Performance by category and sub-category

Top-selling products

Most and least profitable products

Geographical Analysis

Sales and profit by region and state

Regional comparisons

Customer Analysis

Customer segments

Top customers by revenue and profit

Sales distribution by segment

🎯 Project Objectives

Apply Business Intelligence concepts

Practice dimensional modeling

Develop DAX measures

Build clear, interactive, and decision-oriented dashboards

Create a strong professional portfolio project

🛠️ Tools & Technologies

Power BI Desktop

Power Query

DAX

Kaggle

📌 Key Insights

The analysis enables the identification of:

The most profitable regions

Best-performing product categories

High-volume, low-margin products

Sales and profit trends over time

These insights support strategic decisions related to pricing, product mix, sales strategy, and regional expansion.
