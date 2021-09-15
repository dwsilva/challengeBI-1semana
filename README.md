# challengeBI-1semana

Dashboard de Logística

A pessoa que gerencia a área de logística da Alura Log, está enfrentando algumas mudanças em sua área por conta do aumento da demanda dos serviços de logística no período da pandemia. Ela quer manter a qualidade de seu serviço, mas para isso precisa acompanhar constantemente as métricas do seu departamento para tomar as melhores decisões. Quando nos contou isso, analisamos que para auxiliar nesse desafio precisaremos fazer um dashboard para logística. Para isso, vamos visualizar algumas métricas muito importantes para a área.

Base de Dados
A base de dados consiste em quatro arquivos .csv com a seguinte estrutura:

Tabela Pedidos

ID Pedido
ID Produto
Quantidade
ID Veículo
Status do pedido
Data da compra
Data de entrega
Data previsão
Latitude
Longitude
UF da entrega

Tabela Veículos

ID veículos
Tipo
Status

Tabela Estoque

ID Produto
Data atualização
Quantidade

Tabela Produtos

categoria_produto
preço

Ferramentas utilizadas

Foi utilizado somente o Power BI para desenvolver o Dashboard

Tratamento dos dados

Tabela Pedidos: Alterada tipagem dos dados; Transformada coluna “Data previsão” para o formato data.
Tabela Produtos: Alteração na tipagem dos dados; Segregação do ID e Categoria de modo a criar uma nova coluna com ID; Removido Sublinhado.
Tabela Estoque: Alterada tipagem dos dados; Ajustada coluna “Data atualização”.
Tabela Veículos: Alterada tipagem dos dados.

Métricas

Entregas no prazo;
Entregas atrasadas;
Quantidade de veículos disponíveis;
Quantidade de veículos atrasados;
S2D - Ship to door;
Índice de ocorrências por Estado;
Média de estoque por ano;
Entregas por Região.

Relacionamentos

Pedidos -- Produtos
Pedidos - Veículos
Produtos -- Estoque

Link do Dashboard

https://app.powerbi.com/view?r=eyJrIjoiZDdiZjQyMTktNjVkMC00YmYzLTliMmYtMWMxNDUxMzc2MmM5IiwidCI6IjA3Njg1MDA5LTg5NzAtNGFkNC05MmU1LTkzOWFhYTc1MGZmZCJ9
