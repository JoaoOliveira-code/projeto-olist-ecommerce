# Análise de Dados do E-commerce Olist

## 1. Visão Geral do Projeto

Este projeto consiste em uma Análise Exploratoria de Dados (EDA) realizada sobre um conjunto de dados públicos de e-commerce da empresa Olist, a maior loja de departamentos do mercado brasileiro. O objetivo é extrair insights de negócio a partir de mais de 100.000 pedidos realizados entre 2016 e 2018,

## 2. Fonte dos Dados

Os dados foram obtidos através da plataforma Kaggle e representam uma versão anonimizada de informações sobre clientes, pedidos, produtos, pagamentos e avaliações.
* **Link para o Dataset:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## 3. Perguntas de Negócio Respondidas

Durante a análise, busquei responder ás seguintes perguntas de negócio:

* De quais estados vêm a maioria dos nossos clientes?
* Qual é o comportamento das vendas ao longo do tempo? Existe sazonalidade?
* Quais dias da semana concentram o maior número de compras?
* Quais as formas de pagamento mais utilizadas pelos clientes?
* Quais são as categorias de produtos mais vendidas?

## 4. Ferramentas e Bibliotecas Utilizadas

* **Linguagem:** Python
* **Bibliotecas:** Pandas (para manipulação de dados), Matplotlib e Seaborn (para visualização de dados).
* **Ambiente:** Jupyter Notebook 

## 5. Principais Insights Gerados

* **Perfil dos Clientes:** A grande maioria das vendas está concentrada no estado de São Paulo (SP), indicando ser o principal mercado da empresa.
* **Sazonalidade:** O final do ano, especialmente o mês de Novembro (provavelmente devido à Black Friday), representa o pico de vendas anual.
* **Padrão Semanal:** As Segundas-feiras são o dia com maior volume de pedidos, sugerindo que as decisões de compra são tomadas durante o fim de semana.
* **Pagamentos:** O Cartão de Crédito é o método de pagamento preferido, utilizado em mais de 75% das transações, seguido pelo Boleto.
* **Produtos:** A categoria "Cama, Mesa e Banho" é a líder de vendas, caracterizando a Olist como uma forte varejista de produtos para o lar.

## 6. Próximos Passos

Como próximo passos, seria interessante aprofundar a análise de satisfação do cliente (usando o dataset de reviews) ou criar um modelo de Machine Learning para prever o tempo de entrega dos pedidos.