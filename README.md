# IATitanic
Trabalho da matéria de inteligência artificial

Explicação dos valores:
Verdadeiro Negativo (TN) = 3: O modelo previu corretamente 3 passageiros que não sobreviveram (classe negativa).
Falso Positivo (FP) = 10: O modelo previu incorretamente que 10 passageiros sobreviveram, quando na verdade eles não sobreviveram.
Falso Negative (FN) = 11: O modelo previu incorretamente que 11 passageiros não sobreviveram, mas eles sobreviveram.
Verdadeiro Positivo (TP) = 37: O modelo previu corretamente que 37 passageiros sobreviveram (classe positiva).

Acurácia: 66%
Isso indica que de todas as classificações realizadas pelo modelo, 66% delas estavam corretas, o que implica em 34% de classificações erradas.

Pode se observar também que o modelo está acertando mais as previsões de sobrevivência (37 acertos na classe de sobreviventes), mas tem dificuldade em prever corretamente os passageiros que não sobreviveram (somente 3 acertos nesta classe).
Existem muitos falsos positivos (10) e falsos negativos (11), o que indica que o modelo está confundindo passageiros que não sobreviveram com aqueles que sobreviveram, e vice-versa.
