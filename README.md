# Banco de Dados - Comercial CADSPM LTDA

Este projeto é um banco de dados relacional criado para a empresa Comercial CADSPM LTDA. Ele foi desenvolvido com o objetivo de gerenciar clientes, funcionários, pedidos, produtos e os itens contidos em cada pedido.

## Entidades Principais

- **Cliente**: armazena os dados dos clientes.
- **Funcionario**: armazena os dados dos funcionários e seus cargos.
- **Produto**: registra os produtos e seus preços.
- **Pedido**: representa as compras feitas por clientes.
- **ItemPedido**: associa produtos aos pedidos com quantidade e subtotal.

## Relacionamentos

- Um cliente pode fazer vários pedidos.
- Um pedido pode ser atendido por vários funcionários.
- Cada pedido possui um ou mais itens.
- Cada item é referente a um produto.

## Regras de Negócio

- Todo pedido precisa estar ligado a um cliente.
- Cada itemPedido deve conter um produto e uma quantidade.
- O subtotal do item é calculado multiplicando o preço do produto pela quantidade.

## Consultas SQL

O projeto também contém várias consultas SQL organizadas por tipos:

- Filtros com `WHERE`
- Agrupamentos com `GROUP BY` e `ORDER BY`
- Operadores aritméticos e de comparação
- Operadores lógicos (`AND`, `OR`, `NOT`)
- Subconsultas
- `JOIN` entre tabelas (INNER, LEFT, RIGHT)
- Funções de data (`NOW()`, `YEAR()`)
- Funções de agregação (`SUM`, `AVG`, `MAX`)

Essas consultas demonstram como extrair e cruzar dados do banco de forma eficiente.

