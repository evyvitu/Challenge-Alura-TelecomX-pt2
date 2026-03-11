# 📊 Telecom X — Previsão de Churn de Clientes

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte do **Challenge de Data Science da Alura**, com o objetivo de analisar e prever a evasão de clientes (churn) da empresa fictícia **Telecom X**.

Na primeira etapa do projeto foi realizada uma **análise exploratória dos dados** para compreender os padrões de evasão e identificar possíveis fatores relacionados ao cancelamento dos serviços.

Na segunda etapa foi desenvolvido um **pipeline de Machine Learning** capaz de prever quais clientes possuem maior probabilidade de churn, permitindo que a empresa atue de forma preventiva para reduzir perdas.

---

# 🎯 Objetivos do projeto

- Analisar o comportamento dos clientes da Telecom X  
- Identificar fatores associados à evasão (churn)  
- Preparar os dados para modelagem preditiva  
- Construir modelos de classificação para prever churn  
- Avaliar o desempenho dos modelos  
- Identificar as variáveis mais importantes para a previsão  
- Gerar insights estratégicos para retenção de clientes  

---

# 🧠 Etapas do projeto

## 📥 1. Extração e tratamento dos dados

Os dados foram obtidos a partir de um arquivo JSON contendo informações sobre:

- perfil do cliente
- tipo de contrato
- serviços contratados
- valores de cobrança
- histórico de churn

Principais etapas de tratamento:

- normalização da estrutura do JSON  
- renomeação de colunas  
- conversão de variáveis numéricas  
- tratamento de valores ausentes  
- remoção de colunas irrelevantes  
- encoding de variáveis categóricas  

---

## 📊 2. Análise exploratória

A análise inicial permitiu observar padrões importantes relacionados à evasão de clientes.

Foram analisados:

- distribuição da variável **Churn**
- relação entre churn e **tipo de contrato**
- relação entre churn e **tempo de serviço**
- relação entre churn e **valores de cobrança**
- **correlação entre variáveis numéricas**

Essas análises ajudaram a compreender quais características podem influenciar a evasão.

---

## ⚙️ 3. Preparação para Machine Learning

Após a etapa de análise, os dados foram preparados para modelagem.

Processos realizados:

- encoding de variáveis categóricas  
- separação entre **variáveis preditoras (X)** e **variável alvo (y)**  
- verificação da proporção de churn  
- balanceamento de classes utilizando **SMOTE**  
- divisão entre **conjunto de treino e teste**  
- normalização de variáveis numéricas quando necessário  

---

# 🤖 Modelos de Machine Learning

Foram testados diferentes algoritmos de classificação para prever churn:

- Regressão Logística  
- Random Forest  

Os modelos foram avaliados utilizando as seguintes métricas:

- **Acurácia**
- **Precisão**
- **Recall**
- **F1-score**
- **Matriz de confusão**

---

# 📈 Comparação de desempenho dos modelos

| Modelo | Acurácia | Precisão | Recall | F1-score |
|------|------|------|------|------|
| Regressão Logística | 0.79 | 0.65 | 0.52 | 0.58 |
| Random Forest | 0.78 | 0.64 | 0.47 | 0.54 |

Os resultados indicam que ambos os modelos apresentam desempenho semelhante, com leve vantagem para a **Regressão Logística** em algumas métricas.

---

# 🔍 Importância das variáveis

A análise de importância das variáveis mostrou que alguns fatores possuem maior influência na evasão de clientes, como:

- tipo de contrato  
- tempo de serviço  
- encargos mensais  
- serviços adicionais contratados  

Essas informações ajudam a compreender os comportamentos que levam ao cancelamento.

---

# 📉 Previsão de probabilidade de churn

Além da classificação, o modelo também permite estimar a **probabilidade de churn para cada cliente**.

Exemplo de saída do modelo:

| Cliente | Probabilidade de churn |
|------|------|
| Cliente A | 0.96 |
| Cliente B | 0.66 |
| Cliente C | 0.12 |

Clientes com **probabilidade elevada** podem ser considerados de **alto risco**, permitindo que a empresa implemente ações preventivas de retenção.

---

# 💡 Insights estratégicos

Com base nas análises realizadas, alguns fatores parecem influenciar significativamente a evasão de clientes:

- clientes com **contratos mensais** apresentam maior taxa de churn  
- clientes com **pouco tempo de serviço** têm maior probabilidade de cancelar  
- valores mais altos de **cobrança mensal** podem aumentar o risco de evasão  

Esses resultados sugerem que a empresa pode adotar estratégias como:

- incentivos para contratos de longo prazo  
- programas de fidelização para novos clientes  
- ofertas personalizadas para clientes com maior risco de churn  

---

# 🛠 Tecnologias utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Imbalanced-learn  
- Jupyter Notebook  

---

# 📁 Estrutura do projeto

```
Challenge-Alura-TelecomX-pt2
│
├── Challenge-Alura-TelecomX-pt2.ipynb
└── README.md
```

---

# 📌 Conclusão

Este projeto demonstrou como a **análise de dados e técnicas de Machine Learning** podem ser utilizadas para compreender e prever a evasão de clientes.

A construção de modelos preditivos permite que empresas identifiquem **padrões de comportamento associados ao churn** e tomem decisões mais estratégicas para melhorar a retenção de clientes.

Com a utilização dessas ferramentas, a Telecom X pode **atuar de forma preventiva**, direcionando esforços para clientes com maior risco de cancelamento e reduzindo perdas financeiras.

---

📎 Projeto desenvolvido como parte do **Challenge de Data Science da Alura**.
