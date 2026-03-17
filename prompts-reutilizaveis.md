# 🔁 Biblioteca de Prompts Reutilizáveis — AI Agents

> Use estes prompts no NotebookLM ou em qualquer ferramenta de IA para revisar e aprofundar o tema.

---

## 🟢 Nível Iniciante — Compreensão e Definição

```
Defina AI Agent em no máximo 3 parágrafos, usando linguagem acessível 
para alguém que conhece programação mas nunca estudou IA. 
Use exemplos das fontes carregadas.
```

```
Qual é a diferença entre um chatbot simples e um AI Agent? 
Liste pelo menos 5 diferenças concretas em formato de tabela.
```

```
Explique o conceito de "loop agêntico" (agentic loop) com um diagrama 
em formato texto (ASCII art) mostrando o ciclo Perceber → Planejar → 
Agir → Observar.
```

---

## 🟡 Nível Intermediário — Componentes e Arquitetura

```
Descreva em detalhes os 4 componentes de um AI Agent: Memória, 
Planejamento, Ferramentas e Ação. Para cada um, dê 2 exemplos de 
implementação do mundo real e cite a fonte onde encontrou essa informação.
```

```
O que é o padrão ReAct? Mostre um exemplo de raciocínio ReAct completo 
(com Thought, Action e Observation) para a tarefa de "pesquisar e resumir 
as 3 principais novidades em AI da última semana".
```

```
Compare as topologias de sistemas multi-agentes: Rede, Supervisor e 
Hierárquica. Em qual situação cada uma seria mais adequada?
```

---

## 🔴 Nível Avançado — Crítica e Aplicação

```
Quais são os principais riscos de segurança em sistemas multi-agentes 
em produção? Organize por: (1) riscos técnicos, (2) riscos de negócio, 
(3) riscos éticos. Cite evidências das fontes.
```

```
Projete uma arquitetura multi-agente para automatizar o processo de 
onboarding de novos funcionários em uma empresa. Defina: número de 
agentes, papel de cada um, ferramentas necessárias, ponto de supervisão 
humana e potenciais falhas.
```

```
Segundo as fontes, quando a Anthropic recomenda NÃO usar agentes? 
Quais são os critérios para escolher entre um pipeline determinístico 
simples e um sistema agêntico complexo?
```

---

## 🔵 Prompts de Revisão e Consolidação

```
Crie um mapa mental em formato de lista hierárquica sobre AI Agents, 
cobrindo todos os tópicos das fontes. Use 3 níveis de profundidade.
```

```
Gere 10 flashcards sobre AI Agents no formato:
FRENTE: [pergunta]
VERSO: [resposta]
Cubra tanto conceitos teóricos quanto aplicações práticas.
```

```
Faça um quiz de 5 questões de múltipla escolha com 4 alternativas cada, 
baseado exclusivamente no conteúdo das fontes. Inclua gabarito comentado.
```

```
Identifique 3 contradições ou tensões conceituais entre as fontes 
carregadas. Como você conciliaria essas diferentes perspectivas?
```

---

## 🛠️ Prompts para Troubleshooting

> Use quando a resposta não estiver boa o suficiente.

**Se a resposta estiver muito genérica:**
```
Sua resposta anterior foi genérica. Por favor, refaça sendo mais específico 
e citando explicitamente em qual fonte (nome e seção) você encontrou 
cada informação.
```

**Se o modelo incluiu informação externa às fontes:**
```
Você incluiu informações que podem não estar nas fontes carregadas. 
Por favor, refaça usando APENAS o conteúdo disponível nas fontes. 
Se algum ponto não tiver cobertura, escreva explicitamente: 
"Essa informação não está nas fontes disponíveis."
```

**Se precisar de mais profundidade:**
```
Expanda o item [X] da sua resposta anterior com 3x mais detalhes, 
incluindo exemplos concretos e referências às fontes.
```

**Se quiser simplificar:**
```
Reescreva sua última resposta como se fosse explicar para alguém 
com 15 anos, sem jargão técnico. Use analogias do cotidiano.
```
