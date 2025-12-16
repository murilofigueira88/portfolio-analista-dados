📊 Projeto Power BI — Análise de Vendas (Superstore)
📌 Visão Geral

Este projeto tem como objetivo analisar o desempenho de vendas de uma empresa fictícia de varejo utilizando o dataset Sample Superstore, amplamente utilizado em estudos e projetos de Business Intelligence.

O foco do projeto é a construção de um dashboard interativo no Power BI, explorando indicadores de vendas, lucro, desempenho por região, categorias de produtos e comportamento ao longo do tempo, aplicando boas práticas de modelagem dimensional e DAX.

🗂️ Base de Dados

Fonte: Kaggle — Tableau Sample Superstore

Link: https://www.kaggle.com/datasets/truongdai/tableau-sample-superstore

Formato: CSV

Período: Dados históricos de pedidos de vendas

Principais colunas

Order ID, Order Date, Ship Date

Customer ID, Customer Name, Segment

Product Name, Category, Sub-Category

Region, State, City

Sales, Profit, Quantity, Discount

🏗️ Modelagem de Dados

Foi aplicada uma modelagem dimensional (Star Schema) visando melhor desempenho, organização e clareza analítica.

🔹 Tabela Fato

Fato_Vendas

Sales

Profit

Quantity

Discount

Chaves de relacionamento: Tempo, Produto, Cliente e Região

🔹 Tabelas Dimensão

Dim_Tempo (Ano, Mês, Ano-Mês, Trimestre, Data)

Dim_Produto (Categoria, Subcategoria, Produto)

Dim_Cliente (Cliente, Segmento)

Dim_Região (Região – valores únicos)

Dim_Vendedor (Gerente Regional, Região)

As medidas foram organizadas em uma tabela dedicada (Medidas), seguindo boas práticas no Power BI.

📐 Métricas Criadas (DAX)

Algumas das principais medidas desenvolvidas:

Total Sales

Total Profit

Profit Margin (%)

Total Orders

Quantity Sold

Average Ticket

Indicadores acumulados (YTD)

Análises temporais e comparativas

📊 Dashboards Desenvolvidos

O relatório contém páginas analíticas, incluindo:

🔹 Visão Geral

KPIs principais (Vendas, Pedidos, Ticket Médio)

Evolução de vendas e lucro ao longo do tempo (com drill-down)

Análise de vendas por categoria

Análise de vendas por região

🔹 Análises Complementares

Performance por categoria e subcategoria

Comparação regional

Análise por segmento de clientes

🎯 Objetivos do Projeto

Aplicar conceitos de Business Intelligence

Praticar modelagem dimensional (Star Schema)

Desenvolver medidas em DAX

Criar dashboards claros, interativos e orientados à tomada de decisão

Construir um projeto sólido para portfólio profissional

🛠️ Ferramentas Utilizadas

Power BI Desktop

Power Query

DAX

Kaggle

📌 Conclusões

O dashboard permite identificar, de forma clara:

Regiões com maior volume de vendas

Categorias mais relevantes para o negócio

Diferenças de desempenho entre segmentos de clientes

Tendências de vendas ao longo do tempo

Essas análises apoiam decisões estratégicas relacionadas a mix de produtos, estratégia comercial e expansão regional.

📎 Observações

Este projeto é educacional e demonstrativo, utilizando dados públicos e fictícios, com foco em aprendizado, prática de BI e apresentação de habilidades analíticas
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
