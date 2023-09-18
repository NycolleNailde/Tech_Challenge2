# Tech_Challenge2
Este projeto faz parte do meu estudo sobre séries temporais. Avaliei as componentes da decomposição, a estacionariedade, as funções de autocorrelação e autocorrelação parcial. Também analisei o desempenho de alguns modelos preditivos, utilizando o erro wmape.

## Análise da IBOVESPA

Os dados analisados são os valores de fechamento da IBOVESPA no período entre 2005 e 2013. Esses dados foram obtidos do site da [Investing](https://br.investing.com/indices/bovespa-historical-data).

## Análise da Decomposição da Série Temporal e Estacionariedade

Realizei a decomposição da série temporal para avaliar suas componentes de tendência, sazonalidade e resíduo. A estacionariedade da série foi verificada pelo teste de Dickey-Fuller aumentado.

## Análise dos Gráficos de ACF e PACF

Analisei os gráficos de autocorrelação (ACF) e autocorrelação parcial (PACF). Foi possível identificar uma forte autocorrelação entre os valores à medida que o número de lags aumenta. Por outro lado, a autocorrelação parcial mostrou-se significativa apenas para valores de lags pequenos.

## Avaliação do Erro wmape para Modelos de Previsão

Utilizei o erro wmape (Erro Médio Ponderado Absoluto) como métrica de desempenho dos modelos de previsão testados, incluindo os modelos Naive, SeasonalNaive, SeasonalWindowAverage, AutoArima e Prophet. Apresento os resultados dessa avaliação.

## Análise do Desempenho dos Modelos com e sem Transformação Matemática da Série

Realizei testes nos dados sem transformação matemática e com transformação logarítmica, subtraída da média móvel e com uma diferenciação. Essa transformação foi feita para atingir a estacionariedade. Como resultados, os modelos tiveram um melhor desempenho com os dados sem a transformação.


