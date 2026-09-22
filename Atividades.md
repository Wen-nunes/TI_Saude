## Atividade 1: Analise de crédito. 

1. Regressão Logística
<img width="224" height="104" alt="image" src="https://github.com/user-attachments/assets/0279208d-eaa2-43be-b047-31cba563f37f" />

Apresenta um desempenho mediano, com acurácia de 65% e F1-Score de 0.4800. Sua capacidade de identificar os verdadeiros positivos (12) é comparável à do Random Forest, mas o modelo acaba penalizado por cometer mais erros tanto nos falsos positivos (8) quanto nos falsos negativos (18).

2. Gradient Boosting
<img width="219" height="114" alt="image" src="https://github.com/user-attachments/assets/325a11a9-f777-4c0f-b081-1a18c4ac8afc" />

Apresenta sinal de overfitting devido a dificuldade em identificar a classe 1. Desempenho fraco, evidenciado pela queda no F1-Score 0.3478 e acurácia de 60%. O modelo falhou na identificação da classe positiva, gerando 22 falsos negativos e acertando apenas 8 previsões de interesse.

3. Random Forest
<img width="187" height="113" alt="image" src="https://github.com/user-attachments/assets/1a7863d5-13b5-4fda-ae2d-12790b9afd23" />

Dos métodos analisados obteve o melhor equilíbrio com acurácia de 69% e o maior F1, de 0.5306, quanto a matriz de confusão, mostra que erro menos as predições podendo ser visto na sua diagonal principal com o baixo indice de falso positivo e falso negativo.


## Atividade 2: Analise de dados da saúde.

1. Regressão Logística
<img width="228" height="116" alt="image" src="https://github.com/user-attachments/assets/5b9652cf-9e0a-4d1b-b754-8e39151899dd" />

Embora tenha tido um rendimento pior que o Gradient Boosting, a Regressão Logística foi o modelo que mais identificou pacientes de alto risco, acertando 29 casos e cometendo apenas 8 Falsos Negativos. No entanto, pecou ao classificar incorretamente 10 pacientes saudáveis como sendo de alto risco.

2. Gradient Boosting
<img width="229" height="117" alt="image" src="https://github.com/user-attachments/assets/23d434a0-4751-4db7-8ed7-e87f58aa6539" />

modelo alcançou a maior Acurácia 78.67% e o maior F1-Score 0.7778, com destaque em cometer o menor número total de erros, apenas 16, e foi o mais eficiente na classificação correta dos pacientes de baixo risco, com 31 Verdadeiros Negativos.

3. Random Forest
<img width="186" height="111" alt="image" src="https://github.com/user-attachments/assets/d8a3f30a-38b0-4d93-b1a5-04c41771bfba" />

Apresentou a menor Acurácia 74.67% e F1-Score 0.7324. Foi o modelo com a maior taxa de Falsos Negativos, sendo crítico num contexto de saúde, pois significa que 11 pacientes de alto risco de internação não foram detectados.
