# 📊 Projeto: Previsão de Risco de Crédito com Machine Learning
### por Márcia Bayardino Weyne

Este projeto visa prever a inadimplência de clientes de cartão de crédito utilizando algoritmos de Machine Learning. O fluxo inclui treinamento com tratamento de desbalanceamento via SMOTE, salvamento do modelo e aplicação em novos dados.

---

## 🎯 Objetivos

- Criar um modelo preditivo baseado em atributos como:
  - Limite de crédito (`limit_bal`)
  - Idade (`age`)
  - Histórico de pagamento (`pay_0`, `pay_2`, `pay_4`, `pay_5`)
  - Valor de pagamento (`pay_amt2`)
- Tratar desbalanceamento com SMOTE
- Padronizar os dados com `StandardScaler`
- Usar Regressão Logística como modelo base
- Aplicar o modelo a novos dados de clientes

---

## 🧰 Tecnologias e Bibliotecas

- Python
- Pandas, NumPy
- Scikit-learn
- imbalanced-learn (SMOTE)
- Joblib
- Jupyter Notebook

---

## 📁 Estrutura

| Arquivo | Função |
|--------|--------|
| `ML_Risco_Credito_Train_e_Prev.ipynb` | Treina o modelo e salva com o scaler |
| `Prever_Inadimplencia_Novos_Clientes.ipynb` | Carrega modelo e aplica em novos dados |
| `credit_card_default.csv` | Base de dados com atributos de clientes |
| `novos_clientes.csv` | Dados simulados de novos clientes |
| `modelo_risco_credito.pkl` | Modelo treinado salvo |
| `scaler_risco_credito.pkl` | Scaler salvo para padronizar novos dados |
| `clientes_com_previsoes.csv` | Resultado da previsão |
| `requirements_ML.txt` | Dependências do projeto |

---

## 🚀 Como Executar

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/risco-credito-ml.git
cd risco-credito-ml
```

2. Instale os requisitos:
```bash
pip install -r requirements_ML.txt
```

3. Execute:
- `ML_Risco_Credito_Train_e_Prev.ipynb` → treina o modelo
- `Prever_Inadimplencia_Novos_Clientes.ipynb` → aplica o modelo em novos dados

---

## 📊 Resultados

- Modelo treinado com SMOTE e Regressão Logística
- Acurado em prever risco de inadimplência com base em histórico e perfil financeiro
- Resultados salvos em `clientes_com_previsoes.csv` com:
  - `prob_inadimplencia`: probabilidade prevista
  - `inadimplente_previsto`: classe (0 = adimplente, 1 = inadimplente)

---

## 👩‍💻 Autora

**Márcia Bayardino Weyne**  
📍 Rio de Janeiro – Brasil  
🔗 [LinkedIn](https://www.linkedin.com/in/marcia-bayardino-weyne)  
🔗 [GitHub](https://github.com/mbweyne)

---

## ✅ Observações

Este projeto é parte do meu portfólio em Data Science e demonstra domínio de modelagem preditiva, pipelines de ML, tratamento de dados desbalanceados e entregáveis profissionais.

## 👤 Autora

**Márcia Bayardino Weyne**  
📍 Rio de Janeiro - Brasil  
🔗 [LinkedIn](https://www.linkedin.com/in/marcia-bayardino-weyne)  
🔗 [GitHub](https://github.com/mbweyne)
