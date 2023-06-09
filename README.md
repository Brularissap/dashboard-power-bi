<h1>  POWER BI | DASHBOARD </h1>
<h2>Introdução</h2>
Este repositório contém exemplos de dashboards criados com o auxílio da ferramenta Power BI. O Power BI é uma plataforma de análise de dados poderosa e intuitiva que permite criar visualizações interativas e insights acionáveis a partir de grandes conjuntos de dados. Explore esses projetos para ver como o Power BI pode ser usado para criar dashboards eficazes e visualmente atraentes, com recursos como gráficos, tabelas e filtros interativos.

<h2>Projeto 1: Dashboard do desmatamento na Amazônia Legal (AML), através dos dados do PRODES</h2>
<p>O objetivo do dashboard é apresentar o desmatamento na Amazônia Legal com base nos dados do PRODES. O PRODES (Projeto de Monitoramento do Desflorestamento na Amazônia Legal por Satélite) é um programa coordenado pelo Instituto Nacional de Pesquisas Espaciais (INPE) que utiliza imagens de satélite para monitorar e quantificar o desmatamento na Amazônia Legal. O programa é capaz de mapear e calcular as áreas desmatadas na região, sendo que a área mínima mapeada é de 6,25 hectares.</p>

<p>O PRODES disponibiliza dados precisos sobre o desmatamento na Amazônia Legal, que são apresentados de forma clara e acessível através do dashboard. É possível fazer uma busca por período, visualizar o total de polígonos do PRODES e observar um mapa dos estados da região. Além disso, o dashboard apresenta uma tabela com o desmatamento acumulado por estado na região, um gráfico que exibe a evolução do desmatamento ao longo do tempo e um gráfico de pizza que mostra a porcentagem do desmatamento por estado.</p>

<p>O GIF abaixo apresenta uma prévia da visualização do dashboard.</p>
<p align="center">
<img src="https://github.com/Brularissap/dashboard-power-bi/blob/main/desmatamento-prodes.gif"/>
</p>

Para criar o dashboard, utilizei os dados do Incremento anual no desmatamento - Shapefile (2008/2022), para Amazônia Legal, disponível para download no Terra Brasilis. No entanto, antes de importar esses dados diretamente para o Power BI, foi necessário realizar alguns procedimentos técnicos. Primeiramente, abri os dados no software QGIS e os espacializei, antes de exportá-los para uma planilha CSV no Excel. A partir daí, eu iniciei meu trabalho com esses dados no Power BI, onde extrai, transformei, carreguei e tratei as informações para criar o dashboard que apresento neste texto. 
  
Mais informações sobre a origem desses dados podem ser acessadas através do seguinte link:

```
http://terrabrasilis.dpi.inpe.br/downloads/
```

O dashboard completo pode ser acessado através do seguinte link: 
```
https://app.powerbi.com/view?r=eyJrIjoiZDYyMjY2MmItMDc4Yi00Y2EwLTg3YjctZjJhYTU2NDAxNGI2IiwidCI6IjllYjM1NmMzLWE0OGYtNDc1NS04NDlkLWY5NzFiNzE1ODU5MiJ9
```

É importante destacar que a preservação da Amazônia Legal é uma questão de grande importância, e o dashboard é uma ferramenta útil para monitorar e compreender a evolução do desmatamento na região. 
Com essas informações, é possível tomar medidas para proteger a Amazônia Legal e garantir sua sustentabilidade a longo prazo.

<h2>Projeto 2: Pet Shop Alura Pets</h2>

Este é um projeto fictício desenvolvido durante o curso de Power BI que fiz no Alura. A dona do Petshop, Helô, deseja obter informações sobre as vendas de suas duas marcas de produtos, Doguito e Gatito, ao longo do tempo, bem como identificar quais produtos são mais vendidos, qual o faturamento total, a média de pets por cliente e o gênero que mais compra cada produto. Além disso, Helô tem planos de expansão e quer saber onde abrir uma nova loja com base nas informações de faturamento e clientes. 

Com base nas fontes de dados, que incluíam tabelas de vendas em formato Excel, tabela TXT com informações dos clientes e tabela de produtos em formato Excel, utilizei as ferramentas do Power BI para tratar e modelar os dados. A partir disso, criei um dashboard com as informações solicitadas pela proprietária do Petshop Alura Pets, Helô.
  
<p>O GIF abaixo apresenta uma prévia da visualização do dashboard.</p>
<p align="center">
<img src="https://github.com/Brularissap/dashboard-power-bi/blob/main/alura-pets.gif"/>
</p>

<p>De acordo com os planos de expansão de Helô, proprietária do Pet Shop Alura Pets, de saber onde abrir uma nova loja com base nas informações de faturamento e clientes, é importante salientar que o gráfico de faturamento por bairro pode ser uma ferramenta valiosa. Esse gráfico, gerado a partir das tabelas de vendas e de clientes, permite identificar quais são os bairros onde a marca possui um bom desempenho e onde há uma demanda latente por produtos para animais de estimação.</p>
<p>Com base nessas informações, Helô pode tomar uma decisão mais embasada sobre onde abrir sua nova loja, visando potencializar seu faturamento e aumentar a satisfação dos clientes. Além disso, o gráfico de faturamento por bairro pode ajudar a identificar tendências de mercado e oportunidades de negócio que possam ser exploradas pela empresa.</p>
<p>Assim, fica claro que a análise do faturamento por bairro pode ser uma ferramenta estratégica para a expansão dos negócios do Pet Shop Alura Pets, auxiliando Helô a tomar decisões mais embasadas e a identificar novas oportunidades de mercado.</p>

O dashboard completo pode ser acessado através do seguinte link: 
```
https://app.powerbi.com/view?r=eyJrIjoiNTk1NmJjYjAtYjViYy00OWRhLThlZDgtNDMyMzhhMDQzYTZiIiwidCI6IjllYjM1NmMzLWE0OGYtNDc1NS04NDlkLWY5NzFiNzE1ODU5MiJ9

```

