# TREINAMENTO DE REDES NEURAIS COM KERAS (DADOS TABULARES)
Atividade da disciplina: DISRUPTIVE ARCHITECTURES: IOT, IOB E GENERATIVE AI


## 👩‍👦‍👦 Equipe
- Felipe Seiki Hashiguti - RM98985
- Lucas Corradini Silveira - RM555118
- Matheus Gregorio Mota - RM557254

## EXERCÍCIO 1 – CLASSIFICAÇÃO MULTICLASSE
**Dataset: [Wine Dataset (UCI)](https://archive.ics.uci.edu/dataset/109/wine)**
1. Treinar uma rede neural em Keras para classificar vinhos em 3 classes:
  - Configuração mínima: 2 camadas ocultas com 32 neurônios cada, função de ativação ReLU.
    >  
    >
  - Camada de saída com 3 neurônios, função de ativação Softmax.
    >  
    >
  - Função de perda: categorical_crossentropy.
    >  
    >
  - Otimizador: Adam.
    >  
    >

2. Comparar os resultados com um modelo do scikit-learn (RandomForestClassifier ou LogisticRegression).
   >  
   >
4. Registrar métricas de acurácia e discutir qual modelo teve melhor desempenho.
   >  
   >

## EXERCÍCIO 2 – REGRESSÃO
**Dataset: [California Housing Dataset (Scikit-learn)](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)**
1. Treinar uma rede neural em Keras para prever o valor médio das casas.
- Configuração mínima: 3 camadas ocultas com 64, 32 e 16 neurônios, função de ativação ReLU.
- Camada de saída com 1 neurônio, função de ativação Linear.
- Função de perda: mse.
- Otimizador: Adam.
2. Comparar os resultados com um modelo do scikit-learn (LinearRegression ou
RandomForestRegressor).
3. Registrar métricas de erro (RMSE ou MAE) e discutir qual modelo teve melhor desempenho.
