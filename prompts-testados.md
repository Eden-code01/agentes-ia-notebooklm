# 🧪 Histórico de Testes de Prompts — Engenharia de Prompts

> Registro completo das iterações de prompts testados no NotebookLM.
> Formato: Versão → Problema → Solução → Aprendizado

---

## Teste #1 — Definição de AI Agent

| Campo | Detalhe |
|-------|---------|
| **Data** | Março 2026 |
| **Objetivo** | Obter definição clara e fundamentada de AI Agent |
| **Fonte alvo** | Todas |

### v1 (Prompt inicial)
```
O que é um AI Agent?
```
**Avaliação:** ❌ Ruim  
**Problema:** Resposta genérica, misturou IA geral com agentes. Não citou fontes.

### v2 (Refinado com contexto)
```
Com base nas fontes carregadas, explique o que diferencia um AI Agent 
de um modelo de linguagem tradicional.
```
**Avaliação:** 🟡 Médio  
**Melhora:** Começou a citar fontes, mas ainda superficial.

### v3 (Final aprovado)
```
Com base nas fontes carregadas, explique o que diferencia um AI Agent de 
um modelo de linguagem tradicional. Use o padrão ReAct como exemplo 
central e cite pelo menos 2 fontes diferentes.
```
**Avaliação:** ✅ Ótimo  
**Resultado:** Resposta bem estruturada, com citações corretas e exemplo do ReAct.

**🎯 Aprendizado:** Especificar o exemplo central + pedir múltiplas fontes força maior profundidade.

---

## Teste #2 — Comparação de Frameworks

| Campo | Detalhe |
|-------|---------|
| **Data** | Março 2026 |
| **Objetivo** | Comparar LangGraph, CrewAI e AutoGen |
| **Fonte alvo** | Fontes 3 e 4 |

### v1 (Prompt inicial)
```
Compare os principais frameworks de AI Agents.
```
**Avaliação:** ❌ Ruim  
**Problema:** Mencionou frameworks NÃO presentes nas fontes (BabyAGI, AgentGPT). Mistura de conhecimento interno e das fontes.

### v2 (Com restrição de fonte)
```
Compare LangGraph e CrewAI usando apenas as Fontes 3 e 4. Se alguma 
informação não estiver disponível nas fontes, diga explicitamente.
```
**Avaliação:** ✅ Ótimo  
**Resultado:** Comparação honesta, indicou lacunas de cobertura.

**🎯 Aprendizado (CRÍTICO):** Sempre incluir "use apenas as fontes disponíveis" em prompts comparativos. O NotebookLM pode vazar conhecimento externo sem avisar.

---

## Teste #3 — Geração de Glossário

| Campo | Detalhe |
|-------|---------|
| **Data** | Março 2026 |
| **Objetivo** | Criar glossário técnico dos termos das fontes |
| **Fonte alvo** | Todas |

### v1
```
Liste os termos técnicos importantes.
```
**Avaliação:** ❌ Ruim  
**Problema:** Listou apenas 6 termos sem definições.

### v2 (Final aprovado)
```
Crie um glossário completo com TODOS os termos técnicos relevantes 
encontrados nas fontes. Para cada termo: (1) nome, (2) definição em 1-2 
frases, (3) qual fonte menciona o termo. Organize em ordem alfabética.
```
**Avaliação:** ✅ Excelente  
**Resultado:** 18 termos com definições e referências.

**🎯 Aprendizado:** "Todos os termos" + "ordem alfabética" + "qual fonte" produz resultados muito mais completos.

---

## Síntese dos Aprendizados de Engenharia de Prompts

| # | Princípio | Exemplo de Aplicação |
|---|-----------|---------------------|
| 1 | **Seja específico** | "explique X citando Y como exemplo" > "explique X" |
| 2 | **Restrinja às fontes** | Adicionar "use apenas as fontes disponíveis" |
| 3 | **Peça formato** | Tabela, lista numerada, glossário, flashcard |
| 4 | **Peça referências** | "cite qual fonte" ancora nas fontes reais |
| 5 | **Itere gradualmente** | Comece simples, adicione complexidade v1 → v2 → v3 |
| 6 | **Teste com "o que falta"** | "O que as fontes NÃO cobrem?" revela lacunas |
