#Marcelo Siqueira Bonfim - 558254
# Análise de Consumo de Energia Residencial

Este repositório contém o código e as análises do projeto de ciência de dados focado no consumo de energia de uma residência individual. O trabalho é dividido em quatro partes, abordando a exploração de dados, modelagem preditiva e técnicas de clustering.

### Conteúdo do Projeto

O projeto é dividido em um único notebook Jupyter, seguindo as instruções do `CHECKPOINT 01`. Ele aborda os seguintes tópicos:

* [cite_start]**Parte 1 - Exercícios Iniciais:** Análise exploratória e visualização do dataset `Individual Household Electric Power Consumption`[cite: 2].
* [cite_start]**Parte 2 - Exercícios Adicionais:** Análises mais avançadas, como autocorrelação de séries temporais e redução de dimensionalidade com PCA[cite: 22, 28, 32].
* [cite_start]**Parte 3 - Novo Dataset:** Exploração de um segundo dataset (`Appliances Energy Prediction`) com variáveis ambientais e modelagem de regressão e classificação[cite: 44, 47].
* [cite_start]**Parte 4 - Orange Data Mining:** Respostas e conclusões obtidas através da ferramenta de mineração de dados Orange[cite: 79].

### Como Executar o Projeto

Para executar a maior parte do código, você pode usar um ambiente de notebook interativo como o Google Colab ou o VS Code.

#### Requisitos

* **Python 3.x**
* **Bibliotecas Python:**
    * `pandas`
    * `numpy`
    * `scikit-learn`
    * `matplotlib`
    * `seaborn`
    * `statsmodels`

Você pode instalar todas as bibliotecas de uma vez usando pip:
`pip install pandas numpy scikit-learn matplotlib seaborn statsmodels`

#### Estrutura de Arquivos

* `checkpoint.ipynb`: O notebook Jupyter que contém todo o código e as análises.
* `household_power_consumption.txt`: O dataset principal usado nas Partes 1 e 2.
* [cite_start]`energydata_complete.csv`: O segundo dataset usado na Parte 3[cite: 44, 46].
* `README.md`: Este arquivo.

### Como Iniciar

1.  Clone este repositório ou baixe os arquivos.
2.  Faça o upload dos datasets (`household_power_consumption.txt` e `energydata_complete.csv`) para o seu ambiente de trabalho (por exemplo, no Google Colab).
3.  Abra o arquivo `checkpoint.ipynb` e execute as células na ordem para reproduzir as análises e obter os resultados.
