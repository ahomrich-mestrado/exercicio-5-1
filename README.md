# Exercício 5.1 — SQL por prompt

Repositório do exercício 5.1 do curso IDP.

## Autor
Augusto Homrich

## Descrição
Escrever prompts em português que um LLM traduz em consultas SQL
sobre a base de dados do W3Schools (tabelas `Products` e `Customers`).

## Prompts

**Tarefa 1 — SELECT + WHERE**
> Na tabela Products, retorne as colunas ProductName e Price apenas das linhas em que CategoryID é igual a 1

**Tarefa 2 — COUNT**
> Na tabela Customers, conte quantas linhas têm Country igual a 'France'

**Tarefa 3 — SUM**
> Na tabela Products, some a coluna Price considerando apenas as linhas em que CategoryID é igual a 1

**Tarefa 4 — GROUP BY**
> Na tabela Customers, retorne o Country e a contagem de clientes agrupando por Country

**Tarefa 5 — GROUP BY + SUM**
> Na tabela Products, retorne o CategoryID e a soma de Price agrupando por CategoryID
