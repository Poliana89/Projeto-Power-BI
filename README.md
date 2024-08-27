# Projeto-Power-BI


<h2>Dashboard Analítico de Vendas Globais</h2>


<h3> Objetivo </h3>
O objetivo do relatório é responder algumas perguntas de negócios, do dataset vendas globais. Nesse processo iremos utilizar o software da Microsoft  Power BI, para construir o dashboard e gerar 
insight valiosos para tomadas de decição e acompanhamento gerencial.

<h3>Ferramenta Utilizada</h3>

Usaremos a ferramenta Power BI, na versão desktop Versão: 2.132.908.0 64-bit (agosto de 2024).

<h3>Perguntas de Negócio.</h3>

    • Qual o valor total vendido?
    • Quantas vendas foram realizadas por categoria de produtos?
    • Quantas vendas foram realizadas por país, considerando a prioridade de entrega?
    • Qual foi a média de desconto nas vendas por subcategoria de produtos?
    • Quais países tiveram a maior média de valor de venda?

  <h3>Transformando e Tratando o Conjunto de Dados de Vendas</h3>


 <b> Carregando a fonte de dados no Power BI– </b> A fonte de dados são dados fictícios na extesão  data.csv, com  as seguintes colunas: 

<table>
  <tr>
    <td>ID_Pedido</td>
    <td>Nessa coluna está o código das transações de venda</td>
  </tr>
  <tr>
    <td>Data_Pedido</td>
    <td>Apresenta a data que o pedido foi realizado</td>
  </tr>
   <tr>
    <td>ID_Cliente</td>
    <td>Código do cliente</td>
  </tr>
  <tr>
    <td>Segmento</td>
    <td>Segmento que ocorreu a venda (O tipo do cliente).</td>
  </tr>
   <tr>
    <td>Região</td>
    <td> Região onde foi solicitado o pedido</td>
  </tr>
 <tr>
    <td>País</td>
    <td> País onde foi solicitado o pedido</td>
  </tr>
   <tr>
    <td>Product_ID</td>
    <td> Código do produto</td>
  </tr>
   <tr>
    <td>Categoria</td>
    <td> Categoria do produto</td>
  </tr>
   <tr>
    <td>SubCategoria</td>
    <td> Subcategoria do produto.</td>
  </tr>
  <tr>
    <td>Total_Vendas</td>
    <td> Total de Vendas dos produtos</td>
  </tr>
   <tr>
    <td>Quantidade</td>
    <td>Quantidade de produtos vendidos</td>
  </tr>
  <tr>
    <td>Desconto </td>
    <td>Desconto</td>
  </tr>
   <tr>
    <td>Lucro </td>
    <td>Lucro da empresa</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>Prioridade do pedido</td>
  </tr>
</table>

 Ao importar o arquivo foi verificado que não teria necessidade de tratar os dados, limpá-los ou formatar, pois o arquivo já estava com os dados e colunas corretos.

<h3>Construção do Dashboard - Relatório Vendas </h3>

<li>Para responder à pergunta <b>qual o valor total vendido</b>, utilizei o gráfico do tipo CARTÃO, informando a coluna <b>Total_Vendas</b>, e fazendo a soma de todas as vendas, no conjunto de dados. </li>

<li>Para responder à pergunta <b>quantas vendas foram realizadas por categoria de produtos</b>b>, utilizei o gráfico de pizza com a coluna <b>ID_Pedido</b>, realizando a contagem dos itens vendidos por categorias.</li>

<li>Para responder à pergunta <b>quantas vendas foram realizadas por país, considerando a prioridade de entrega</b>, utilizei o gráfico de barras empilhadas, nesse gráfico visualizaremos a contagem de número de pedidos(vendas) por país e por prioridade de entrega.</li>

<li>Para responder à pergunta <b>qual foi a média de desconto nas vendas por subcategoria de produtos</b>, utilizei o gráfico de barras na horizontal, onde conseguimos visualizar a média de desconto por subcategoria.</li>


<li>Para responder à pergunta <b> quais países tiveram a maior média de valor de venda</b>, utilizei para visualização o mapa, aplicando o filtro de média maior que 250, gerando um visual, mas limpo dentro do mapa.</li>
<br></br>
<b>Filtros:</b> O dashboard irá dar ao usuário a possibilidade de filtrar os dados por ano, por segmento e por país.

<h3>Publicação</h3>

Para visualização do relatório <b> Dashboard Analítico de Vendas Globais</b>, basta clicar no link abaixo.

<a> https://app.powerbi.com/view?r=eyJrIjoiMjkwY2NlNjQtMzZkMi00ZWQ4LWFiODEtNmZjYmIxMmEzMmU1IiwidCI6IjU1Mjc3NjUwLThhODAtNDVlZC04M2I5LTc0MmU0ZGM5MmY4NiJ9
</a>
