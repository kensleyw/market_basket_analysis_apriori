# Dataset de supermercado para regras de associação

O conjunto de dados de comportamento do consumidor de supermercado consiste em 2.019.501 linhas e 12 colunas:
* **order_id** (Um número exclusivo para identificar o pedido)
* **user_id** - (Um número exclusivo para identificar o usuário)
* **order_number** (Número do pedido)
* **order_dow** (Dia da semana em que o pedido foi feito)
* **order_hour_of_day** (Hora do pedido)
* **dias_since_prior_order** (Histórico do pedido)
* **product_id** (Id do produto)
* **add_to_cart_order** (Número de itens adicionados ao carrinho)
* **reordenado** (se o novo pedido ocorreu)
* **departamental_id** (Número exclusivo alocado para cada departamento)
* **departament** (Nomes dos departamentos)
* **product_name** (Nome dos produtos)

**Fonte dos dados:**
O conjunto de dados consiste em mais de 2 milhões de registros de compras em um renomado supermercado Hunter :)

https://www.kaggle.com/datasets/hunter0007/ecommerce-dataset-for-predictive-marketing-2023/data

## Explicação do algorítimo Apriori
Suponha que temos a regra de associação
{Pão} →{Manteiga} com um suporte de **0.1**, uma confiança de **0.6** e um lift de **1.5**.

**Suporte** (Pão): 10% das transações contêm pão.

**Confiança** (Pão → Manteiga): 60% das transações que contêm pão também contêm manteiga.

**Lift** (Pão → Manteiga): A probabilidade de comprar pão e manteiga juntos é 1.5 vezes maior do que se fossem comprados independentemente.

Portanto, ao comprar pão, há uma probabilidade de 60% de que manteiga também seja comprada, e essa probabilidade é 1.5 vezes maior do que se pão e manteiga fossem comprados independentemente. Isso ajuda a identificar associações interessantes nos dados de transações.

