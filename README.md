# Bike_rent_rede_neural
rede neural para previsão de demanda de aluguel de bicicletas

Este projeto tem como objetivo criar uma rede neural para prever a demanda de aluguel de bicicletas, com base em dados coletados por uma locadora de bicicletas. A ideia é utilizar esses dados históricos para realizar previsões precisas sobre a locação futura, empregando uma rede neural com 4 camadas densas.

Descrição do Projeto
O projeto utiliza dados reais de uma locadora de bicicletas para treinar uma rede neural, permitindo assim a previsão da demanda de aluguel em períodos futuros. As 4 camadas densas da rede são projetadas para aprender padrões complexos nos dados, proporcionando uma modelagem eficaz para a previsão de aluguel.

Métricas Incorporadas
Diversas métricas foram incorporadas para avaliar a performance do modelo e possibilitar um processo comparativo robusto. Algumas das métricas utilizadas são:

MAE (Mean Absolute Error): Média do valor absoluto das diferenças entre as previsões e os valores reais de aluguel.

MSE (Mean Squared Error): Média dos quadrados das diferenças entre as previsões e os valores reais de aluguel.

RMSE (Root Mean Squared Error): Raiz quadrada do MSE, proporcionando uma visão mais intuitiva do erro médio.

R² (Coefficient of Determination): Indica a proporção da variabilidade nos dados que é explicada pelo modelo.

Adj R² (Adjusted R-squared): Versão ajustada do R², levando em consideração o número de variáveis no modelo.

adj_r2 = 1 - (1 - r2) * (n - 1) / (n - k - 1)

Essas métricas fornecem insights valiosos sobre o desempenho da rede neural, permitindo ajustes e otimizações para melhorar a precisão das previsões. O processo comparativo torna-se crucial para validar a eficácia do modelo em diferentes cenários.
