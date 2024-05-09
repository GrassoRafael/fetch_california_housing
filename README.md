# Projeto de Previsão de Preços de Casas na Califórnia
Este projeto visa desenvolver um modelo de machine learning para prever os preços de casas na Califórnia utilizando a base de dados fetch_california_housing do Scikit-learn.

# Objetivo
O objetivo principal deste projeto é construir um modelo de regressão capaz de prever com precisão os preços das casas na Califórnia com base em diversas características disponíveis na base de dados.

# Descrição da Base de Dados
A base de dados utilizada é a fetch_california_housing fornecida pelo Scikit-learn, que contém informações sobre preços de casas na Califórnia, bem como características relacionadas a essas casas. Alguns dos atributos incluídos na base são: longitude, latitude, renda média da região, número médio de quartos, número médio de quartos, entre outros.

# Metodologia
Exploração de Dados: Realizamos uma análise exploratória para entender a distribuição dos dados, identificar correlações e detectar possíveis anomalias.
Pré-processamento de Dados: Realizamos o pré-processamento dos dados, incluindo tratamento de valores ausentes, normalização de características e codificação de variáveis categóricas.
Seleção de Características: Utilizamos técnicas de seleção de características para identificar as características mais relevantes para o modelo.
Treinamento do Modelo: Treinamos vários modelos de regressão, como Regressão Linear, Árvores de Decisão, e Gradient Boosting, utilizando a base de dados de treino.
Avaliação do Modelo: Avaliamos o desempenho dos modelos utilizando métricas de avaliação de regressão, como Erro Quadrático Médio (MSE) e Coeficiente de Determinação (R²).
Otimização do Modelo: Realizamos ajustes nos hiperparâmetros dos modelos selecionados para melhorar o desempenho e generalização.
Validação Cruzada: Aplicamos validação cruzada para verificar a robustez do modelo e sua capacidade de generalização para novos dados.

# Instalação
Este projeto requer Python 3 e as seguintes bibliotecas Python:

NumPy
Pandas
Scikit-learn
Você pode instalar essas bibliotecas via pip.

````bash
pip install numpy pandas scikit-learn
````
Uso
Você pode executar o script main.py para treinar e avaliar o modelo de previsão de preços de casas na Califórnia.

````bash
python main.py
````
# Contribuição
Contribuições são bem-vindas! Para sugestões de melhorias, por favor abra uma issue neste repositório.
