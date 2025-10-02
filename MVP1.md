# 📌 MVP - Lean Flow: Smart Solutions for Logistics Challenges

## 🎯 Objetivo do MVP
> Desenvolver uma plataforma de Business Intelligence (BI) para analisar a eficiência portuária nos portos brasileiros.  
- **Problema resolvido:** Falta de informações consolidadas e comparativas sobre eficiência de terminais portuários.  
- **Hipótese validada:** É possível usar dados da ANTAQ e modelos DEA para medir e comparar a eficiência portuária.  
- **Valor entregue:** Apoio a gestores e analistas na tomada de decisão com base em indicadores claros de produtividade, tempo de operação e motivos de paralisações.  

---

## 📝 Descrição da Solução
> O MVP consiste em um dashboard de BI com indicadores de eficiência portuária.  
- **Funcionalidades principais:**  
  - Banco de dados centralizado com informações da ANTAQ  
  - Limpeza, padronização e tratamento de dados inconsistentes  
  - Cálculo de eficiência via DEA (CCR e BCC)  
  - Ranking de portos por eficiência  
  - Visualização em mapa e filtros por ano/porto  

- **Limitações conhecidas:**  
  - Análise restrita aos dados públicos da ANTAQ  
  - Modelos estatísticos limitados a CCR e BCC nesta fase inicial  

- **Escopo reduzido (essencial para validação):**  
  - Importar, tratar e visualizar dados básicos de eficiência  
  - Entregar insights iniciais em dashboards  

---

## 👥 Personas / Usuários-Alvo
- **Analista de Dados:** Precisa consolidar, limpar e analisar dados portuários.  
- **Gestor Portuário:** Necessita de indicadores de eficiência e comparativos para tomada de decisão.  
- **Usuário Final (público em geral):** Deseja visualizar quais portos são mais/menos eficientes.  

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | Como analista, quero criar um banco de dados para facilitar o acesso aos dados. | Alta       | 5 pontos   |
| US2 | Como analista, quero importar dados brutos da ANTAQ para iniciar as análises. | Alta       | 5 pontos   |
| US3 | Como analista, quero limpar e padronizar dados inconsistentes.              | Alta       | 8 pontos   |
| US4 | Como gestor, quero calcular a eficiência portuária usando DEA CCR.          | Média      | 5 pontos   |
| US5 | Como gestor, quero calcular a eficiência portuária usando DEA BCC.          | Média      | 5 pontos   |
| US6 | Como analista, quero visualizar um ranking de eficiência dos portos.        | Média      | 3 pontos   |
| US7 | Como usuário, quero visualizar os portos mais/menos eficientes em um mapa.  | Média      | 3 pontos   |
| US8 | Como gestor, quero analisar causas e duração de paralisações.               | Baixa      | 5 pontos   |
| US9 | Como gestor, quero acompanhar a evolução ao longo de 10 anos.               | Baixa      | 8 pontos   |
| US10| Como gestor, quero analisar tendências e previsões futuras.                 | Baixa      | 8 pontos   |
| US11| Como usuário, quero filtrar dados por porto e ano.                          | Baixa      | 3 pontos   |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status        |
|--------|----------------------------------------------|---------------|
| 01     | Criar banco de dados, importar e padronizar dados ANTAQ | Concluído     |
| 02     | Implementar modelos DEA (CCR e BCC) e ranking de portos | Em andamento |
| 03     | Identificar causas/duração de paralisações, evolução histórica e previsões | Futuro        |
| 04     | Dashboard final com filtros e mapa interativo | Futuro        |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir importar e padronizar dados da ANTAQ  
- O sistema deve calcular a eficiência dos portos com DEA CCR e BCC  
- Deve ser possível visualizar um ranking de eficiência  
- O usuário deve conseguir aplicar filtros por ano e porto  

---

## 📈 Métricas de Validação
- Número de usuários que testaram o dashboard  
- Feedback de gestores e analistas sobre clareza dos indicadores  
- Indicadores de negócio: % de uso da plataforma, tempo médio de acesso e engajamento  

---

## 🚀 Próximos Passos
- Implementar visualização em mapa interativo  
- Adicionar análise de causas e tempos de paralisação  
- Criar módulo de tendências e previsões  
- Expandir métricas para outros indicadores logísticos  
