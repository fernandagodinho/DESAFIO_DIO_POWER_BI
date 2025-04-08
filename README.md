O projeto "Classificação de músicas do Spotify 🎵"
é uma aplicação de ciência de dados que usa o conjunto de dados de faixas do Spotify disponível no Kaggle. 
Ele contém informações sobre 125 gêneros musicais, com diversos recursos de áudio associados a cada faixa.

Objetivo do Projeto 🎯
Desenvolver um modelo preditivo para classificar músicas em "agitadas" e "lentas" com base no valor da coluna valence.
Essa métrica descreve a positividade musical: valores altos indicam faixas alegres, enquanto valores baixos
indicam músicas melancólicas.

Etapas do Projeto 🚀
Exploração de Dados:

Carregar a base de dados usando o Pandas e exibir as colunas e primeiras linhas.

O dataset tem 114.000 registros e 21 colunas, como: track_name, popularity, danceability, energy, valence, e tempo.

Criação da Variável Target:

Baseada na coluna valence:

Músicas com valence > 0.5 são classificadas como "agitadas".

Músicas com valence <= 0.5 são classificadas como "lentas".

Uma nova coluna chamada target é adicionada para armazenar essa categorização.

Visualização de Dados:

Criado um histograma para entender a distribuição dos valores de valence.

Refinamento do Dataset:

Eliminação de colunas desnecessárias (Unnamed: 0, track_id) para reduzir o dataframe àquelas mais relevantes
para a análise e modelagem.

Próximos Passos:

Dividir o dataset em conjunto de treino e teste.

Escolher algoritmos de machine learning (como Decision Trees, Random Forests ou Logistic Regression) para construir
o modelo preditivo.

Avaliar métricas de desempenho, como acurácia e matriz de confusão, para verificar se o modelo faz boas classificações.

É um projeto interessante para explorar técnicas de classificação e até construir sistemas de recomendação
musical com potencial para aplicações no mundo real.
