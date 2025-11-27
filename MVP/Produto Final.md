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

![Gráfico DEA CCR](https://github.com/Ludmilacarmo/LeanFlow/blob/main/Imagens/grafico%20ccr.jpeg)

---

## 🎯 Insights Gerais da Sprint 2

- Poucos portos atingiram eficiência total em **CCR**  
- Portos eficientes em BCC mas não em CCR mostram boa gestão com infraestrutura limitada  
- Diferenças entre os modelos revelam impacto da escala operacional  

---

# ⚓ Movimentação de Soja, Berços e Operações

![Dashboard Soja e Operações](https://github.com/Ludmilacarmo/LeanFlow/blob/main/Imagens/WhatsApp%20Image%202025-10-30%20at%2021.05.48.jpeg)

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
![Ocorrências 1](https://github.com/Ludmilacarmo/LeanFlow/blob/main/Imagens/Ocorr%C3%AAncias%20por%20Porto%20de%20Atraca%C3%A7%C3%A3o.png)

#### **Imagem 2 – Dashboard com filtro aplicado**
![Ocorrências 2](https://github.com/Ludmilacarmo/LeanFlow/blob/main/Imagens/sprint3.1%5D.png)

#### **Imagem 3 – *Filtro atualizado***  

![Ocorrências 3](https://github.com/Ludmilacarmo/LeanFlow/blob/main/Imagens/sprint3.2.png)

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
# 📄 **RELATÓRIO TÉCNICO – Análise de Exportações de Soja e Ocorrências Portuárias (ANTAQ)**
LINK PARA O CÓDIGO:(https://github.com/Ludmilacarmo/LeanFlow/blob/main/C%C3%93DIGO%20API/c%C3%B3digo%20API.ipynb)
## ✔ **1. Objetivo Geral do Código**

O código tem como objetivo:

**➤ Identificar e analisar os principais portos e terminais responsáveis pela exportação de soja no Brasil**, utilizando os dados públicos da **ANTAQ**, e  
**➤ Levantar e agrupar os motivos de paralisações (ocorrências)** relacionados às atracações desses mesmos portos.

Em resumo:

### 🔍 **O código descobre:**

- Quais portos mais exportam soja no Brasil (top 10)
- Quais são as atracações de soja nesses portos
- Quais paralisações ocorreram nessas atracações
- Quais são os principais motivos dessas paralisações
- O número de ocorrências e as horas totais de paralisação

---

# ✔ **2. Etapas do Código**

## **2.1. Montagem e Teste do Google Drive**

O código:

- Monta o Google Drive no Google Colab
- Testa se há permissão de escrita
- Define o caminho onde estão os dados da ANTAQ

Isso garante que toda a análise funcione sem erros de permissão.

---

# ✔ **2.2. Leitura dos dados de Carga (2015–2025)**

O código percorre as pastas:

```
/Dados API/ANTAQ/2015
/Dados API/ANTAQ/2016
...
/Dados API/ANTAQ/2025
```

E para cada ano:

- Abre o arquivo **Carga.txt**
- Padroniza o código de mercadoria
- Filtra apenas cargas **relacionadas à soja**

### 💡 Mercadorias de soja filtradas:

- 1201 → Soja em grão  
- 2304 → Tortas de soja  
- 1507 → Óleo de soja bruto  
- 1516 / 1517 → Gorduras/óleos vegetais  

Resultado:

👉 **Um dataframe unificado com todas as cargas de soja exportadas entre 2015 e 2025.**

---

# ✔ **2.3. Leitura dos Dados de Atracação**

A segunda parte do código:

- Lê os arquivos **Atracacao.txt** de todos os anos
- Junta tudo em um só dataframe
- Mantém informações como:
  - Porto de atracação  
  - Tipo de navegação  
  - Sentido (embarque/exportação)  
  - Identificador da atracação (IDAtracacao)

---

# ✔ **2.4. Fusão dos Dados (Carga + Atracação)**

A fusão é feita pela chave **IDAtracacao**, permitindo saber:

- Qual carga estava associada a qual atracação
- Qual porto movimentou a soja
- Qual foi o volume exportado
- Se foi navegação de longo curso (exportação internacional)

Essa parte filtra:

✔ Soja  
✔ Sentido = “Embarcados” (exportação)  
✔ Tipo Navegação = Longo Curso  

---

# ✔ **2.5. Identificação dos Top 10 Portos Exportadores de Soja**

O código agrupa por:

```
Porto Atracação
```

E soma o peso da carga de soja.

Resultado:

👉 Lista de **Top 10 portos/terminais que mais exportaram soja** entre 2015 e 2025.

---

# ✔ **2.6. Leitura dos Dados de Paralisações**

O código carrega os arquivos:

```
TemposAtracacaoParalisacao.txt
```

para cada ano, gerando:

- Motivos das paralisações  
- Duração de cada paralisação  
- Vinculação via IDAtracacao  

---

# ✔ **2.7. Selecionando apenas Paralisações dos Top 10 Portos**

Com base nos resultados anteriores:

- Seleciona só atracações de soja nos top 10 portos  
- Seleciona todas as paralisações relacionadas a essas atracações  

Depois, junta novamente as informações de porto para completar os dados.

---

# ✔ **2.8. Análise dos Motivos das Paralisações**

O código agrupa por:

```
Porto + Motivo da Paralisação
```

E calcula:

- Quantidade de ocorrências  
- Total de horas paradas  

Depois filtra apenas **os 5 principais motivos** por porto.

---

# ✔ **2.9. Exportação Final**

O relatório final é salvo em:

```
/content/paralisacoes_soja_top_portos_maiores.csv
```

Esse arquivo contém:

- Porto  
- Motivo  
- Quantidade de ocorrências  
- Total de horas paradas  

---

# 🎯 **3. Em Resumo – Para que serve o código?**

### O código tem 3 funções principais:

---

## **1️⃣ Identificar os portos que mais exportam soja no Brasil**

Com base nos dados da ANTAQ de 2015 a 2025.

---

## **2️⃣ Obter todas as ocorrências (paralisações) associadas a essas atracações**

Relacionando:

```
Atracação → Carga → Porto → Paralisação
```

---

## **3️⃣ Descobrir os principais motivos de paralisação por porto**

Inclui:

- ranking dos motivos  
- horas totais paradas  
- número de eventos  

Permite identificar:

### 🔥 **Gargalos logísticos na exportação de soja no Brasil**

---

#  **4. Aplicações Práticas**

Este código permite:

- análise logística de exportação  
- auditoria de operações portuárias  
- identificação de gargalos  
- análise de eficiência  
- estudos acadêmicos  
- geração de dashboards  
- preparação para modelos DEA  

---
# Reltório das Sprints
LINK PARA O relatório:(LINK PARA O CÓDIGO:(https://github.com/Ludmilacarmo/LeanFlow/blob/main/C%C3%93DIGO%20API/c%C3%B3digo%20API.ipynb)
## ✔ **1. Objetivo Geral do Código**)

---

# 🧠 Conclusão Geral

A Lean Flow consolidou **eficiência (Sprint 2)** e **operações (Sprint 3)** em um único produto robusto.  
O sistema combina **DEA + BI + dashboards operacionais**, fornecendo visão estratégica completa para gestão logística portuária.
