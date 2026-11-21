# Semana 09 — Ética, Viés e Responsabilidade

**Formação:** IA Aplicada | {reprograma}  
**Status:** ✅ Projeto em grupo desenvolvido

## 🎯 Objetivo

Investigar possíveis vieses em decisões produzidas por Inteligência Artificial, avaliando a transparência dos critérios, a qualidade dos dados e os riscos de tratamento desigual.

## 💻 Projeto — Detetive de Viés: Auditoria de Cupons de Desconto

**Grupo:** Turma dos Descontos — Jhenifer, Letícia, Karol e Rilza.

**IA auditada:** Claude.

**Pergunta central:** A Inteligência Artificial trata clientes de maneira equivalente ao recomendar cupons de desconto?

O projeto simulou uma campanha de marketing para uma loja de roupas, acessórios e calçados, utilizando perfis fictícios de clientes.

## 🔎 Identificação de possíveis vieses

Na primeira análise, o Claude sugeriu descontos diferentes com base em informações insuficientes.

Entre os exemplos:

- Elisa, 18 anos, estudante: 15% de desconto.
- Mauro, 36 anos, analista de TI: 8% de desconto.
- Carla, 56 anos: 12% de desconto.
- Letícia, 26 anos: 12% de desconto.

Ao questionar os critérios, identificamos que a IA havia utilizado suposições sobre idade, ocupação, bairro e variedade de categorias compradas, sem conhecer o histórico financeiro dos clientes.

A investigação demonstrou que a diversidade de produtos adquiridos não comprova maior volume de compras ou maior valor gasto.

## 🧪 Auditoria e testes

O grupo realizou 20 testes em conversas separadas com o Claude:

- 10 perfis com idades entre 25 e 45 anos.
- 10 perfis com idades a partir de 65 anos.
- Mesmo histórico de compras e mesmo pedido.
- Apenas a idade foi alterada.

**Resultados:**

| Indicador | 25–45 anos | 65 anos ou mais |
|---|---:|---:|
| Receberam 10% de desconto | 10 de 10 | 10 de 10 |
| Receberam condição de compra mínima | 2 de 10 | 6 de 10 |

Não houve diferença no percentual de desconto, mas houve maior frequência de condições de compra mínima para os perfis mais velhos.

O resultado foi considerado um padrão que merece investigação adicional, sem comprovar discriminação.

## ⚖️ Riscos identificados

- Tratamento desigual entre clientes.
- Uso de características pessoais como substitutas de informações financeiras.
- Decisões sem justificativa mensurável.
- Riscos relacionados à privacidade e à LGPD.
- Impactos financeiros e reputacionais para o negócio.

## 🛡️ Recomendações

1. Utilizar critérios comportamentais, como recência, frequência e valor das compras.
2. Evitar utilizar idade, bairro e ocupação como critérios indiretos de potencial de consumo.
3. Implementar revisão humana antes da liberação dos cupons.
4. Monitorar diferenças nas condições e nos percentuais oferecidos.
5. Manter um plano alternativo baseado em regras simples e transparentes.

**Veredito do grupo:** lançar a campanha com ajustes, condicionando sua utilização a critérios justificáveis e supervisão humana.

## 💡 Competências desenvolvidas

- Ética aplicada à Inteligência Artificial.
- Identificação de vieses algorítmicos.
- Pensamento crítico e questionamento de respostas de IA.
- Construção de testes comparativos.
- Avaliação de riscos.
- Privacidade e proteção de dados.
- Governança e supervisão humana.
- Trabalho colaborativo.

## 📚 Aprendizados

A atividade demonstrou que uma resposta aparentemente lógica pode esconder pressupostos sem evidências.

O uso responsável da Inteligência Artificial exige questionar como uma decisão foi construída, quais dados foram utilizados e se pessoas com comportamentos equivalentes recebem tratamento equivalente.

**Uma IA não deve ser considerada justa apenas porque apresenta uma justificativa convincente. Suas decisões precisam ser testadas.**
