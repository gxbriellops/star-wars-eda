# Projeto de Análise de Dados de Star Wars

## Visão Geral

Este repositório contém uma análise exploratória de dados de uma pesquisa sobre Star Wars realizada pelo FiveThirtyEight. A análise investiga vários aspectos do fandom de Star Wars, incluindo visualização de filmes, preferências de personagens e padrões demográficos entre fãs.

## Descrição do Dataset

O dataset inclui respostas de 1.187 participantes da pesquisa com informações sobre:
- Se eles assistiram aos filmes de Star Wars
- Quais filmes específicos eles assistiram
- Preferências de filmes (classificações)
- Opiniões sobre personagens (favorável/desfavorável)
- Informações demográficas (gênero, idade, renda, educação, localização)
- Opiniões sobre o debate "quem atirou primeiro"
- Familiaridade com o Universo Expandido
- Cruzamento de fandom com Star Trek

## Principais Análises Realizadas

1. **Padrões de Visualização de Filmes**
   - Porcentagem de entrevistados que assistiram a cada filme
   - Comparação de visualização entre fãs de Star Wars e fãs de Star Trek

2. **Impacto do Nível de Educação**
   - Análise de como os níveis de educação se correlacionam com o fandom de Star Wars
   - Distribuição de fãs entre diferentes grupos educacionais

3. **Idade e Preferências de Filmes**
   - Exame dos padrões de visualização de filmes em diferentes faixas etárias
   - Investigação de diferenças geracionais no consumo de Star Wars

4. **Análise de Classificações de Filmes**
   - Classificações médias para cada filme de Star Wars
   - Filmes mais e menos populares entre os fãs

5. **Popularidade de Personagens**
   - Análise das classificações de favorabilidade dos personagens
   - Identificação dos personagens mais e menos populares (Yoda foi o mais popular, Jar Jar Binks o menos popular)

6. **Preferências Regionais**
   - Popularidade de personagens por região geográfica
   - Padrões regionais no fandom de Star Wars

7. **Perfis Demográficos**
   - Comparação entre fãs e não-fãs de Star Wars em variáveis demográficas
   - Distribuições de gênero, idade, renda e educação entre os fãs

8. **Análise Probabilística**
   - Cálculos de probabilidade condicional (ex: probabilidade de um respondente masculino avaliar a Princesa Leia muito favoravelmente)

## Metodologia

A análise empregou várias técnicas de transformação de dados e criou colunas derivadas para entender melhor os padrões nos dados. Os métodos principais incluíram:

- Limpeza de dados e renomeação de colunas sem nome
- Criação de métricas derivadas (ex: "Assistiu_Todos" para rastrear quem assistiu a todos os filmes)
- Transformação de dados categóricos em valores numéricos para análise
- Implementação de técnicas de visualização usando Matplotlib e Seaborn
- Análise estatística incluindo regressão logística para identificar preditores de fãs
- Cálculos de probabilidade condicional para examinar relações específicas

## Descobertas Interessantes

- Diferenças de gênero no fandom (mais homens entre os fãs, mais mulheres entre os não-fãs)
- Maior concentração de fãs entre aqueles com educação universitária
- Correlação entre o fandom de Star Trek e Star Wars
- Diferenças regionais na popularidade dos personagens
- Alta popularidade da Princesa Leia entre os respondentes masculinos (63,18% muito favorável)
- Padrões claros de preferência pelos prequels entre muitos respondentes, com "A Vingança dos Sith" recebendo a classificação mais alta

## Nota Pessoal

Trabalhar com este conjunto de dados foi particularmente interessante porque exigiu uma transformação cuidadosa dos dados. Precisei pensar criticamente sobre como criar colunas derivadas e transformar os dados para facilitar uma análise mais significativa. O processo de manipulação de dados e engenharia de recursos ajudou a revelar padrões que não eram imediatamente óbvios no conjunto de dados brutos.

## Ferramentas Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
