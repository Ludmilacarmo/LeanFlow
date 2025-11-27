## Lean Flow – Análise de Eficiência Portuária com BI e DEA
 
Product Owner: Vinicius Messias  
LinkedIn: https://www.linkedin.com/in/vinicius-silva-5b2763302/
 
Scrum Master: Yasmin Aureliano  
LinkedIn: https://www.linkedin.com/in/yasmin-fraz%C3%A3o-096a53300/
 
Team Member: Ludmila de Mello  
LinkedIn: https://www.linkedin.com/in/ludmila-de-mello-2132b22ba/
 
Team Member: Arthur Araujo  
LinkedIn: https://www.linkedin.com/in/arthur-anacleto54/
 
Team Member: Enzo Bragadin  
LinkedIn: https://www.linkedin.com/in/enzo-bragadin-collavito-montenegro-891053264/
 
Github:  
https://github.com/ViniciusMeSilva
 
Professor M2 / Orientador: Marcus Nascimento  
Professor P2: Newton Yamada
 
## Resumo
 
Este relatório busca apresentar de forma breve e objetiva o desenvolvimento e os resultados obtidos na Sprint 2 do projeto Lean Flow, que tem como objetivo analisar a eficiência portuária no Brasil por meio de Business Intelligence (BI) aliado à metodologia Data Envelopment Analysis (DEA). Nesta entrega, avançamos na exploração e no tratamento dos dados disponibilizados pela ANTAQ, ao mesmo tempo em que realizamos os primeiros testes com os modelos DEA CCR e BCC para avaliação dos portos selecionados.
 
A etapa atual contou com a consolidação da base de dados, estudos sobre a metodologia DEA e a aplicação de cálculos preliminares, o que permitiu gerar uma primeira versão dos dashboards com análises de eficiência, movimentação e desempenho operacional. Com isso, foi possível identificar diferenças entre os modelos CCR e BCC, compreender as limitações estruturais e operacionais dos portos e aprofundar o entendimento sobre o impacto da escala nas operações portuárias.
 
Além disso, o grupo iniciou o desenvolvimento da análise de movimentação da soja, tema de importância estratégica para o escoamento de commodities brasileiras. Também foram incluídas análises complementares de operações portuárias e paradas operacionais, contribuindo para uma visão mais abrangente das operações portuárias no Brasil.
 
Concluímos que a combinação entre BI e DEA é uma abordagem eficiente para a análise portuária e possui potencial para evoluir com a aplicação de séries históricas, comparação entre portos e integração com indicadores logísticos adicionais.
 
Palavras-chave: Eficiência portuária; DEA; Logística; ANTAQ; Business Intelligence.
 
## 1. Introdução
 
Este relatório apresenta o desenvolvimento da Sprint 2 do projeto Lean Flow, que tem como objetivo aplicar Business Intelligence (BI) e técnicas de análise de eficiência, como a metodologia Data Envelopment Analysis (DEA), para avaliar o desempenho dos portos brasileiros a partir de dados fornecidos pela Agência Nacional de Transportes Aquaviários (ANTAQ).
 
A eficiência portuária é um tema de extrema relevância no cenário logístico brasileiro, considerando que grande parte das exportações e importações do país dependem da infraestrutura portuária. Entretanto, os portos brasileiros apresentam diferentes capacidades, níveis de automatização e gargalos operacionais, o que impacta diretamente a competitividade das cadeias logísticas.
 
Com o avanço dos estudos na Sprint 2, foi possível explorar a base de dados portuários, integrar informações de movimentação, estrutura e operações e aplicar cálculos iniciais com os modelos DEA CCR e BCC. Tais modelos permitem mensurar a eficiência relativa de unidades tomadoras de decisão — neste caso, os portos — com base em insumos (inputs) e produtos (outputs).
 
O relatório também engloba uma análise de movimentação da soja, produto que representa significativa fatia das exportações brasileiras, além de análises complementares envolvendo operações portuárias e tempos de parada.
 
## 2. Objetivos
 
Apresentar os objetivos de forma clara e direta:
 
1. Mensurar a eficiência dos portos brasileiros utilizando DEA (CCR e BCC);
2. Explorar e tratar a base de dados disponibilizada pela ANTAQ;
3. Desenvolver dashboards interativos que permitam visualizar informações de eficiência, movimentação e desempenho portuário;
4. Compreender os fatores que mais influenciam a eficiência portuária;
5. Iniciar análises complementares sobre movimentação da soja e outros indicadores portuários.
 
## 3. Métodos Analíticos
 
Este tópico aborda os métodos e técnicas utilizados para realizar as análises do projeto. Cada método deve ser fundamentado com base científica.
 
