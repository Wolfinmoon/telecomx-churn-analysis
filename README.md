# 📊 Telecom X - Análise de Evasão de Clientes (Churn)

Bem-vindo(a)! Este projeto faz parte de um desafio de Data Science com foco em **análise de churn**, ou seja, evasão de clientes. Utilizando Python e bibliotecas de ciência de dados, o objetivo é identificar padrões e fatores que contribuem para o cancelamento de contratos na empresa fictícia **Telecom X**.

---

## 🎯 Objetivo

Investigar o comportamento dos clientes e entender quais variáveis influenciam a evasão, auxiliando a empresa a:

- Reduzir o churn
- Fidelizar clientes
- Otimizar decisões estratégicas

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 🧩 Estrutura do Projeto

```
📁 TelecomX_Churn_Analysis
├── TelecomX_Data.json              # Base de dados original (JSON)
├── TelecomX_Dataset_Transformado.csv  # Dados tratados
├── TelecomX_BR.ipynb              # Notebook completo com ETL, EDA e relatório final
├── README.md                      # Este arquivo
```

---

## 🔍 O que foi feito

### 1. Extração
- Carregamento da base de dados em JSON via `pandas.json_normalize`.

### 2. Transformação
- Limpeza de dados inconsistentes ou nulos.
- Conversão de colunas numéricas e criação de novas variáveis como `Contas_Diarias`.

### 3. Carga e Análise
- Análise descritiva com médias, medianas, desvios padrão.
- Análises gráficas comparando churn com variáveis categóricas e numéricas.

### 4. Relatório Final
- Insights estratégicos para reduzir o churn.
- Recomendações claras para ações futuras.

---

## 📈 Resultados e Insights

- Contratos mensais apresentam maior taxa de cancelamento.
- Clientes com menos de 12 meses de uso são os mais propensos a sair.
- Pagamento via débito automático reduz churn.
- Serviços extras como suporte técnico ajudam a fidelizar.

---

## 🧪 Como Executar o Projeto

1. Faça o clone do repositório:
```bash
git clone https://github.com/seu-usuario/telecomx-churn-analysis.git
```

2. Instale as bibliotecas necessárias:
```bash
pip install pandas matplotlib seaborn
```

3. Abra o notebook no [Google Colab](https://colab.research.google.com/) ou localmente com Jupyter Notebook.

4. Siga as etapas comentadas no notebook `TelecomX_BR.ipynb`.

---

## ❗ Possíveis Problemas

- Ao rodar localmente, verifique se o arquivo JSON está no mesmo diretório do notebook.
- Pode ocorrer `SettingWithCopyWarning` (corrigido com `.loc[]` no código).

---

## 🏁 Conclusão

Este projeto reforça a importância da análise de dados no apoio à tomada de decisões e mostra como identificar clientes com maior risco de cancelamento é essencial para a estratégia de uma empresa.

---
