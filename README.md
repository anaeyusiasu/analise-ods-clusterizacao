# analise-ods-clusterizacao
Análise dos indicadores dos ODS dos municípios brasileiros utilizando técnicas de Clusterização


# Análise dos ODS nos Municípios Brasileiros
Este projeto aplica técnicas de mineração de dados para identificar perfis de sustentabilidade entre os 5.570 municípios brasileiros, considerando seu desempenho nos Objetivos de Desenvolvimento Sustentável (ODS).

## Objetivo
Agrupar os municípios conforme suas similaridades nos ODS e analisar a relação entre os agrupamentos e as características regionais do Brasil.

## Metodologia
Foi utilizada a base **IDSC-BR 2025**, com as notas gerais dos 17 ODS. O ODS 14 foi excluído devido à grande quantidade de dados ausentes. As 16 variáveis restantes foram normalizadas e analisadas por meio do algoritmo **K-Means**, com a formação de quatro clusters. Posteriormente, foi utilizado **Random Forest** para validar os agrupamentos e identificar os ODS mais relevantes para diferenciá-los.

## Principais resultados
Os quatro clusters apresentaram perfis distintos e forte associação com padrões regionais. Os melhores desempenhos médios foram observados principalmente nas regiões **Sul e Sudeste**, enquanto os menores se concentraram no **Norte e Nordeste**.
Os ODS relacionados a **crescimento econômico, instituições e energia limpa** apresentaram maior relevância para a diferenciação dos grupos.

## Tecnologias
Python • Pandas • NumPy • Scikit-learn • GeoPandas • Matplotlib • Seaborn

## Fonte dos dados
Índice de Desenvolvimento Sustentável das Cidades – **IDSC-BR 2025**.
[IDSC-BR 2025](https://idsc.cidadessustentaveis.org.br/)
