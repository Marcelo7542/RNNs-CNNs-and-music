English Description Below:


SimpleRNN and Bach

Olá! Bem-vindo ao meu repositório dedicado a experimentos com Redes Neurais Recorrentes (RNNs). 

Este projeto explora a aplicação de RNNs simples para tarefas de previsão de séries temporais e para geração de sequências musicais inspiradas no estilo de Johann Sebastian Bach.

Conteúdo do Repositório

O repositório possui dois scripts principais:

1. SimpleRNN
   
Este script utiliza uma RNN simples para realizar previsões em uma série temporal sintética. O objetivo é entender o comportamento das RNNs e experimentar diferentes arquiteturas.

Principais Recursos:

Geração de dados de séries temporais sintéticas com múltiplos padrões de ondas senoidais.

Comparação entre modelos lineares básicos e arquiteturas RNN para previsão.

Testes com diferentes números de camadas RNN e diferentes hiperparâmetros.

Uso de métricas como o Mean Squared Error (MSE) para avaliar o desempenho.

2. Bach
   
Este script explora a geração de sequências musicais, inspiradas no estilo de Johann Sebastian Bach.

Utiliei arquitetura WaveNet para modelar sequências musicais e gerar novos padrões com base nos dados de treinamento.

Principais Recursos:

Treinamento de um modelo sequencial para aprender padrões musicais.

Uso de camadas conv1D empilhadas para capturar dependências temporais mais complexas.

Geração de novas sequências musicais e análise da qualidade dos resultados.


-------------------------------------------------------------------------------------



SimpleRNN and Bach

Hello! Welcome to my repository dedicated to experiments with Recurrent Neural Networks (RNNs).

This project explores the application of simple RNNs for time series forecasting and music sequence generation inspired by the style of Johann Sebastian Bach.

Repository Content

The repository contains two main scripts:

SimpleRNN

This script uses a simple RNN to perform predictions on a synthetic time series. The goal is to understand the behavior of RNNs and experiment with different architectures.

Key Features:

Generation of synthetic time series data with multiple sinusoidal patterns.

Comparison between basic linear models and RNN architectures for forecasting.

Testing with different numbers of RNN layers and hyperparameters.

Use of metrics such as Mean Squared Error (MSE) to evaluate performance.

Bach

This script explores the generation of music sequences inspired by the style of Johann Sebastian Bach.

It leverages the WaveNet architecture to model musical sequences and generate new patterns based on the training data.

Key Features:

Training a sequential model to learn musical patterns.

Using stacked Conv1D layers to capture more complex temporal dependencies.

Generating new musical sequences and analyzing the quality of the results.
