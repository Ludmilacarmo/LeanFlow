# 🚢 Lean Flow – Plataforma Integrada de Eficiência e Operações Portuárias  
 Produto Final Consolidado

---

# 📊 Visão Geral do Produto Final

A **Lean Flow** é uma plataforma de **Business Intelligence (BI)** desenvolvida para analisar, comparar e monitorar a eficiência portuária no Brasil.  
O sistema utiliza:

-Dados públicos e oficiais da ANTAQ

-Modelos matemáticos DEA (CCR e BCC)

-Dashboards interativos

-Análises operacionais e monitoramento de gargalos

-Indicadores de eficiência, movimentação e ocorrências

Integra modelos DEA (CCR e BCC), dados públicos da ANTAQ e dashboards operacionais, incluindo análises de paradas e ocorrências por porto de atracação.

---

# 🎯 Objetivo Geral

Oferecer um sistema inteligente capaz de:

- Medir eficiência portuária com rigor técnico  
- Identificar gargalos logísticos  
- Entregar dashboards interativos  
- Apoiar decisões estratégicas em operações portuárias  

---

# 💡 Hipótese Validada

A aplicação de DEA (CCR e BCC) aos dados da ANTAQ permite medir eficiência portuária de forma objetiva, comparável e auditável.

---


# 🧩 Estrutura Geral do MVP

| Item | Detalhe |
|------|---------|
| 🎯 Problema | Falta de dados consolidados e comparativos sobre eficiência portuária |
| ✅ Hipótese Validada | DEA aplicado à ANTAQ permite medir eficiência objetivamente |
| 💡 Valor Entregue | Indicadores de produtividade, movimentação e operações |

### Componentes do MVP

- Extração de dados ANTAQ  
- Tratamento e padronização  
- Modelos DEA CCR e BCC  
- Dashboards interativos de eficiência  
- Dashboards de movimentação (soja, berços, operações)  
- Dashboards operacionais (paradas e ocorrências por porto)  

---

# 📅 Sprint 2 – Modelos DEA e Dashboard de Eficiência

## 🔧 Entregas
| Entrega | Status |
|--------|:-----:|
| Modelo DEA CCR | ✅ |
| Modelo DEA BCC | ✅ |
| Ranking de Eficiência | ✅ |
| Dashboard CCR x BCC | ✅ |
| Integração com dados operacionais | ✅ |

---

# 📈 Resultados da Sprint 2

## ⚙️ Modelo BCC – Eficiência dos Portos
Avalia eficiência considerando **retornos variáveis de escala**.

Permite entender:

- Impacto da gestão

- Performance relativa por tamanho

- Portos eficientes mesmo com infraestrutura menor

![Gráfico DEA BCC](https://github.com/Ludmilacarmo/LeanFlow/blob/main/Imagens/Grafico%20bbc.jpeg)

---

## ⚙️ Modelo CCR – Eficiência dos Portos
Avalia produtividade com **retornos constantes de escala**.

Avalia:

- Produtividade total

- Eficiência global do sistema

![Gráfico DEA CCR](img_dea_ccr.png)

---

## 🎯 Insights Gerais da Sprint 2

- Poucos portos atingiram eficiência total em **CCR**  
- Portos eficientes em BCC mas não em CCR mostram boa gestão com infraestrutura limitada  
- Diferenças entre os modelos revelam impacto da escala operacional  

---

# ⚓ Movimentação de Soja, Berços e Operações

![Dashboard Soja e Operações](img_soja_operacoes.png)

### 🔍 Destaques
- **344 berços**  
- **406 mil operações**  
- **948 bilhões de toneladas** movimentadas  
- Santos lidera movimentação  
- Manaus lidera operações  
- Itaqui e Santarém: eficiência elevada com menor estrutura  

---

# 🚢 Sprint 3 – Ocorrências e Gargalos Operacionais

---

# 📊 Dashboard – Ocorrências por Porto de Atracação

### 📌 Imagens anexadas:

#### **Imagem 1 – Dashboard completo**
![Ocorrências 1](dashboard_ocorrencias_1.png)

#### **Imagem 2 – Dashboard com filtro aplicado**
![Ocorrências 2](dashboard_ocorrencias_2.png)

#### **Imagem 3 – *Nova imagem atualizada***  

![Ocorrências 3](dashboard_ocorrencias_novo.png)

---

## 🔹 Máximo de Ocorrências
O painel indica dinamicamente o maior valor de ocorrências entre os portos filtrados.

## 🔹 Comparativo Entre Portos
Portos apresentados no gráfico:

- Itaqui  
- Paranaguá  
- São Francisco do Sul  
- Terminal Bianchini  
- Terminal de Tubarão  
- TIPLAM  

## 🔹 Legenda e Estrutura Visual
- Legenda por complexo portuário  
- Tooltip com informações do porto, complexo e total de ocorrências  
- Filtro lateral para múltiplas seleções  

---

# 📝 Insights da Sprint 3

### 🔸 Portos Críticos
- Paranaguá ultrapassa **160 mil ocorrências**  
- Indica atrasos e alta demanda

### 🔸 Portos Estáveis
- Itaqui  
- Tubarão  
- TIPLAM  

### 🔸 Distribuição Assimétrica
Sugere necessidade de reforço operacional em pontos críticos.

---

# 🧩 Entregáveis da Sprint 3

| Entrega | Status |
|--------|:-----:|
| Painel completo de ocorrências | ✅ |
| Indicador dinâmico | ✅ |
| Comparativo entre portos | ✅ |
| Legenda dinâmica | ✅ |
| Filtros avançados | ✅ |

---

# 🗂️ User Stories Consolidadas

| ID | Descrição | Status |
|----|-----------|:-----:|
| US4 | Calcular eficiência CCR | ✅ |
| US5 | Calcular eficiência BCC | ✅ |
| US6 | Ranking de eficiência | ✅ |
| US7 | Painel de ocorrências | ✅ |
| US8 | Destacar valor máximo | ✅ |
| US9 | Comparação entre portos | ✅ |
| US10 | Filtros por porto e complexo | ✅ |

---

# 🧠 Conclusão Geral

A Lean Flow consolidou **eficiência (Sprint 2)** e **operações (Sprint 3)** em um único produto robusto.  
O sistema combina **DEA + BI + dashboards operacionais**, fornecendo visão estratégica completa para gestão logística portuária.
