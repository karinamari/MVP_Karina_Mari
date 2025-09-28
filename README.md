# MVP_Karina_Mari

# MVP: Previsão de Inadimplência para Financiamento de Veículos

Este repositório contém o Minimum Viable Product (MVP) desenvolvido para a disciplina de Machine Learning, como parte do curso de pós-graduação em Ciência de Dados.

## 1. Objetivo do Projeto

O projeto visa desenvolver um modelo de machine learning para prever a probabilidade de um cliente se tornar inadimplente em um financiamento de veículo. O objetivo de negócio é transformar a abordagem de vendas em um modelo mais consultivo, direcionando proativamente o cliente a opções de veículos e modalidades de compra adequadas ao seu perfil, aumentando a taxa de conversão e a satisfação do cliente.

## 2. Conteúdo do Repositório

* **/MVP_Karina_Mari.ipynb**: O notebook Jupyter contendo todo o fluxo do projeto, desde a análise exploratória dos dados até a conclusão final.
* **/Default_Fin.csv**: O dataset utilizado para o treinamento e avaliação.
    * **Fonte Original:** [Loan Default Prediction Dataset (Kaggle)](https://www.kaggle.com/datasets/kmldas/loan-default-prediction).
    * *O arquivo está incluído neste repositório e é carregado via URL Raw para garantir a execução direta e a reprodutibilidade do notebook.*
* **/search_results_rf.pkl**: Artefato salvo contendo os resultados da otimização de hiperparâmetros do modelo Random Forest.

## 3. Como Executar o Projeto

1.  Clone ou faça o download deste repositório.
2.  Abra o notebook `MVP_Karina_Mari.ipynb` em um ambiente compatível, como o Google Colab.
3.  Execute todas as células do notebook em sequência ("Executar tudo").

O notebook foi projetado para ser autocontido, carregando o dataset `Default_Fin.csv` diretamente a partir deste repositório, garantindo a reprodutibilidade.

## 4. Conclusão Principal

A análise demonstrou que as features disponíveis no dataset público possuem poder preditivo limitado. O modelo final, embora metodologicamente robusto, não atingiu um nível de performance ideal para uma aplicação em produção, destacando a necessidade de enriquecer a base de dados com features mais relevantes (ex: histórico de crédito) e de utilizar dados internos da empresa para garantir a generalização do modelo.
