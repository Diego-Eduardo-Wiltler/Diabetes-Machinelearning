# Classificação de Diabetes usando Árvore de Decisão

## Este é um projeto de classificação de diabetes usando um modelo de árvore de decisão em Python.

###### O código realiza as seguintes etapas:

1. Importa as bibliotecas necessárias, incluindo pandas, scikit-learn e numpy.
2. Lê o arquivo CSV que contém os dados de pacientes do hospital de diabetes de Pima Indian usando pandas e separa os dados em uma matriz de características e um vetor de rótulos.
3. Divide o conjunto de dados em um conjunto de treinamento e um conjunto de teste usando a função train_test_split da biblioteca scikit-learn.
4. Cria um modelo de árvore de decisão usando a classe DecisionTreeClassifier da biblioteca scikit-learn.
5. Treina o modelo usando o conjunto de treinamento.
6. Realiza previsões no conjunto de teste usando o modelo treinado.
7. Calcula várias métricas de avaliação, incluindo a acurácia, a precisão, a revocação (recall) e o f1-score usando as funções accuracy_score, precision_score, recall_score e f1_score da biblioteca scikit-learn.
8. Calcula a matriz de confusão usando a função confusion_matrix da biblioteca scikit-learn.
9. Imprime as métricas de avaliação e a matriz de confusão.

## Como usar:
- Instale as bibliotecas necessárias (pandas, scikit-learn e numpy).
- Baixe o arquivo diabetes.csv.
- Abra o arquivo projeto_classificacao_diabetes.py em um ambiente Python (por exemplo, Jupyter Notebook, Google Colab, PyCharm, etc.).
- Execute o código.
- Veja as métricas de avaliação e a matriz de confusão impressas na tela.

## Exemplo

Acurácia: 0.7142857142857143

Precisão: 0.7085106382978723

Revocação(recall): 0.7142857142857143

F1-SCORE: 0.7089366661242388

Matriz de Confusão:
 
 [[117  33]
 
 [ 36  45]]
