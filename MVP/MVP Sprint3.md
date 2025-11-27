# 🚢 Sprint 3 – Análise de Ocorrências por Porto de Atracação

Plataforma Lean Flow – *Business Intelligence aplicado à eficiência logística portuária*

---

## 🎯 Objetivo da Sprint

Desenvolver um painel dedicado à **análise do número de ocorrências por porto de atracação**, permitindo:

- Identificar gargalos operacionais  
- Destacar portos críticos  
- Comparar desempenho entre unidades portuárias  
- Apoiar decisões de priorização e alocação de recursos  

A sprint entregou uma visualização clara e objetiva sobre a distribuição das ocorrências, permitindo avaliar comportamentos operacionais em diferentes contextos filtrados.

---

## 📊 Dashboard – Ocorrências por Porto de Atracação

![Ocorrências por Porto de Atracação](https://github.com/Ludmilacarmo/LeanFlow/blob/main/Imagens/Ocorr%C3%AAncias%20por%20Porto%20de%20Atraca%C3%A7%C3%A3o.png)
![Ocorrências por Porto de Atracação](https://github.com/Ludmilacarmo/LeanFlow/blob/main/Imagens/Ocorr%C3%AAncias%20por%20Porto%20de%20Atraca%C3%A7%C3%A3o.png)
![Ocorrências por Porto de Atracação](https://github.com/Ludmilacarmo/LeanFlow/blob/main/Imagens/Ocorr%C3%AAncias%20por%20Porto%20de%20Atraca%C3%A7%C3%A3o.png)

Os painéis apresentam:

---

### 🔹 Máximo de Ocorrências

O dashboard destaca dinamicamente o **maior valor de ocorrências** entre os portos selecionados.


O valor muda conforme os filtros aplicados, permitindo análises segmentadas por porto ou complexo portuário.

---

### 🔹 Comparativo Entre Portos

O gráfico de barras apresenta a **soma total de ocorrências**, permitindo avaliações rápidas entre portos como:

- Itaqui  
- Paranaguá  
- São Francisco do Sul  
- Terminal Bianchini (Terbian)  
- Terminal de Tubarão  
- TIPLAM  

A legenda destaca o **complexo portuário**, e o comportamento do gráfico se adapta à seleção feita pelo usuário.

---

### 🔹 Legenda por Complexo Portuário

A legenda dinâmica permite identificar:

- Quais complexos possuem maior concentração de ocorrências  
- Como as operações se distribuem entre regiões portuárias  

Isso facilita análises segmentadas por áreas de atuação e auxilia na priorização de ações de melhoria.

- Legenda exibindo o complexo portuário correspondente às barras.
- Tooltip dinâmico que mostra:
  - Porto Atracação  
  - Complexo Portuário  
  - Soma de Ocorrências
- Filtro lateral “Porto Atracação” permitindo selecionar múltiplos terminais:
  - Itaqui  
  - Paranaguá  
  - São Francisco do Sul  
  - Terbian  
  - Terminal de Tubarão  
  - TIPLAM  

### ✔ Composição visual
A captura apresenta uma interface clara, com:

- Fundo translúcido que melhora a visualização do gráfico  
- Estrutura dividida entre indicador, gráfico, legenda e filtros  
- Layout moderno e coerente com dashboards portuários  

---

## 📝 Insights Extraídos

### 🔸 1. Portos Críticos
Paranaguá apresenta mais de **160 mil ocorrências** no dataset completo, evidenciando:

- Alta demanda operacional  
- Possíveis atrasos  
- Gargalos significativos  

### 🔸 2. Portos Estáveis
Portos como:

- Itaqui  
- Tubarão  
- TIPLAM  

mostram valores menores de ocorrências, indicando maior estabilidade operacional ou menor volume de movimentação.

### 🔸 3. Variação Dinâmica pelo Filtro

O painel se adapta ao filtro selecionado, alterando:

- O porto com maior número de ocorrências  
- A distribuição visual entre os portos  
- A interpretação sobre gargalos ou estabilidade  

### 🔸 4. Distribuição Assimétrica

A assimetria na quantidade de ocorrências sugere:

- Necessidade de reforço operacional em portos críticos  
- Ações de redistribuição de equipes  
- Revisão de processos e turnos  
- Ajustes de infraestrutura nos locais mais impactados  

---

## 🧩 Entregáveis da Sprint 3

| Entrega | Status |
|--------|:-----:|
| Painel completo de ocorrências por porto | ✅ |
| Indicador dinâmico do maior valor | ✅ |
| Gráfico comparativo entre portos | ✅ |
| Legenda dinâmica por complexo portuário | ✅ |
| Filtros por porto e complexo | ✅ |

---

## 🗂️ User Stories Relacionadas

| ID | Descrição | Status |
|----|-----------|:-----:|
| US8 | Criar painel de ocorrências por porto | ✅ |
| US9 | Destacar automaticamente o valor máximo | ✅ |
| US10 | Comparar portos por soma de ocorrências | ✅ |
| US11 | Implementar filtros por porto e complexo | ✅ |


---

## 🧠 Conclusão

A Sprint 3 entrega uma visão robusta sobre como as ocorrências se distribuem entre diferentes portos, destacando gargalos, assimetrias operacionais e necessidades de melhoria.

---
