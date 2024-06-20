
# Criando um Modelo de Regressão

## Descrição do Projeto

O objetivo deste projeto é prever o preço das casas na Califórnia utilizando o dataset California Housing, disponível em [California Housing Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html#sklearn.datasets.fetch_california_housing). Apliquei diferentes técnicas de regressão para criar e avaliar modelos que possam fazer previsões precisas sobre os preços das casas.

## Ferramentas Utilizadas

-   **Matriz de Correlação**: Para identificar as relações entre as variáveis.
-   **Tratamento de Dados**: Limpeza e preparação dos dados para análise.
-   **Avaliação do Modelo**: Métricas e técnicas para avaliar a performance dos modelos.
-   **Regressão Linear Simples e Múltipla**: Modelos de regressão para prever os preços das casas.
-   **Árvore de Regressão**: Técnica de aprendizado de máquina para regressão.

## Descrição dos Dados

O dataset California Housing inclui as seguintes colunas:

-   **MedInc**: Renda média das famílias no bairro.
-   **HouseAge**: Idade média das casas no bairro.
-   **AveRooms**: Número médio de cômodos por casa.
-   **AveBedrms**: Número médio de quartos por casa.
-   **Population**: População do bairro.
-   **AveOccup**: Número médio de ocupantes por casa.
-   **Latitude**: Latitude da localização.
-   **Longitude**: Longitude da localização.
-   **MedHouseVal**: Valor médio das casas no bairro (variável alvo).

## Conclusões

1.  **Matriz de Correlação**
    
    -   A matriz de correlação foi utilizada para identificar quais variáveis têm maior correlação com o preço das casas (MedHouseVal).
        
2.  **Regressão Linear Simples e Múltipla**
    
    -   Modelos de regressão linear simples e múltipla foram treinados e avaliados. A regressão múltipla levou em consideração todas as variáveis explicativas para melhorar a precisão.
        
3.  **Árvore de Regressão**
    
    -   Utilizamos a árvore de regressão para capturar relações não lineares entre as variáveis e o preço das casas.
        
4.  **SVR (Suport Vector Regression)**
    
    -   Apliquei o algoritmo SVR para melhorar a precisão das previsões em cenários com alta dimensionalidade e complexidade.
        

## Objetivo

O objetivo deste projeto é desenvolver e avaliar diferentes modelos de regressão para prever os preços das casas na Califórnia, utilizando técnicas que vão desde a regressão linear simples até métodos mais complexos como árvores de regressão e SVR. Através da análise e visualização dos dados, buscamos proporcionar insights que ajudem a entender os fatores que influenciam os preços das casas.



**Lembrete**: O código foi realizado na versão 3.11.7 do python
