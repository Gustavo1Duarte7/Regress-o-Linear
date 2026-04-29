# 📊 Análise de Regressão Linear - Investimento vs Taxa Anual

## 🎯 Objetivo

Este projeto tem como objetivo analisar a relação entre o **investimento inicial** e a **taxa anual de retorno**, utilizando um modelo de **Regressão Linear**.

A proposta é entender se existe correlação entre as variáveis e construir um modelo capaz de realizar previsões.

---

## 🗂️ Estrutura do Projeto

```
📦 projeto-regressao-linear
 ┣ 📜 Franqueado.ipynb
 ┣ 📜 slr12.csv
 ┗ 📄 README.md
```

---

## 📥 Base de Dados

O dataset utilizado contém duas variáveis:

* **CusInic** → Investimento inicial
* **FrqAnual** → Taxa anual

Exemplo:

| FrqAnual | CusInic |
| -------- | ------- |
| 1000     | 1050    |
| 1125     | 1150    |
| 1087     | 1213    |

---

## ⚙️ Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 🔍 Etapas da Análise

### 1. Carregamento dos dados

Leitura do arquivo CSV e inspeção inicial dos dados.

### 2. Preparação das variáveis

* Definição de:

  * `X` → Investimento inicial (variável independente)
  * `Y` → Taxa anual (variável dependente)

### 3. Análise de Correlação

Foi calculada a correlação entre as variáveis:

📌 Correlação ≈ **0.47**

👉 Indica uma correlação **moderada positiva**.

---

### 4. Modelagem (Regressão Linear)

O modelo foi treinado utilizando:

* Intercepto (β₀): **347.55**
* Coeficiente angular (β₁): **0.61**

---

### 5. Visualização

Foi gerado um gráfico contendo:

* Pontos reais (scatter plot)
* Reta de regressão (previsão do modelo)

---

## 📈 Resultado

O modelo sugere que:

👉 Para cada aumento no investimento inicial, a taxa anual tende a aumentar de forma proporcional.

Porém, como a correlação não é forte, existem outros fatores que podem influenciar o resultado.

---

## 🚀 Possíveis Melhorias

* Adicionar mais variáveis (modelo multivariado)
* Avaliar métricas como:

  * R²
  * MAE / RMSE
* Testar outros modelos de regressão
* Fazer tratamento de outliers

---

## 📌 Conclusão

Este projeto demonstra a aplicação prática de:

* Análise exploratória de dados
* Correlação entre variáveis
* Construção de modelo de Machine Learning
* Visualização de resultados

---

## 👨‍💻 Autor

Projeto desenvolvido para fins de estudo e portfólio na área de Dados.

