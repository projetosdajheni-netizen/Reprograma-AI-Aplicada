# Semana 08 — Dados Avançados: Do Bruto ao Insight

**Formação:** Todas em Tech — IA Aplicada | {reprograma}  
**Status:** ✅ Atividade em grupo desenvolvida

## 🎯 Objetivo

Aplicar técnicas de preparação, limpeza, análise e visualização de dados para identificar padrões de comportamento e transformar resultados em recomendações estratégicas.

## 💻 Projeto — Renda Mensal e Fidelização no Delivery

**Grupo 2 — Claudia, Evana e Jhenifer**

**Pergunta central:** A faixa de renda mensal influencia o comportamento de quem realiza pedidos de delivery online?

O grupo analisou um dataset compartilhado de pedidos de comida online, investigando a relação entre renda mensal e intenção de realizar novos pedidos.

## 🧹 Preparação e limpeza dos dados

Com apoio do Claude, o grupo realizou:

- Identificação de 103 registros duplicados em uma base de 388 linhas.
- Remoção das duplicatas, resultando em 285 registros.
- Identificação e exclusão de uma coluna sem nome que duplicava os dados de `Output`.
- Correção de inconsistências de formatação em latitude e longitude.
- Padronização da categoria `Self Employeed` para `Self Employed`.

## 📊 Resultados

| Faixa de renda mensal | Registros | Intenção de recompra |
|---|---:|---:|
| Sem renda | 131 | 85,5% |
| Até Rs. 10.000 | 19 | 78,9% |
| Rs. 10.001–25.000 | 36 | 75,0% |
| Rs. 25.001–50.000 | 52 | 63,5% |
| Acima de Rs. 50.000 | 47 | 63,8% |

A análise identificou uma associação entre faixas de renda mais elevadas e menor intenção declarada de recompra.

As duas faixas de renda mais altas representavam aproximadamente 35% da base analisada.

## 🎯 Recomendações estratégicas

### Persona A — Operação

Investigar os motivos do feedback negativo na faixa de renda até Rs. 10.000, que apresentou 36,8% de avaliações negativas.

A proposta foi priorizar a identificação das causas e estabelecer um processo ágil de recuperação do atendimento.

### Persona B — Negócio

Concentrar a investigação e os testes de retenção nas faixas de renda acima de Rs. 25.000, que apresentaram menor intenção de recompra.

Entre as ações propostas:

- Pesquisa qualitativa para compreender a baixa intenção de recompra.
- Benefícios de fidelização segmentados.
- Testes A/B antes de ampliar as iniciativas.

## 🛠️ Ferramentas e métodos

- Claude para diagnóstico e limpeza dos dados.
- Análise exploratória e segmentação de clientes.
- Visualização comparativa de indicadores.
- Priorização por impacto e esforço.
- Construção de recomendações para operação e negócio.

## 💡 Competências desenvolvidas

- Tratamento e qualidade de dados.
- Identificação de duplicatas e inconsistências.
- Análise de dados por segmentos.
- Interpretação de indicadores.
- Visualização e storytelling de dados.
- Pensamento estratégico orientado ao negócio.
- Colaboração em equipe.

## 📚 Aprendizados

A atividade demonstrou a importância de preparar os dados antes de interpretá-los e de transformar padrões identificados em hipóteses e decisões de negócio.

Também reforçou que diferenças observadas entre grupos não comprovam, isoladamente, uma relação de causa e efeito.

**O valor da análise de dados está em transformar informações confiáveis em decisões que possam ser testadas e aprimoradas.**

## 💬 Feedback da mentora

**Jessica Alves — 12 de outubro**

A mentora avaliou positivamente a apresentação do Grupo 2 e confirmou que os resultados numéricos estavam consistentes com a base de dados após a limpeza.

Também destacou a priorização das recomendações por esforço e impacto, reconhecendo uma abordagem estratégica próxima à atuação de consultoria.

**Oportunidade de melhoria:** aprimorar a etapa de padronização dos dados, identificando espaços extras em valores categóricos, como `Negative ` na coluna `Feedback`.

### Aprendizado a partir do feedback

A experiência reforçou que a qualidade de uma análise depende não apenas dos cálculos e das visualizações, mas também da atenção aos detalhes durante a preparação dos dados.

Para análises futuras, o processo de limpeza deve incluir a verificação de espaços em branco, inconsistências de escrita e padronização de categorias antes da consolidação dos resultados.
