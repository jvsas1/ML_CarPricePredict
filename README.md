# Cálculo da previsão do preço de venda de carros.

<p>O objetivo desse projeto é desenvolver um modelo de máquina para calcular o preço de venda dos carros.</p> 
<p>Usou-se o modelo de regressão linear, que apresentou um score de 84%</p> 
<h1>Etapas: </h1>
<h2>1. Data-Cleaning</h2>
<p>Remoção de valores nulls e duplicados</p>
<h2>2. Análises exploratórias</h2>
<h2>3. Remoção de Outliers</h2>
<p>Com o boxplot, obsevou-se a presença dos outliers da base, os de maiores valore foram removidos, pois sua presença afetaria bastante o desempenho e score da máquina. </p>
<h2>4. Label Encoding</h2>
<p>Conversão das labels (grupos/categorias) em valores numéricos para serem utilizados no modelo.</p>
<h2>5. Construção do modelo</h2>
<p>Importação do modelo de regressão linear, divisão da base em 'train' e 'test' e retorno dos valores de previsões, score e erro médio quadrático.</p>
<h2>6. Comparação e análise dos resultados</h2>
<p>Análise de amostras de carros da base, com seus preços de venda reais e o preço de venda previsto pelo modelo, ao lado do erro percentual.</p>
