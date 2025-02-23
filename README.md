# pos-infnet-classificacao

## Objetivo Geral
Validar os conhecimentos em algoritmos supervisionados aplicados à classificação, utilizando a base de dados dos vinhos verdes portugueses.

## Etapas principais:
- Conclusão do módulo do Kaggle 'Intro to Machine Learning';
- Utilizar a base completa, mas para as questões 2 a 5 trabalhar somente com os vinhos brancos;
- Criação da variável “opinion” a partir da variável “quality” (0 para quality ≤ 5 e 1 para quality > 5);
- Descrição exploratória dos dados (variáveis, tipos, estatísticas básicas);
- Treinamento de três modelos de classificação (regressão logística, árvore de decisão e SVM) usando validação cruzada estratificada com 10 folds;
- Cálculo das métricas de avaliação (acurácia, precisão, recall, f1-score) para cada modelo;
- Comparação dos modelos (inclusive plotando as curvas ROC médias) para escolha do melhor;
- Utilização do melhor modelo treinado com os vinhos brancos para inferência na base dos vinhos tintos;
- Publicação do código em um repositório GitHub.

## Fontes e Bases
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.
