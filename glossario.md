# 📘 Glossário — AI Agents e Sistemas Multi-Agentes

> Versão standalone do glossário para consulta rápida.

| Termo | Definição | Fonte |
|-------|-----------|-------|
| **AI Agent** | Sistema de IA que percebe, raciocina, planeja e age autonomamente em um ambiente | Survey (F2) |
| **ReAct** | Padrão de raciocínio que alterna entre Thought (reflexão) e Action (ação) em loop | ReAct Paper (F1) |
| **Tool Use / Function Calling** | Capacidade do modelo de chamar funções externas (APIs, buscas, código) | Anthropic (F3) |
| **Memória Vetorial** | Banco de dados que armazena informações como embeddings para recuperação semântica | Survey (F2) |
| **Orchestrator** | Agente responsável por coordenar e delegar tarefas para outros agentes | LangGraph (F4) |
| **Subagente** | Agente especializado que recebe tarefas do orquestrador e as executa | LangGraph (F4) |
| **Chain-of-Thought (CoT)** | Técnica onde o modelo "pensa em voz alta" antes de responder | ReAct Paper (F1) |
| **Human-in-the-Loop** | Ponto de controle onde um humano aprova ou rejeita a ação do agente | Anthropic (F3) |
| **Scaffolding** | Código externo ao LLM que gerencia o loop de execução do agente | Survey (F2) |
| **Agentic Loop** | Ciclo de percepção → planejamento → ação → observação de um agente | ReAct Paper (F1) |
| **Grounding** | Processo de ancorar as respostas da IA em fontes verificáveis | MIT Review (F5) |
| **Multi-Agent System (MAS)** | Arquitetura com múltiplos agentes de IA colaborando para resolver problemas complexos | LangGraph (F4) |
| **LangGraph** | Framework para construir agentes e fluxos multi-agentes como grafos de estado | LangGraph (F4) |
| **CrewAI** | Framework focado em equipes de agentes com papéis e objetivos definidos | MIT Review (F5) |
| **AutoGen** | Framework da Microsoft para agentes conversacionais multi-turno | MIT Review (F5) |
| **Embedding** | Representação numérica de texto em espaço vetorial para busca semântica | Survey (F2) |
| **RAG** | Retrieval-Augmented Generation — combina busca em base de conhecimento com geração de texto | Survey (F2) |
| **Tree-of-Thoughts** | Extensão do CoT que explora múltiplos caminhos de raciocínio em paralelo | Survey (F2) |
| **Prompt Chaining** | Padrão onde a saída de um prompt se torna entrada do próximo | Anthropic (F3) |
| **State Graph** | Grafo de estado usado pelo LangGraph para gerenciar o fluxo entre agentes | LangGraph (F4) |
