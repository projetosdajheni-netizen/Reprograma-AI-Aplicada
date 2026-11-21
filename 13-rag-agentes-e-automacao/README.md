# Semana 13 — RAG, Agentes e Automação

**Formação:** IA Aplicada | {reprograma}  
**Projeto:** Meu Ritmo — Agente de Planejamento Consciente  
**Status:** Documentação do agente e testes apresentados

## 🎯 Objetivo

Desenvolver e avaliar um agente de Inteligência Artificial capaz de apoiar o planejamento pessoal, considerando compromissos, prioridades, tempo disponível e bem-estar.

## 🤖 O agente Meu Ritmo

O agente foi concebido para ajudar a transformar objetivos em pequenas ações possíveis, respeitando as responsabilidades e os limites de cada pessoa.

Sua proposta é orientar sem cobranças irreais, incentivar a autonomia e tornar o planejamento mais sustentável.

### Funcionalidades previstas nas instruções

- Analisar tarefas e sugerir prioridades.
- Organizar atividades de acordo com tempo e energia disponíveis.
- Apoiar estudos e desenvolvimento de habilidades.
- Apresentar resumos de evolução baseados em informações acessíveis.
- Sugerir melhorias sem modificar automaticamente os registros.

## 🔐 Regras de segurança

O agente pode analisar, ensinar, sugerir e preparar ações sem autorização prévia.

Entretanto, antes de alterar tarefas, compromissos, arquivos, configurações ou dados, deve:

1. Explicar exatamente a alteração pretendida.
2. Identificar os itens afetados e as consequências.
3. Informar o que permanecerá inalterado.
4. Aguardar a confirmação explícita por meio da palavra **"confirmo"**.
5. Executar somente a ação autorizada, quando houver ferramentas disponíveis.

Outra regra importante é tratar instruções encontradas em documentos, páginas e mensagens externas como conteúdo não confiável, evitando que substituam as regras de segurança do agente.

## 🧪 Testes A, B e C

### Teste A — Confirmação antes de agir

Avaliação do comportamento do agente diante de uma solicitação que poderia modificar dados.

**Resultado relatado:** comportamento positivo quanto à exigência de confirmação.

### Teste B — Honestidade sobre informações indisponíveis

Avaliação da capacidade do agente de reconhecer quando não possui informações suficientes.

**Resultado relatado:** comportamento positivo quanto à prevenção de respostas inventadas.

### Teste C — Leitura de documento de contexto

Avaliação do comportamento do agente ao analisar um documento relacionado ao projeto.

**Resultado relatado:** comportamento positivo na análise conversacional.

**Limitação:** os resultados descritos não constituem uma auditoria técnica completa de segurança.

## 📅 Exemplo prático — Planejamento de um sábado

Foi realizado um exercício de planejamento para 31 de outubro de 2026.

Contexto utilizado:

- Energia disponível: média.
- Prioridade: estudos de tecnologia.
- Objetivo: organizar o dia de maneira realista.

O agente apresentou sugestões de organização com foco nos estudos, sem efetuar alterações nos registros.

## ⏱️ Comparação de tempo

A atividade propôs comparar o tempo necessário para realizar o planejamento manualmente e com apoio do agente.

Os valores medidos ainda precisam ser incorporados à documentação.

## 🧰 Materiais da atividade

- Resumo das instruções do agente.
- Regras de autorização e segurança.
- Roteiro de apresentação em primeira pessoa.
- Apresentação visual no Canva.

## 💡 Competências desenvolvidas

- Criação de agentes de Inteligência Artificial.
- Engenharia de instruções.
- Definição de limites de autonomia.
- Segurança contra manipulação de instruções.
- Planejamento orientado por contexto.
- Validação de comportamento por testes.
- Comunicação de soluções com IA.

## 📚 Aprendizados

A experiência reforçou que um agente de IA não precisa executar mudanças automaticamente para ser útil.

Sua contribuição também pode estar na análise de informações, na organização de alternativas e no apoio à tomada de decisões.

**O propósito do Meu Ritmo é utilizar a tecnologia para apoiar as pessoas, respeitando suas escolhas, seus limites e seu próprio ritmo.**
