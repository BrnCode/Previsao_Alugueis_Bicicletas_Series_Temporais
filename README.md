# Previsão de Aluguéis de Bicicletas com Séries Temporais

**O objetivo deste projeto é desenvolver um modelo preditivo capaz de estimar o número de bicicletas que serão alugadas. 
Para isso, realizaremos uma análise exploratória dos dados e construiremos um modelo preditivo utilizando o Prophet, desenvolvido pela Meta.**

## Previsão com Séries Temporais
O objetivo é criar um modelo preditivo com séries temporais, nesse projeto iremos usar exclusivamente o Prophet para isso.

## Projeto
**Contexto:** Utilizamos um conjunto de dados fornecido pela Alura no curso de séries temporais. Este conjunto de dados contém informações coletadas ao longo de 2 anos sobre uma empresa de aluguel de bicicletas que atua em Londres. Saber onde isso ocorre é um fator importante, pois o conjunto de dados inclui informações sobre o clima. Portanto, é necessário considerar informações sobre como as estações do ano ocorrem no hemisfério norte.

### Análise Exploratória de Dados
Para compreender os dados e as variáveis disponíveis, conduzimos uma análise exploratória detalhada.
Isso incluiu também a investigação das relações entre as variáveis preditoras e o target, utilizando testes de hipóteses adequados.
O notebook contendo esta etapa pode ser acessado [aqui]([https://github.com/leticiadluz/ml_internet_provider_churn/blob/main/EDA.ipynb](https://github.com/BrnCode/Previsao_Alugueis_Bicicletas_Series_Temporais/blob/main/EDA_locacoes_de_bicicleta.ipynb).

### Modelo Preditivo
Construi alguns variações do Prophet, visando entender como melhorar o resultado do modelo baseline com alterações nos dados, uso e melhoria de hiperparametros. Nosso modelo final atindiu um RMSE que nos trouxe um erro de 20.24% nos valores preditos no D1.
O notebook contendo esta etapa pode ser acessado [aqui](https://github.com/BrnCode/Previsao_Alugueis_Bicicletas_Series_Temporais/blob/main/Modelo_locacoes_de_bicicletas_ipynb.ipynb)

## Ferramentas utilizadas

* Google Colab
  
## Linguagem utilizada

* Python
