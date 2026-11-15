# André Vinícius Diz Freitas

**Engenharia de Software & IA Generativa | Sistemas Multi-Agente, Machine Learning & Sistemas Distribuídos**

- 🏛️ **Estagiário em Engenharia de Software** no **Tribunal de Contas da União (TCU)**
- 🔬 **Pesquisador de Iniciação Científica / Extensão** na **UEFS** (Sistemas de Recomendação com LSH Forest & MinHash)
- 🚀 **Google Student Ambassador 2026** & **Finalista Nacional do 13º Campus Mobile** (Instituto Claro / LSITEC)
- 🎓 Bacharelado em Engenharia da Computação — **UEFS**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-andrevnc-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/andrevnc)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-TheAndr3-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/TheAndr3)
[![Portfolio](https://img.shields.io/badge/Portfolio-andrevnc.dev-111111?style=flat-square&logo=vercel)](https://andrevnc.dev)

---

## 🤖 IA Generativa, Agentes & Machine Learning

| Projeto | Stack & Conceitos | Links |
| :--- | :--- | :--- |
| **[Comanda](https://github.com/TheAndr3/comanda)** | Orquestração multi-agente para pós-venda de delivery (Claude Agent SDK, MCP, regras financeiras em código, guardrails determinísticos, BM25 + Snowball PT do zero e avaliação estilo τ-bench com 30 cenários, 8 adversariais e `pass³`). | [ Código & 29 ADRs](https://github.com/TheAndr3/comanda) · [ Replay (Vercel)](https://comanda-blond.vercel.app) · [ Dataset (HF)](https://huggingface.co/datasets/TheAndr3/comanda-delivery-support-eval-ptbr) |
| **[LSH Forest & MinHash Recommender](https://huggingface.co/TheAndr3/lsh-forest-clinical-recommender)** | Motor de recomendação por Filtragem Colaborativa Baseada no Usuário em produção (`l=200`, `k=20`), arquitetura *Memory-First* com Cache LRU em RAM (~200ms em *warm start*), inferência em lote (300 pacientes/chamada) e degradação graciosa em 4 níveis. | [ Modelo & Código (HF)](https://huggingface.co/TheAndr3/lsh-forest-clinical-recommender) |
| **Redes Neurais & IA Clássica do Zero** | Implementações fundamentais em Python sem frameworks caixa-preta: [**Multilayer Perceptron (Backpropagation)**](https://github.com/TheAndr3/multilayer-perceptron), [**Mapas de Kohonen (SOM)**](https://github.com/TheAndr3/kohonen-iris-plants), [**Adaline (Regra Delta LMS)**](https://github.com/TheAndr3/adaline_valvulas), [**Perceptron**](https://github.com/TheAndr3/perceptron-oil-problem), [**Controlador Fuzzy**](https://github.com/TheAndr3/controlador_fuzzy) e [**Algoritmo Genético**](https://github.com/TheAndr3/Algoritmo-Genetico). | [ Repositórios](https://github.com/TheAndr3?tab=repositories) |

---

## ⚙️ Backend & Sistemas Distribuídos

- **[Flow](https://github.com/TheAndr3/flow)** (`Elixir`, `Phoenix`, `Broadway`, `Oban`, `PostgreSQL`): Pipeline de ingestão e processamento assíncrono de telemetria com *batching*, *backpressure*, jobs persistentes e observabilidade em tempo real.
- **[SignalDesk](https://github.com/TheAndr3/SignalDesk)** (`NestJS`, `TypeScript`, `PostgreSQL`, `Jest`): API multi-tenant com autenticação JWT, autorização baseada em papéis (RBAC), transações e controle de concorrência contra condições de corrida.
- **[Sistema Distribuído de Recarga (2PC)](https://github.com/TheAndr3/Blockchain-Redes)** (`Go`, `Gin`, `MQTT/Mosquitto`, `Docker`): Serviços distribuídos concorrentes coordenando reservas via protocolo **Two-Phase Commit (2PC)** (*prepare, commit, abort*).

---

## 🛠️ Tecnologias Principais

- **IA & Dados:** `Python`, `Claude Agent SDK`, `MCP`, `Gemini API`, `Ollama`, `BM25`, `LSH Forest / MinHash`, `Avaliação de LLMs (τ-bench / LLM-as-a-Judge)`
- **Backend & Concorrência:** `TypeScript / Node.js`, `NestJS`, `Next.js`, `FastAPI`, `Go`, `Elixir / OTP`, `Phoenix`, `Java / Spring Boot`, `Apex / PL/SQL`
- **Bancos, Testes & Infra:** `PostgreSQL`, `SQLite`, `MongoDB`, `Docker`, `MQTT`, `Pytest`, `Vitest`, `Jest`, `ExUnit`, `GitHub Actions CI/CD`