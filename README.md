# Análise e Visualização de Dados de Vendas em Shoppings de Istambul

Este projeto realiza uma análise aprofundada de um conjunto de dados de vendas de shoppings em Istambul. O objetivo é extrair insights valiosos sobre o comportamento de compra dos clientes, padrões de vendas e características demográficas, utilizando bibliotecas populares de ciência de dados e visualização em Python.

---

## Dataset

O projeto utiliza o arquivo `customer_shopping_data.csv`, que contém informações detalhadas sobre as transações de compra, incluindo:
* **invoice_no**: Número da fatura
* **customer_id**: ID do cliente
* **gender**: Gênero do cliente
* **age**: Idade do cliente
* **category**: Categoria do produto comprado
* **quantity**: Quantidade de itens
* **price**: Preço total da compra
* **payment_method**: Método de pagamento
* **invoice_date**: Data da compra
* **shopping_mall**: Shopping onde a compra foi realizada

---

## Ferramentas e Bibliotecas

As seguintes bibliotecas foram utilizadas para a análise e visualização dos dados:
* `pandas`
* `zipfile`
* `io`
* `matplotlib.pyplot`
* `seaborn`
* `folium`
* `scipy.stats`

---

## Análise e Visualização

O notebook apresenta uma série de análises e visualizações, incluindo:
* **Estrutura do Dataset**: Verificação inicial da estrutura do dataframe.
* **Análise Descritiva**: Sumário estatístico das variáveis.
* **Visualizações**: Gráficos de barras, histogramas, boxplots e até mesmo um mapa interativo para mostrar a localização dos shoppings e o volume de vendas.
* **Insights Chave**: Identificação das categorias de produtos mais vendidas, shoppings com maior volume de vendas, e a distribuição de clientes por gênero e idade.

---

## Resumo

O projeto conclui que a **categoria de Roupas (Clothing) é a mais popular**, gerando um volume significativo de vendas e receita. O método de pagamento mais utilizado é o **Cartão de Crédito**, sendo responsável pela maior parte da receita. A análise também mostra que os shoppings **Mall of Istanbul e Kanyon** são os que apresentam o maior número de transações.
