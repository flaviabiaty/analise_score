# 📊 Previsão de Score de Clientes

## 📌 Descrição
Este projeto realiza uma **análise e previsão de score de clientes** de um banco, utilizando algoritmos de **classificação** para apoiar decisões de concessão de crédito.  
A partir de uma base de dados com **100.000 clientes** e 25 colunas, o objetivo é prever se um cliente terá **score “Poor”, “Standard” ou “Good”**, auxiliando o banco a reduzir riscos e melhorar a tomada de decisão.
---
## 🎯 Objetivos
- Importar e tratar a base de dados.  
- Converter variáveis de texto em numéricas para uso em modelos de classificação.  
- Treinar e comparar dois algoritmos de Machine Learning (Árvore de Decisão e KNN).  
- Identificar as características mais relevantes para prever o score.  

---
## 🛠 Tecnologias Utilizadas
- **Python**
- **Pandas** → manipulação de dados  
- **scikit-learn** → pré-processamento, modelagem e avaliação  
- **LabelEncoder** → codificação de variáveis categóricas  
- **DecisionTreeClassifier** e **KNeighborsClassifier** → modelos de classificação
---

## 📂 Etapas do Projeto
1. **Importação da base de dados** com Pandas.  
2. **Verificação e tratamento** de valores ausentes e formatos de dados.  
3. **Codificação** de variáveis categóricas com `LabelEncoder` (exceto a variável alvo `score_credito`).  
4. **Separação dos dados** em treino e teste com `train_test_split`.  
5. **Treinamento** dos modelos: Árvore de Decisão e KNN.  
6. **Avaliação da acurácia** dos modelos.  
7. **Análise de importância das variáveis** no modelo vencedor.
---

## 📊 Resultados
- **Árvore de Decisão**: 82% de acurácia  
- **KNN**: 73% de acurácia  

**Principais variáveis para previsão:**
1. `divida_total`
2. `mix_credito`
3. `juros_empréstimo`
O modelo de Árvore de Decisão foi o mais adequado para este conjunto de dados.

---

## 🚀 Conclusão
O projeto demonstrou a importância do tratamento de dados, escolha de modelos adequados e avaliação de métricas para obter previsões confiáveis.  
A análise de variáveis mais relevantes permite ao banco direcionar estratégias para reduzir clientes com score baixo.

---
