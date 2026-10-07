# projeto_previsao_ml
Do dado bruto à previsão: um projeto completo em Python que transforma dados em informações, treina modelos de Machine Learning e testa sua capacidade de previsão.

Sobre o Projeto:
Este projeto tem como intuito desenvolver um modelo de Machine Learning capaz de prever a próxima ação/vela do mercado Forex, utilizando dados históricos do par EUR/USD.

O que é o Forex?
O Forex (Foreign Exchange) é o mercado de negociação de moedas, onde diferentes moedas são negociadas em pares. Neste projeto, foi utilizado o par EUR/USD, que representa a relação entre o euro e o dólar americano.

Como funciona?
Os dados históricos utilizados no projeto são obtidos através da plataforma MetaTrader 5 (MT5). A partir desses dados, é gerado um arquivo CSV, que posteriormente é lido e analisado pelo modelo de Machine Learning.

A etapa de coleta e geração dos dados também envolve MQL5, linguagem utilizada para desenvolver ferramentas e automatizações dentro do MetaTrader 5.

Depois disso, a biblioteca Scikit-Learn é utilizada para treinar o modelo, analisar os dados e realizar as previsões.

Fluxo do projeto:
MetaTrader 5 → Dados → CSV → Machine Learning → Previsão

Resultados e evolução
Os resultados iniciais foram promissores, porém um bom resultado não significa que o modelo necessariamente funcionará no mercado real.

O projeto ainda precisa evoluir e ser testado de forma mais aprofundada, principalmente para verificar se os resultados se mantêm em diferentes períodos e condições de mercado.

Como próximos passos, a ideia é comparar diferentes algoritmos de Machine Learning, analisar seus resultados e realizar testes mais aprofundados.

Objetivo
Mais do que simplesmente buscar uma previsão correta, o principal objetivo deste projeto é aprender, experimentar e entender na prática todo o processo, desde a obtenção dos dados até o treinamento, avaliação e evolução de um modelo de Machine Learning aplicado a dados do mercado financeiro.
