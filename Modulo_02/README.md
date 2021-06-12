# <p align = "center"> 👀🎲 Visualização de Dados com Seaborn e Matplotlib 🎲👀
  
[![Github](https://img.shields.io/badge/gustavolq-100000?style=plastic&logo=github&logoColor=white)](https://github.com/gustavolq)
[![linkedin](https://img.shields.io/badge/gustavoquadra-0077B5??style=plastic&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gustavoquadra/)
  
Olá! Seja muito bem-vindo ao meu repositório referente ao **Módulo 2 - Visualização de Dados com Seaborn e Matplotlib** do Bootcamp de Data Science Aplicada 2021 da [Alura](https://www.alura.com.br/).
  
 A divisão desse repositório se encontra da seguinte forma :
 - [Aulas](https://github.com/gustavolq/Bootcamp-DataScience-Alura/tree/main/Modulo_02/Aulas) : Notebook e datasets utilizados durante as aulas.
 - [Projeto](https://github.com/gustavolq/Bootcamp-DataScience-Alura/tree/main/Modulo_02/Projeto) : Notebook e datasets utilizados para o projeto final do módulo.
  
Para realizar as aulas e o projeto utilizamos o [Google Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb), um serviço de nuvem da Google, onde podemos realizar a criação de Notebooks para realizar a criação de linhas de comandos em Python e textos.
  
 ## Mas Gustavo, o que é Seaborn e Matplotlib? 🤔
 O [Matplotlib](https://matplotlib.org/), é um pacote da linguagem de programação Python, voltado para a criação de gráficos e visualizações de dados, sendo criada pelo biólogo e neurocientista americano John D. Hunter. 
 
 O [Seaborn](https://seaborn.pydata.org/) também é um pacote de Python voltado para a visualização de dados, foi baseado no Matplotlib e fornece uma interface de alto nível para desenharmos gráficos estatísticos atraentes e informativos.
  
# <p align="center"> 💻 Sobre o Projeto 💻

<p align="center">
  <img width="700" src="https://github.com/gustavolq/Bootcamp-DataScience-Alura/blob/main/Modulo_02/Outros/AnaliseDadosGif.gif">
</p>

## Introdução
O projeto será baseado na análise dos dados de casos confirmados de Covid-19 para o estado de Santa Catarina (SC) - Brasil e seus municípios.

### Resumo Covid-19

COVID-19 é a doença causada por uma nova espécie de coronavírus, denominada SARS-CoV-2 e pertence a uma família de vírus que já circulava no Brasil antes da pandemia e era responsável por grande parte dos resfriados comuns. A origem do vírus ainda está sendo estudada, mas é muito provável que ela teve origem em Wuhan, China através de morcegos no ano de 2019.

O COVID-19 possuem sintomas leves na maioria dos casos (tosse, dor de garganta, coriza), mas pode ser extremamente agressiva (falta de ar) à uma minoria. Costuma ser mais perigoso para idosos com mais de 60 anos e pessoas com doenças pré-existentes.

Para a prevenção do COVID-19, é importante mantermos as mãos higienizadas com alcool em gel, utilizarmos máscaras e evitarmos aglomerações. E também, aliada as medidas de prevenção, felizmente, hoje (05/06/2021), estamos em campanha de vacinação no mundo inteiro para vencermos essa pandemia!

## Objetivo do Projeto
O objetivo principal do projeto será realizar uma análise de dados referente à diversas informações (idade, raça, municipio, sexo, sintomas...) de pacientes que foram confirmados com COVID-19 em Santa Catarina - Brasil, buscando responder questionamentos e formular hipóteses para os nossos dados.

## Planejamento do Projeto
<b> 1.</b> Introdução </br>
<b> 2.</b> Definição do Problema de Negócio </br>
<b> 3.</b> Preparação dos Dados </br>
<b> 4.</b> Análise Exploratória dos Dados </br>
<b> 5.</b> Criação de Hipóteses </br>
<b> 6.</b> Conclusão </br>

## Dados Utilizados
Os dados foram extraídos do [Portal de Dados Abertos do Estado de Santa Catarina](http://dados.sc.gov.br/tr/dataset/covid-19-dados-anonimizados-de-casos-confirmados) em 04/06/2021 e sofreram um processo de manipulação para utilizarmos as seguintes variáveis :
- recuperados
- data_inicio_sintomas
- sintomas
- sexo
- municipio
- obito
- idade

Os dados foram separados utilizando o comando ```split -l 195665 Todos-Confirmados-SC.csv``` em minha máquina e podem ser acessados nesse [repositório](https://github.com/gustavolq/Bootcamp-DataScience-Alura/tree/main/Modulo_02/Projeto/Dados).

Caso você queira verificar o dicionário de dados completo, você pode clicar [aqui](https://github.com/gustavolq/Bootcamp-DataScience-Alura/blob/main/Modulo_02/Projeto/Dados/Dicionario_Dados.pdf) para verificar o PDF com as informações.
