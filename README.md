# Projeto Conceitual de Banco de Dados E-Commerce


## Descrição
Modelar um projeto conceitual de banco de dados E-commerce, a partir dos escopos Produto, Cliente, Estoque, Pedido, Fornecedor e Venda de Produtos.
O modelo será criado no MySQL WorkBench e disponibilizado em PNG.

## Requisitos
Produto:
1) Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros);
2) Cada produto possui um fornecedor;
3) Um ou mais produtos podem compor um pedido.

Cliente:
1) O cliente pode se cadastrar no site com seu CPF ou CNPJ;
2) O endereço do cliente irá determinar o valor do frete;
3) Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto.

Pedido:
1) Os pedidos são criados por clientes e possuem informações de compra, endereço e status de entrega;
2) Um produto ou mais compõem o pedido;
3) O pedido pode ser cancelado.

Fornecedor:
1) Achar melhor solução.

Estoque:
1) Achar melhor solução.


## Objetivo
Refine o modelo apresentado acrescentando os seguintes pontos:
1) Cliente PJ e PF: Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
2) Pagamento: Pode ter cadastrado mais de uma forma de pagamento;
3) Entrega: Possui status e código de rastreio;

---

## Autor
Eduardo Lucio
