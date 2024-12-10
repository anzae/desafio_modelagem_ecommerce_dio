# Desafio DIO - Modelagem de banco de dados para um ecommerce

## Descrição

O desafio consiste na modelagem de um banco de dados relacional para um ecommerce fictício com as regras de negócio apresentadas na narrativa. A modelagem foi feita utilizando MySQL Workbench.

## Narrativa

### Modelo de negócio
- Os produtos são vendidos por uma única plataforma online, por vendedores distintos (terceiros)
- Cada produto possui um ou mais fornecedores
- Os pedidos são compostos por um ou mais produtos

### Cliente

- O cliente pode se cadastrar com CPF ou CNPJ
- O endereço determina o valor do frete
- Um cliente pode comprar mais de um pedido

### Pedido

- O pedido é criado por cliente e possui informações de compra, endereço, status de entrega
- Um produto ou mais compõe o pedido
- O pedido pode ser cancelado
