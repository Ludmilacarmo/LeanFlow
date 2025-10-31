# 📊 Lean Flow – Smart Solutions for Logistics Challenges

🚀 Plataforma de Business Intelligence (BI) para análise e monitoramento da eficiência portuária no Brasil, utilizando dados da ANTAQ e modelos DEA (CCR e BCC).

---

## 🎯 Objetivo do MVP

Desenvolver um sistema para **medir e visualizar eficiência portuária**, identificando gargalos e apoiando a tomada de decisão em logística.

| Item | Detalhe |
|------|--------|
| 🎯 Problema | Falta de dados consolidados e comparativos sobre eficiência portuária |
| ✅ Hipótese Validada | DEA aplicado à ANTAQ permite medir eficiência objetivamente |
| 💡 Valor Entregue | Indicadores de produtividade, movimentação e operações |

---

## 🧩 Estrutura do MVP

- Extração de dados públicos (ANTAQ)
- Tratamento e padronização dos dados
- Implementação dos Modelos DEA (CCR e BCC)
- Dashboards interativos com eficiência e movimentação

---

## 📅 Sprint 2 – Modelos DEA e Dashboards

### 🔧 Entregas

| Entrega | Status |
|--------|:-----:|
| Modelo DEA CCR | ✅ |
| Modelo DEA BCC | ✅ |
| Ranking de Eficiência | ✅ |
| Dashboard CCR x BCC | ✅ |
| Integração com dados de soja, berços e operações | ✅ |

---

## 📈 Resultados Sprint 2

### ⚙️ Modelo BCC – Eficiência dos Portos de Atracação

> Permite análise sob retornos variáveis de escala.

📊 Gráfico DEA BCC:  
![Eficiência BCC](imagens/dashboard_bcc.png)

---

### ⚙️ Modelo CCR – Eficiência dos Portos de Atracação

> Avalia produtividade sob retornos constantes de escala.

📊 Gráfico DEA CCR:  
![Eficiência CCR](imagens/dashboard_ccr.png)

---

### 🎯 Insights Gerais

- Poucos portos atingiram eficiência total em **CCR**
- Diferenças entre CCR e BCC mostram **efeito de escala**
- Portos eficientes no BCC mas não no CCR → **boa gestão, infraestrutura limitada**

---

## ⚓ Movimentação de Soja e Estrutura Portuária

📊 Dashboard:  
![Dashboard Soja e Operações](imagens/dashboard_soja_operacoes.png)

🔍 Destaques:

- **344** berços no total
- **406 mil** operações registradas
- **948 bilhões de toneladas** movimentadas
- **Santos** lidera movimentação e berços
- **Manaus** lidera operações
- **Itaqui** e **Santarém** mostram alta eficiência mesmo com estrutura menor

---

## 🛑 Sprint 3 – Paradas Operacionais e Gargalos

📊 Dashboard:  
![Paradas e Operações](imagens/dashboard_paradas_operacoes.png)

Insights:

- **41 complexos portuários analisados**
- Chuva = maior causa de parada (**237 mil horas**)
- Vila do Conde – Belém = alta demanda + paradas → gargalo crítico
- Base para melhoria operacional e previsão de desempenho

---

## 🗂️ User Stories

| ID | Descrição | Status |
|----|-----------|:-----:|
| US4 | Calcular eficiência CCR | ✅ |
| US5 | Calcular eficiência BCC | ✅ |
| US6 | Ranking de eficiência | ✅ |
| US7 | Visualizar portos eficientes em mapa | 🔄 Em desenvolvimento |

---

## ✅ Critérios de Aceitação

- Dashboards interativos e funcionais
- Comparação de eficiência entre portos
- Indicadores operacionais integrados

---

## 🔮 Próximos Passos

- Histórico de eficiência (últimos 10 anos)
- Modelos preditivos
- Dashboard com mapa dinâmico
- Expansão para outros tipos de carga

---


## 🧠 Conclusão

A Sprint 2 concluiu a validação técnica do MVP com sucesso, provando que **BI + DEA** é uma ferramenta estratégica para decisões portuárias.

---
