# TelecomX_2

# 📊 Predição de Evasão de Clientes (Churn Prediction)

Este projeto tem como objetivo **analisar e prever a evasão de clientes (churn)** em uma base de dados utilizando técnicas de **Aprendizado de Máquina**.
Foram aplicados dois modelos principais: **Regressão Logística** e **Random Forest**, além de análises estatísticas para identificar os fatores que mais influenciam a evasão.

---
## 🚀 Tecnologias e Bibliotecas
- Python 3.x
- Pandas, Numpy
- Matplotlib, Seaborn
- Scikit-learn

---
## 📂 Estrutura do Projeto
- `TelecomX_2.ipynb` → Notebook principal com todo o código.
- `README.md` → Documentação do projeto.

---
## 📈 Modelos Avaliados

### 🔹 Regressão Logística
- **Acurácia**: 79,7%
- **Recall (evasão)**: 54,4%
- **F1-score (evasão)**: 58,7%
- **Interpretação**: Modelo simples e interpretável, útil para identificar a **direção do impacto** das variáveis.


### 🔹 Random Forest
- **Acurácia**: 77,9%
- **ROC AUC**: 0,824
- **Recall (evasão)**: 60%
- **F1-score (evasão)**: 59%
- **Interpretação**: Modelo mais robusto, com **maior poder de generalização** e melhor capacidade em detectar clientes que evadem. 
- **Limitação**: Pode apresentar **leve overfitting** e menor interpretabilidade.

---
## 🔎 Principais Fatores de Evasão
A partir da análise dos **coeficientes da Regressão Logística** e da **importância das variáveis no Random Forest**, identificamos:

1. **Tempo de contrato (Tenure)**
   - Contratos curtos estão fortemente associados à evasão.

2. **Gasto total (Total Charges)**
   - Clientes com baixo gasto acumulado tendem a evadir.

3. **Cobrança mensal (Monthly Charges)**
   - Valores altos, sem fidelização, aumentam risco de evasão.

4. **Tipo de contrato**
   - Contratos **mensais** aumentam churn, enquanto contratos **anuais ou de longo prazo** reduzem.

5. **Serviços adicionais**
   - Clientes que não utilizam serviços complementares apresentam maior risco de evasão.

---
## 🎯 Estratégias de Retenção
Com base nos insights obtidos, recomenda-se:

- **Programas de fidelização** → Descontos e benefícios progressivos para clientes de longo prazo.
- **Engajamento inicial** → Estratégias de onboarding e suporte nos primeiros meses (período mais crítico).
- **Política de preços flexível** → Planos adaptados a clientes com cobranças mensais elevadas.
- **Oferta de serviços adicionais** → Incentivar adesão a pacotes extras, aumentando engajamento.
- **Monitoramento de clientes de baixo gasto** → Ofertas e ações preventivas antes da evasão.

---
## 📌 Conclusão
- A **Regressão Logística** se destacou pela interpretabilidade, ajudando a entender os fatores que influenciam a evasão.
- O **Random Forest** apresentou melhor capacidade de detecção (maior Recall e ROC AUC), sendo mais eficaz para **identificar clientes em risco**.
- Juntos, os modelos fornecem **insights estratégicos** para reduzir churn e aumentar a retenção de clientes.

---

## 👩<2025>💻 Autoria
Projeto desenvolvido por **[Suellen Cunha da Silva]** como estudo de predição de churn com Machine Learning.
