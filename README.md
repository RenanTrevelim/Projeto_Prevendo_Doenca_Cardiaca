🫀 Predição de Doença Cardíaca com Machine Learning

Este projeto aplica técnicas de aprendizado de máquina para prever a presença de doença cardíaca com base em dados clínicos, exames laboratoriais e testes cardíacos. Foram utilizados modelos supervisionados de classificação, com foco em avaliação estatística robusta e interpretabilidade dos resultados.

🎯 Objetivo

Construir e avaliar modelos de classificação capazes de prever a ocorrência de doença cardíaca, utilizando métricas adequadas e estratégias para lidar com desbalanceamento entre classes.


📊 Conjunto de Dados

O dataset contém variáveis clínicas e resultados de exames:

 - Idade

 - Sexo

 - Tipo de dor no peito

 - Pressão arterial

 - Colesterol

 - Glicemia em jejum

 - ECG em repouso

 - Frequência cardíaca máxima

 - Dor induzida por exercício

 - Depressão e inclinação do segmento ST

 - Número de vasos observados por fluoroscopia

 - Cintilografia

 - Doença cardíaca (variável alvo)

⚙️ Modelos Utilizados

 - Regressão Logística (LogisticRegression)

 - Árvore de Decisão (DecisionTreeClassifier)

 - Stratificação: treino e teste

Métricas:

 - Acurácia

 - Precision

 - Recall

 - F1-score

 - Matriz de confusão

 - Curva ROC

⚖️ Tratamento de Desbalanceamento

Foi aplicado o parâmetro:

 - class_weight = 'balanced' -> para tornar o aprendizado mais justo entre classes, penalizando proporcionalmente erros na classe minoritária.

📈 Resultados — Regressão Logística

 - Acurácia: 89%

 - F1-score ponderado: 0,89

 - Resultados:
<img width="627" height="315" alt="image" src="https://github.com/user-attachments/assets/8eb7772c-aeb6-43a5-86bc-f082f4bbafb4" />

 - Resultado Matriz de Confusão
<img width="625" height="569" alt="image" src="https://github.com/user-attachments/assets/d035ee74-4a93-4cbe-a440-821fd34bfce4" />

 - Resultado Curva ROC
<img width="560" height="569" alt="image" src="https://github.com/user-attachments/assets/d4832752-3305-4538-9774-0b6b9374e5be" />

Boa separação entre classes

Excelente desempenho na classe majoritária e forte detecção da classe minoritária

✅ Conclusão

A Regressão Logística apresentou desempenho consistente, interpretável e confiável, sendo adequada para cenários clínicos onde a explicabilidade é importante. A utilização de balanceamento de classes melhorou significativamente a detecção da classe minoritária.
