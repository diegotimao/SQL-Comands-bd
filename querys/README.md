# MySQL - Comands Banco de dados Relacional

Repósitorio destinado ao aramazenamento de queryes referentes ao banco de dados MySQL.

Para acessar deve-se entrar na pasta **/query** onde estão todos os arquivos.


*OBS:* Toda a parte de configuração deste projeto foi desenvolvido pela trybe.

## Query básicas

desafio1 - Exiba apenas os nomes dos produtos na tabela `products`.

---

desafio2 - Exiba os dados de todas as colunas da tabela `products`.

---

desafio3 - Escreva uma query que exiba os valores da coluna que representa a primary key da tabela `products`.

---

desafio4 - Conte quantos registros existem na coluna `product_name` da tabela `products`.

---

desafio5 - Monte uma query que exiba os dados da tabela `products` a partir do quarto registro até o décimo terceiro.

---

desafio6 - Exiba os dados das colunas `product_name` e `id` da tabela `products` de maneira que os resultados estejam em ordem alfabética dos nomes.

---

desafio7 - Mostre apenas os ids dos 5 últimos registros da tabela `products` (a ordernação deve ser baseada na coluna `id`).

---

desafio8 - Faça uma consulta que retorne três colunas, respectivamente, com os nomes 'A', 'Trybe' e 'eh', e com valores referentes a soma de '5 + 6', a string 'de', a soma de '2 + 8'.

## Filtragem de dados

desafio9 - Mostre todos os valores de `notes` da tabela `purchase_orders` que não são nulos.

---

desafio10 - Mostre todos os dados da tabela `purchase_orders` em ordem decrescente, ordenados por `created_by` em que o `created_by` é maior ou igual a 3.

---

desafio11 - Exiba os dados da coluna `notes` da tabela `purchase_orders` em que seu valor de `Purchase generated based on Order` é maior ou igual a 30 e menor ou igual a 39.

---

desafio12 - Mostre as `submitted_date` de `purchase_orders` em que a `submitted_date` é do dia 26 de abril de 2006.

---

desafio13 - Mostre o `supplier_id` das `purchase_orders` em que o `supplier_id` seja 1 ou 3.

---

desafio14 - Mostre os resultados da coluna `supplier_id` da tabela `purchase_orders` em que o `supplier_id` seja maior ou igual a 1 e menor ou igual 3.

---

desafio15 - Mostre somente as horas (sem os minutos e os segundos) da coluna `submitted_date` de todos registros da tabela `purchase_orders`.

---

desafio16 - Exiba a `submitted_date` das `purchase_orders` que estão entre `2006-01-26 00:00:00` e `2006-03-31 23:59:59`.

---

desafio17 - Mostre os registros das colunas `id` e `supplier_id` das `purchase_orders` em que os `supplier_id` sejam tanto 1, ou 3, ou 5, ou 7.

---

desafio18 - Mostre todos os registros de `purchase_orders` que tem o `supplier_id` igual a 3 e `status_id` igual a 2.

---

desafio19 - Mostre a quantidade de pedidos que foram feitos na tabela `orders` pelo `employee_id` igual a 5 ou 6, e que foram enviados através do método(coluna) `shipper_id` igual a 2.

---

## Manipulação de tabelas

desafio20 - Adicione à tabela `order_details` um registro com `order_id`: 69, `product_id`: 80, `quantity`: 15.0000, `unit_price`: 15.0000, `discount`: 0, `status_id`: 2, `date_allocated`: NULL, `purchase_order_id`: NULL e `inventory_id`: 129.

---

desafio21 - Adicione com um único `INSERT`, duas linhas à tabela `order_details` com os mesmos dados do requisito 20.

---

desafio22 - Atualize os dados de `discount` do `order_details` para 15. (Não é necessário utilizar o SAFE UPDATE em sua query).

---

desafio23 - Atualize os dados da coluna `discount` da tabela `order_details` para 30, onde o valor na coluna `unit_price` seja menor que 10.0000.

---

desafio24 - Atualize os dados da coluna `discount` da tabela `order_details` para 45, onde o valor na coluna `unit_price` seja maior que 10.0000 e o id seja um número entre 30 e 40.

---

desafio25 - Delete todos os dados em que a `unit_price` da tabela `order_details` seja menor que 10.0000.

---

desafio26 - Delete todos os dados em que a `unit_price` da tabela `order_details` seja maior que 10.0000.

---

desafio27 - Delete todos os dados da tabela `order_details`.

---