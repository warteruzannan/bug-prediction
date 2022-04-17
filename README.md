# **Predição de bugs**

### **Contexto**

Durante o processo de desenvolvimento de software podem acontecer diversas alterações no código e alguns bugs podem ser inseridos de forma não intencional.

É muito importante que esses bugs sejam encontrados e corrigidos. Para isso, há diversas técnicas já conhecidas na comunidade de Engenharia de Software. Uma que vem sendo cada vez mais explorada é a utilização de algoritmos de ML para a realização dessa tarefa.

### **Dataset**

Um dataset bem interessante que pode ser utilizada para predizer _bugs_, _features_ e _perguntas_ é o GitHub Bugs Prediction (https://www.kaggle.com/datasets/anmolkumar/github-bugs-prediction).

De forma resumida, o dataset contém o título e corpo de issues do github e para cada entrada há uma classe associada que diz qual se aquela issue está relacionada a uma feature, um bug ou uma dúvida.

### **Tarefa**

Originalmente, o dataset foi projetado para dizer se uma issue do github é uma feature, bug ou pergunta. Entretanto, visto a necessidade de identificar bugs no software e com o objetivo de simplificar a tarefa pretende-se trabalhar com os seguintes objetivos:

> **Induzir um classificador capaz de predizer se determinada issue do github é um bug ou não. Ou seja, uma tarefa binária.**

> **Comparar um rede neural profunda com o outros algoritmos**

Notebook utilizado [AQUI](https://github.com/warteruzannan/bug-prediction/blob/main/bug_predictions_neural_networks.ipynb)
