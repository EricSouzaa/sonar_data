# 📡 Projeto de Classificação de Sonar: Rochas vs. Minas usando KNN
Este projeto aplica Machine Learning para identificar se um sinal de sonar reflete uma rocha submarina ou uma mina, com base em 60 frequências registradas. Usamos o algoritmo K-Nearest Neighbors (KNN) com validação cruzada e ajuste de hiperparâmetros.

## 🔗 Dataset original
Os dados foram extraídos do repositório da UCI Machine Learning: 📍 https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks)

# 🔍 Introdução ao problema
Sistemas de sonar emitem sinais sonoros e analisam os ecos que retornam. Com base na intensidade e frequência dessas ondas refletidas, é possível inferir se o objeto detectado é uma mina submarina (M) ou uma rocha (R).

O dataset contém:

208 amostras

60 colunas numéricas representando frequências de retorno

1 coluna final com o rótulo (M para mina, R para rocha)
