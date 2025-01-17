# Previsão de Score de Crédito com Inteligência Artificial - (Maratona - Hashtag Treinamentos)

## Descrição
Este projeto utiliza algoritmos de Machine Learning para prever o score de crédito de clientes com base em variáveis socioeconômicas e comportamentais. A previsão de score de crédito é uma ferramenta essencial para instituições financeiras avaliarem o risco associado a clientes antes de conceder crédito ou empréstimos.

O objetivo principal é construir um modelo preditivo que forneça um score confiável para tomada de decisão, utilizando dados históricos e técnicas de aprendizado supervisionado.

## Objetivo do Projeto
Desenvolver um modelo de Machine Learning capaz de prever o score de crédito de um cliente.
Identificar as variáveis mais relevantes para a previsão.
Criar relatórios visuais para explicar a performance do modelo e os insights extraídos.
Perguntas de Negócio Respondidas
Quais fatores influenciam o score de crédito?

Identificação das variáveis mais impactantes, como idade, renda, histórico de pagamentos, etc.
Qual a precisão do modelo ao prever o score de crédito?

### Tecnologias Utilizadas
Python: Para processamento de dados, treinamento do modelo e avaliação.
Bibliotecas principais:
pandas e numpy para manipulação de dados.
scikit-learn para treinamento e avaliação dos modelos de Machine Learning.
Power BI: Para criação de relatórios interativos e visualizações de insights.
Colab: Para desenvolvimento e teste do modelo.

## Dataset
O projeto foi baseado em um dataset fictício que contém as seguintes informações:

ID do Cliente
Idade
Renda Mensal
Endividamento (%)
Histórico de Pagamento (quantidade de parcelas atrasadas)
Tipo de Empréstimo
Score Atual de Crédito (variável-alvo para treinamento)
Tamanho do Dataset: 10.000 registros (80% para treino, 20% para teste).

## Modelos de Machine Learning Utilizados
Regressão Linear
Árvores de Decisão
KNNs análise comparativa, o Random Forest apresentou o melhor desempenho em termos de precisão e estabilidade.