• DEA CCR: modelo clássico de retornos constantes de escala, aplicável quando a unidade de análise opera com eficiência proporcional ao aumento dos recursos.  
• DEA BCC: modelo de retornos variáveis de escala, adequado para unidades com diferenças estruturais ou de porte.  
• Power BI: plataforma utilizada para construção dos dashboards e visualização de dados.  
• Python: para coleta, tratamento e estruturação dos dados — utilizando bibliotecas como Pandas e Numpy.
 
Cada um dos métodos mencionados deve ser descrito com detalhes na versão final do relatório, conforme orientação do professor.
 
## 4. Tecnologias da Informação
 
As Tecnologias da Informação aplicadas neste projeto tiveram como propósito apoiar a coleta, organização, análise e visualização dos dados da ANTAQ. Nesta seção devem ser descritas:
 
• Power BI — ferramenta escolhida para visualização dos indicadores, geração de dashboards e integração de múltiplas bases;  
• Python — utilizado no processo de tratamento e análise de dados antes da importação para o Power BI;  
• RStudio — quando aplicável, especialmente em análises estatísticas específicas ou validações adicionais.
 
O grupo também deve explicar como cada ferramenta foi utilizada no projeto, dificuldades encontradas e justificativas de uso.
 
## 5. Dados
 
Nesta seção descrevemos os dados utilizados no projeto. É necessário apresentar: quais dados foram coletados, como foram tratados, em que período, fontes (incluindo ANTAQ), além de possíveis limitações identificadas.
 
A Sprint 2 utilizou dados de movimentação de cargas, estrutura portuária, operações, paradas e informações gerais dos portos. Esses dados passaram por limpeza, padronização e integração para permitir a aplicação dos modelos DEA.
 
Devem ser citadas análises, diferenças encontradas entre os modelos CCR e BCC e limitações dos portos, como falta de estrutura compatível, gargalos operacionais e efeitos de escala.
 
## 6. Tratamento dos Dados
 
Descrever o processo de tratamento, limpeza e padronização dos dados.  
• Remoção de registros nulos  
• Padronização de unidades  
• Agregação de dados por porto/período  
• Identificação e tratamento de outliers  
• Preparação da base para cálculos DEA
 
## 7. Resultados Esperados
 
Os membros do grupo devem descrever, com base nas análises realizadas na Sprint 2, quais são os resultados esperados:
 
• Identificação dos portos mais eficientes segundo DEA CCR e BCC;  
• Análise da movimentação de soja;  
• Identificação de gargalos logísticos;  
• Compreensão da relação entre estrutura portuária, escala e eficiência;  
• Desenvolvimento de dashboards com múltiplos indicadores;  
• Contribuições acadêmicas a partir da literatura estudada.
 
## 8. Métodos e Referências Bibliográficas
 
Nesta seção, o grupo deve apresentar a fundamentação teórica dos métodos aplicados. O professor forneceu uma tabela como exemplo, que deve ser preenchida com os autores pesquisados.
 
Exemplo de tabela preenchida:
 
Autor(es) | Métodos de análise | Dados utilizados | Principais conclusões  
Castillo-Manzano (2010) | Regressão linear e modelo PROBIT-LOGIT | 20383 observações | O tempo de espera no terminal antes do embarque tem um impacto significativo na disposição para consumo; gastos aumentam com o tempo de espera.  
Fasone, Kofler e Scuderi (2016) | Econometria | 60 observações | O aumento no número de companhias de baixo custo impacta negativamente os gastos; maior número de passageiros causa congestionamento.  
Yokomi, Wheat e Mizutani (2017) | Regressão logarítmica | 238 observações | Conclusões semelhantes sobre impacto das companhias de baixo custo; passageiros de baixo custo passam menos tempo no terminal.
 
## 9. Referências
 
Bezerra, G. C. L.; Gomes, C. F. The effects of service quality dimensions and passenger characteristics on passenger’s overall satisfaction with an airport. Journal of Air Transport Management, v. 44-45, p. 77-81, May-June, 2015. Disponível em: <http://dx.doi.org/10.1016/j.jairtraman.2015.03.001>. Acesso em: 18 jan. 2019.
 
Castillo-Manzano, J. I. Determinants of commercial revenues at airports: lessons learned from Spanish regional airports. Tourism Management, v. 31, n. 6, p. 788-796, 2010.
 
Chung, Y.S. Hedonic and utilitarian shopping values in airport shopping behavior. Journal of Air Transport Management 49, 28–34, 2015.
 
Del Chiappa, G.; Martin, J. C.; Roman, Concepcion. Service quality of airports’ food and beverage retailers: a fuzzy approach. Journal of Air Transport Management, v. 53, p. 105-113, 2016.
 
Secretaria de Aviação Civil. Research methodology for operational performance and passenger satisfaction. Disponível em: <https://centroestudos.aer...QUISA_ SATISFACAO/METODOLOGIA_2018_-_v.0.0.pdf/>, 2019.
 
