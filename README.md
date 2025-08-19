# 📊 Análise de Evasão de Clientes (Churn)

## 📌 Descrição
Este projeto tem como objetivo analisar e prever a **evasão de clientes (Churn)** em uma empresa de telecomunicações.  
Foram utilizados modelos de **Machine Learning** para identificar os fatores mais relevantes que influenciam no cancelamento de clientes.

---

## 🛠️ Tecnologias
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🔎 Metodologia
- Pré-processamento e normalização dos dados  
- Análise exploratória com correlações, boxplots e scatterplots  
- Modelagem com:
  - **Regressão Logística** (com normalização)  
  - **Random Forest** (sem normalização)  
- Avaliação com métricas de acurácia, precisão, recall e F1-score  

---

## 📈 Resultados
- **Fatores mais relevantes para o churn**:
  - Tempo de contrato (**tenure**)  
  - Tipo de contrato (mensal x anual)  
  - Total gasto (**Charges_Total**)  
  - Serviços adicionais (Internet, Suporte técnico, etc.)  

- **Desempenho dos modelos**:
  - Regressão Logística: ~XX% de acurácia  
  - Random Forest: ~YY% de acurácia (melhor resultado)  

---

## 💡 Estratégias de Retenção
1. Oferecer benefícios para clientes novos (menor tempo de contrato).  
2. Incentivar migração para contratos anuais.  
3. Criar pacotes de valor agregado (internet + suporte + TV).  
4. Monitorar clientes de baixo gasto e oferecer promoções.  

---
