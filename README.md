# Reconhecimento_Digitos_Manuscritos
Este repositório contém um projeto prático de aprendizado de máquina que visa reconhecer dígitos manuscritos usando o conjunto de dados MNIST e a abordagem K-Nearest Neighbors (KNN). 

O projeto abrange desde a importação e pré-processamento dos dados até o treinamento do modelo, avaliação de desempenho e visualização dos resultados.

**Visão Geral**
Neste projeto, utilizei o conjunto de dados MNIST, composto por imagens de dígitos manuscritos de 0 a 9. 

O objetivo era desenvolver um modelo capaz de classificar corretamente esses dígitos. As etapas do projeto incluíram:

- Carregamento dos dados do MNIST e conversão para um DataFrame do **Pandas**.
- Pré-processamento dos dados, incluindo normalização usando o **StandardScaler**.
- Divisão dos dados em conjuntos de treinamento e teste.
- Treinamento de um modelo **KNN** para reconhecimento de padrões.
- Avaliação do modelo usando métricas como acurácia, matriz de confusão e relatório de classificação.
- Visualização dos resultados com gráficos da matriz de confusão e exemplos de previsões.


**Como Usar**
Clone este repositório para sua máquina local usando git clone.

Instale as bibliotecas necessárias

Execute o Jupyter Notebook Reconhecimento_de_Digitos_Manuscritos.ipynb para ver o projeto passo a passo.


**Resultados**
O modelo KNN alcançou uma acurácia de 94.6% na tarefa de reconhecimento de dígitos manuscritos. 
A matriz de confusão e o relatório de classificação fornecem insights detalhados sobre o desempenho do modelo em cada classe.
