# Challenge BI - 1ª semana

<H1>Dashboard de Logística</H1>

A pessoa que gerencia a área de logística da Alura Log, está enfrentando algumas mudanças em sua área por conta do aumento da demanda dos serviços de logística no período da pandemia. Ela quer manter a qualidade de seu serviço, mas para isso precisa acompanhar constantemente as métricas do seu departamento para tomar as melhores decisões. Quando nos contou isso, analisamos que para auxiliar nesse desafio precisaremos fazer um dashboard para logística. Para isso, vamos visualizar algumas métricas muito importantes para a área.

<h2>Base de Dados</h2>

A base de dados consiste em quatro arquivos .csv com a seguinte estrutura:


<h3>Tabela Pedidos</h3>
<ul>
  <li>ID Pedido</li>
  <li>ID Produto</li>
  <li>Quantidade</li>
  <li>ID Veículo</li>
  <li>Status do pedido</li>
  <li>Data da compra</li>
  <li>Data de entrega</li>
  <li>Data previsão</li>
  <li>Latitude</li>
  <li>Longitude</li>
  <li>UF da entrega</li>
</ul>

<h3>Tabela Veículos</h3>
<ul>
  <li>ID veículos</li>
  <li>Tipo</li>
  <li>Status</li>
</ul>
  
<h3>Tabela Estoque</h3>
<ul>
<li>ID Produto</li>
<li>Data atualização</li>
<li>Quantidade</li>
</ul>

<h3>Tabela Produtos</h3>
<ul>
  <li>categoria_produto</li>
  <li>preço</li>
</ul>

<h2>Ferramentas utilizadas</h2>

Foi utilizado somente o Power BI para desenvolver o Dashboard

<h2>Tratamento dos dados</h2>
<ul>
  <li>Tabela Pedidos: Alterada tipagem dos dados; Transformada coluna “Data previsão” para o formato data.</li>
  <li>Tabela Produtos: Alteração na tipagem dos dados; Segregação do ID e Categoria de modo a criar uma nova coluna com ID; Removido Sublinhado.</li>
  <li>Tabela Estoque: Alterada tipagem dos dados; Ajustada coluna “Data atualização”.</li>
  <li>Tabela Veículos: Alterada tipagem dos dados.</li>
</ul>

<h2>Métricas</h2>
<ul>
  <li>Entregas no prazo;</li>
  <li>Entregas atrasadas;</li>
  <li>Quantidade de veículos disponíveis;</li>
  <li>Quantidade de veículos atrasados;</li>
  <li>S2D - Ship to door;</li>
  <li>Índice de ocorrências por Estado;</li>
  <li>Média de estoque por ano;</li>
  <li>Entregas por Região.</li>
</ul>

<h2>Relacionamentos</h2>
<ul>
  <li>Pedidos -- Produtos</li>
  <li>Pedidos - Veículos</li>
  <li>Produtos -- Estoque</li>
</ul>

<h2>Link do Dashboard</h2>

https://app.powerbi.com/view?r=eyJrIjoiMDk3YmVhOGItNTlkNS00ZDAxLWI2ODItZmEyMGQ5NjY1ODAzIiwidCI6IjA3Njg1MDA5LTg5NzAtNGFkNC05MmU1LTkzOWFhYTc1MGZmZCJ9
