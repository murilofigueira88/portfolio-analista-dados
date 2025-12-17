📈 Projeto Power BI — Análise Temporal de Vendas (Superstore)

## 📌 Visão Geral

Este projeto tem como objetivo realizar uma **análise temporal aprofundada** do desempenho de vendas de uma empresa fictícia de varejo, utilizando o dataset **Sample Superstore**.

Diferente de uma visão executiva tradicional, o foco aqui está em **comparações ao longo do tempo**, identificando crescimento, variações percentuais e padrões sazonais que apoiam a tomada de decisão estratégica.

---

## 🗂️ Base de Dados

- **Fonte:** Kaggle — Tableau Sample Superstore  
- **Link:** https://www.kaggle.com/datasets/truongdai/tableau-sample-superstore  
- **Formato:** CSV  
- **Período:** Dados históricos de pedidos  

### Principais colunas
- Order ID, Order Date, Ship Date  
- Customer ID, Segment  
- Product Name, Category, Sub-Category  
- Region, State, City  
- Sales, Profit, Quantity, Discount  

---

## 🏗️ Modelagem de Dados

Foi aplicada uma **modelagem dimensional (Star Schema)**, garantindo melhor desempenho analítico e clareza nas análises temporais.

- Uma tabela fato central de vendas
- Dimensões de Tempo, Produto, Cliente e Região
- Tabela exclusiva para medidas DAX

*(Imagem do modelo em estrela será adicionada após a finalização do modelo)*

---

## 📐 Métricas Criadas (DAX)

O projeto utiliza medidas focadas em **análise de crescimento e comparação temporal**, como:

- Total Sales  
- Total Profit  
- Sales LY (Last

