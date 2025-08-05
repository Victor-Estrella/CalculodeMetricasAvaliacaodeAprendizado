# Projeto: Avaliação de Modelos de Classificação com Métricas e Matriz de Confusão

Este projeto demonstra como calcular as principais métricas de avaliação para modelos de classificação de dados, utilizando uma matriz de confusão multiclasse gerada de forma arbitrária. As métricas implementadas são:

- **Acurácia**
- **Sensibilidade (Recall)**
- **Especificidade**
- **Precisão**
- **F-score**

Além disso, o projeto inclui a visualização gráfica da matriz de confusão no estilo heatmap, facilitando a análise dos resultados.

## Como usar

1. **Abra o notebook no Google Colab**
2. Execute as células na ordem apresentada:
   - Importação das bibliotecas
   - Geração dos rótulos verdadeiros e previstos
   - Visualização da matriz de confusão
   - Cálculo das métricas

## Exemplo de visualização

A matriz de confusão é exibida como um heatmap, mostrando a proporção de acertos e erros para cada classe:

![Exemplo de matriz de confusão](https://scikit-learn.org/stable/_images/sphx_glr_plot_confusion_matrix_001.png)

## Fórmulas Utilizadas

- **Acurácia:** (VP + VN) / (VP + VN + FP + FN)
- **Sensibilidade (Recall):** VP / (VP + FN)
- **Especificidade:** VN / (VN + FP)
- **Precisão:** VP / (VP + FP)
- **F-score:** 2 * (Precisão * Recall) / (Precisão + Recall)

Onde:
- VP: Verdadeiros Positivos
- VN: Verdadeiros Negativos
- FP: Falsos Positivos
- FN: Falsos Negativos

No caso multiclasse, as métricas são calculadas usando a média macro.

## Requisitos

- Python 3.x
- numpy
- matplotlib
- seaborn
- scikit-learn

## Objetivo
O objetivo deste projeto é entender como cada métrica funciona na avaliação de classificadores, utilizando exemplos práticos e visualização gráfica.

## Autor 
Victor Henrique Estrella Carracci
