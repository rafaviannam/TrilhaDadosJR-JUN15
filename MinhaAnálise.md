
# 📚 Trilha Inicial Ciência de Dados Jr
Este projeto tem como objetivo realizar uma análise básica de dados utilizando Python, explorando um conjunto de dados pré-definido para extrair insights simples através de estatísticas descritivas e visualizações gráficas.

## Projeto
- Para realizar as análises exploratórias e gerar os gráficos de visualização foram utilizadas as bibliotecas Python, Seaborn; Matplotlib e Pandas.
- É necessário realizar a instalação das bibliotecas e o download da base de dados no formato csv

## Análise Exploratória dos dados:
1. O primeiro passo da análise foi a compreensão das informações presentes na base de dados. A partir disso, foi possível extrair as seguintes características:
   - Número de linhas: 25
   - Número de colunas: 5
   - Ausência de valores nulos
   - Média da Quantidade de Vendas: 17.96
   - Desvio Padrão da Quantidade de Vendas: 10.92
   - Valor máximo e mínimo da Quantidade de Vendas: 50 e 5 (respectivamente) 
   - Média do Preço Unitário: 83.9
   - Desvio Padrão do Preço Unitário: 21.98
   - Valor máximo e mínimo do Preço Unitário: 119.9 e 39.9 (respectivamente) 

![image](https://github.com/codigocerto/TrilhaDadosJR-JUN15/assets/147278256/efe59725-5e16-4254-a354-f1c5fdb5187e)

- Além disso, também é possível verificar a mediana da Quantidade de Vendas e do Preço Unitário: 15 e 79.9, respectivamente

## Visualização gráfica

- A mediana das duas informações também pode ser visualizada com boxplots:
  
![image](https://github.com/codigocerto/TrilhaDadosJR-JUN15/assets/147278256/01378e5e-a34b-4187-b517-fc006b67d4cb)

- A linha central do boxplot da quantidade de vendas confirma a mediana 15 e também indica a presença de dois outliers ou seja, valores extremos. 

![image](https://github.com/codigocerto/TrilhaDadosJR-JUN15/assets/147278256/3e9f9318-de07-4ce9-b0c8-e28aae3e688c)

- A linha central do boxplot do preço unitário confirma a mediana 79.9 e a ausência de outliers.

- Além dos boxplots também é possível analisar o número de vendas por curso com o gráfico de barras:

![image](https://github.com/codigocerto/TrilhaDadosJR-JUN15/assets/147278256/d2223725-9b47-4db9-8af2-c6ac477e0d55)


O gráfico nos da informações relevantes sobre o curso com maior número de vendas e permite uma compreensão mais rápida e visual das informações o número de vendas por curso de forma decrescente. A paleta de cores escolhida destaca os cursos com o maior número de vendas

## Desafios Propostos:
### 1.Calcular a receita total gerada pela venda dos cursos.
      Receita total = R$ 32735,10

*O cálculo foi com a soma de todas as multiplicação dos preços unitários dos cursos pelas respectivas quantidades de vendas

   
### 2. Identificar o curso com o maior número de vendas.
 O curso com maior número de vendas foi "Introdução à Programação em Python". Tal informação já estava disponível de forma visual no gráfico de barras, mas também foi confirmada numericamente ao organizar a base em ordem decrescente

### 3. Visualizar a distribuição das vendas ao longo do tempo através de gráficos.

Para visualizar a distribuição ao longo do mês de janeiro optei por um gráfico de linhas e um gráfico de barras organizado de forma decrescente. 
![image](https://github.com/rafaviannam/TrilhaDadosJR-JUN15/assets/147278256/50f21ccf-5f0c-40a8-890d-eb83e5b618f3)
![image](https://github.com/rafaviannam/TrilhaDadosJR-JUN15/assets/147278256/fc110807-57c0-4582-b3f2-cd3a7b8a63d3)

No gráfico de barras as datas estão organizadas de forma decrescente (do dia com maior número de vendas para o menor) e as cores mais escuras dão destaque para os dias com mais vendas.

## Conclusão

A análise dos dados permitiu identificar o comportamento dos compradores em relação aos cursos disponíveis. O curso com o maior número de vendas foi "Introdução à Programação em Python", que também é o curso com o menor preço unitário. Esse comportamento inversamente proporcional entre o preço dos cursos e o número de vendas pode ser comprovado com o gráfico de dispersão abaixo:

![image](https://github.com/rafaviannam/TrilhaDadosJR-JUN15/assets/147278256/72eee9eb-d339-4c47-9a07-8bd65b5e9d77)

Além disso, foi possível identificar as datas com maior número de vendas: dia 01 e dia 20 de janeiro.
Essas informações permitem a elaboração de estratégias de vendas mais eficazes futuramente, pois ao compreender os padrões de consumo dos usuários é possível criar abordagens mais personalizadas e que aumentem o fluxo de vendas. 
