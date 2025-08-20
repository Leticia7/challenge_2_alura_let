# 📈 Telecom X — Análise de Evasão de Clientes

## 🧠 Introdução

A empresa fictícia **Telecom X** enfrenta uma alta taxa de cancelamentos de clientes (churn) e precisa entender os fatores que influenciam esse comportamento.  
Este projeto tem como objetivo realizar um processo completo de **ETL (Extração, Transformação e Carga)** e aplicar uma **análise exploratória de dados** para investigar o perfil dos clientes que tendem a abandonar a empresa.  
A partir desses insights, serão propostas **ações estratégicas para retenção de clientes**.

---

## 💾 Fonte dos Dados

Os dados foram fornecidos em formato JSON, contendo informações sobre:

- Perfil do cliente (`gender`, `SeniorCitizen`, `tenure`, etc.)
- Tipo de contrato e pagamentos
- Serviços de internet e telefone contratados
- Status de churn (coluna alvo)

A base contém **+7000 registros únicos** e passou por um processo de **normalização e limpeza de dados**.

---

## ⚙️ Tecnologias Utilizadas

- Python 3
- Pandas & NumPy
- Seaborn & Matplotlib
- Jupyter Notebook

---

## 🔍 Etapas do Projeto

1. **Extração e normalização** do JSON original
2. **Tratamento e padronização** das colunas
3. **Criação de novas variáveis** relevantes para análise
4. **Análise descritiva geral**
5. **Estudo comparativo** entre clientes que permanecem e que cancelam
6. **Geração de visualizações**
7. **Identificação de padrões de churn**
8. **Conclusão e recomendações estratégicas**

---

## 📊 Principais Descobertas

- A taxa de churn é de **26,54%**
- Clientes que cancelam permanecem em média **18 meses** (mediana: 10)
- A maior parte dos cancelamentos ocorre nos **primeiros meses de contrato**
- **Contratos mensais** e **pagamentos manuais** concentram a maior parte dos cancelamentos
![Gráfico entre Churn e Método de Pagamento](images/grafico_churn_metodo_pagamento.png)
- Planos de **fibra óptica com mensalidades elevadas** apresentam alto churn
- **Serviços de segurança e suporte técnico** têm forte impacto positivo na retenção
![Gráfico entre Churn e Serviços de Internet](images/grafico_churn_servicos_internet.png)
---

## 🧩 Recomendações Estratégicas

- Atuar nos **primeiros meses** com ações de onboarding e engajamento
- Estimular **contratos de longo prazo** e **pagamento automático**
- Reavaliar a **proposta de valor dos planos premium**
- Promover serviços como **OnlineSecurity** e **TechSupport**

---

## ✅ Conclusão

A análise oferece uma visão clara sobre os principais fatores que influenciam a evasão de clientes na Telecom X. Esses insights podem ser usados para:

- Reforçar estratégias de retenção
- Otimizar ofertas e pacotes
- Desenvolver modelos preditivos para churn

---

## 🔮 Próximos Passos

- Construção de um **modelo de Machine Learning para previsão de churn**
- Criação de um **dashboard interativo** para monitoramento de métricas
- Desenvolvimento de uma **campanha de retenção baseada em perfis de risco**

---

## 📎 Autor

Bruno Ferrer  
[LinkedIn](https://www.linkedin.com/in/bruno-ferrer-49566230/) • [Portfólio](https://github.com/B-Ferrer)

---

