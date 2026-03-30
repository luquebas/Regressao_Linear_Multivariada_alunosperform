# Predição da Performance de Estudantes com Regressão Linear Multivariada

## Descrição
Este projeto é um estudo de **regressão linear multivariada** para prever a **Performance** de estudantes, usando informações como:

- Horas de estudo  
- Notas anteriores  
- Atividades extracurriculares  
- Horas de sono  
- Questões práticas resolvidas  

O objetivo é demonstrar **pré-processamento, análise exploratória, aplicação de modelos de regressão e interpretação de resultados**.

> **Observação:** O dataset utilizado é do **[Kaggle](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression)** e o projeto foi desenvolvido **apenas com fins de aprendizado**.

---

## Tecnologias / Bibliotecas Utilizadas

- Python 
- Pandas, NumPy  
- Matplotlib
- Scikit-learn (LinearRegression, Ridge, Lasso, MinMaxScaler, OneHotEncoder)  
- Joblib (para salvar e carregar modelos)  

---

## Etapas do Projeto

1. **Análise Exploratória de Dados (EDA)**
   - Inspeção inicial das colunas e tipos de dados  
   - Estatísticas descritivas  
   - Matriz de correlação e scatter plots  
   - Detecção de outliers  

2. **Pré-processamento**
   - One-Hot Encoding para variáveis categóricas  
   - Normalização das variáveis numéricas  

3. **Treinamento dos Modelos**
   - Linear Regression (modelo original/base)  
   - Ridge (regularização L2)  
   - Lasso (regularização L1)  

4. **Avaliação**
   - Métricas: MAE, MSE, RMSE, R²  
   - Comparação de coeficientes dos modelos  
   - Visualização dos resíduos  

5. **Predição de Novo Aluno**
   - Demonstração de como prever a performance de um estudante hipotético  

---

## Insights

- Variáveis mais importantes: `previous_scores` e `hours_studied`  
- Regularização (Ridge/Lasso) não melhorou os resultados, pois todas as features são relevantes e o dataset é pequeno  
- Modelo base apresentou **R² ≈ 0.99**, indicando ótimo ajuste para o conjunto de dados  

---