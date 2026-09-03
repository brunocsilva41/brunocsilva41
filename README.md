# Bruno Silva
**Full Stack Engineer | AI Orchestration & SaaS Architect**

[![Open to Work](https://img.shields.io/badge/Status-Open_to_Work-22c55e?style=for-the-badge&logo=target&logoColor=white)](https://www.linkedin.com/in/dev-bruno-silva)
[![Portfolio](https://img.shields.io/badge/Portfólio_3D-portfolio--bruno.bcs--consult.me-7928CA?style=for-the-badge&logo=googlechrome&logoColor=white)](https://portfolio-bruno.bcs-consult.me/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dev--bruno--silva-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dev-bruno-silva)
[![GitHub](https://img.shields.io/badge/GitHub-brunocsilva41-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/brunocsilva41)
[![Email](https://img.shields.io/badge/Email-brunocesar.social%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:brunocesar.social@gmail.com)

---

### 🚀 Visão Profissional
Engenheiro de Software com foco na convergência entre **Sistemas Distribuídos / SaaS de Alta Performance** e **Inteligência Artificial Autônoma**. Experiência sólida no desenvolvimento de ponta a ponta: da modelagem de dados, arquiteturas multi-tenant e engines em tempo real, até orquestração de agentes autônomos via MCP (Model Context Protocol) e desktop automation com foco em segurança.

| 🏗️ Enterprise SaaS | 🤖 AI & Agentic Systems | ⚡ Real-Time & Systems | 🛠️ DevTools & Infra |
| :--- | :--- | :--- | :--- |
| Next.js (App Router), NestJS, Clean Architecture, Multitenancy e RBAC. | Orquestração de Agentes (Agents Hub), MCP Servers, LLMs (Claude, Gemini, OpenAI) e RAG. | Engines multiplayer (WebSockets / Colyseus), Desktop Agents em Rust (fail-closed) e Middlewares. | Docker, CI/CD (GitHub Actions), automações CLI e observabilidade. |

---

### 🎯 Projetos Autorais em Destaque

> *Todos os projetos listados abaixo foram concebidos e implementados de forma 100% autoral.*

#### 🤖 [Agents Hub](https://github.com/brunocsilva41/Agents-Hub)
**Control Plane para Orquestração e Monitoramento de Múltiplos Agentes de IA**
- **Problema que resolve:** Elimina a complexidade e a fragmentação ao orquestrar múltiplos agentes autônomos em diferentes modelos de LLM.
- **Diferenciais:** Daemon operacional com persistência de memórias de sessão, governança de chamadas, versionamento de prompts e integração multi-provedor (Claude, OpenAI, Codex).
- **Tech Stack:** `TypeScript` `Node.js` `Model Context Protocol (MCP)` `Docker` `LLM APIs`

#### 🛡️ [ControlPC](https://github.com/brunocsilva41/ControlPC)
**Desktop Agent Seguro em Rust para Interação e Controle do Sistema Operacional**
- **Problema que resolve:** Permite que agentes de IA interajam e controlem o ambiente desktop com garantias rigorosas de segurança.
- **Diferenciais:** Arquitetura *security-first (fail-closed)*, resolução semântica de alvos visuais na interface do Windows e verificação contínua de foco.
- **Tech Stack:** `Rust` `TypeScript` `Vite` `Windows Native API` `Desktop Automation`

#### 🏋️ [gymOS — Ultimate Fitness OS](https://github.com/brunocsilva41/gymOS)
**Plataforma SaaS Completa para Gestão de Redes e Academias de Alto Rendimento**
- **Problema que resolve:** Centraliza a operação, controle de acessos, cobrança recorrente e retenção de alunos em uma plataforma moderna e responsiva.
- **Diferenciais:** Monorepo escalável com isolamento lógico multi-tenant, billing automatizado, treinos digitalizados e dashboards analíticos de MRR e churn.
- **Tech Stack:** `Next.js 14 (App Router)` `NestJS` `Prisma ORM` `PostgreSQL` `TailwindCSS` `TurboRepo` `Docker` `Jest & Playwright`

#### 🎮 [TrioOnline](https://github.com/brunocsilva41/TrioOnline)
**Multiplayer Real-Time Game Engine & Web Platform**
- **Problema que resolve:** Versão online do jogo de cartas Trio, viabilizando partidas competitivas em tempo real com baixa latência e alta estabilidade.
- **Diferenciais:** Engine de jogo autoritativa e determinística baseada em ticks, sincronização via WebSockets (Colyseus), persistência de estado em Redis e deploy contínuo em Kubernetes com ArgoCD.
- **Tech Stack:** `TypeScript` `React / Next.js` `Colyseus` `Redis` `PostgreSQL` `Prisma` `Docker`

#### 🔌 [MCP Server Database](https://github.com/brunocsilva41/mcp-server-database)
**Servidor MCP para Acesso e Análise Segura de Bancos de Dados por IAs**
- **Problema que resolve:** Viabiliza consultas e análises de LLMs diretamente em bancos relacionais (MySQL e SQL Server) sem risco de comandos destrutivos.
- **Diferenciais:** Validação sintática multi-estágio via AST parsing, sandbox de queries somente-leitura e suporte flexível a transports (Stdio / SSE).
- **Tech Stack:** `TypeScript` `Node.js` `MySQL` `MSSQL` `Model Context Protocol (MCP)` `Winston`

#### 🌌 [Portfólio 3D — Constelação Interativa](https://github.com/brunocsilva41/Portifolio-BrunoSilvaDev) • [Live Demo](https://portfolio-bruno.bcs-consult.me/)
**Experiência WebGL Imersiva com Shaders GLSL e Navegação Espacial 3D**
- **Problema que resolve:** Apresentação interativa de portfólio que transforma repositórios e habilidades em corpos celestes navegáveis no espaço 3D.
- **Diferenciais:** Shaders GLSL customizados, física de órbita calculada em tempo real, transições cinemáticas e modo de exploração livre.
- **Tech Stack:** `JavaScript` `Three.js` `GLSL Shaders` `CSS3D` `Vite` `Vercel`

#### 🔧 [AI Terminal Tools](https://github.com/brunocsilva41/ai-terminal-tools)
**Conjunto CLI Unificado para Produtividade e Ferramentas Locais de IA**
- **Problema que resolve:** Unifica comandos e automações de múltiplos ecossistemas de IA (Gemini, Claude, OpenAI) diretamente no terminal de trabalho.
- **Diferenciais:** Perfis configuráveis de ativação por projeto, checagens automatizadas e CI/CD matricial via GitHub Actions.
- **Tech Stack:** `JavaScript` `Node.js` `Python` `CLI Tools` `GitHub Actions`

#### ☕ [Café Gourmet](https://github.com/brunocsilva41/cafe-gourmet-react) & [API Café Gourmet](https://github.com/brunocsilva41/api-cafe-gourmet)
**E-commerce Full Stack de Ponta a Ponta (TCC Ciência da Computação)**
- **Problema que resolve:** Trabalho de Conclusão de Curso cobrindo todo o fluxo de um e-commerce: cardápio dinâmico, carrinho, pedidos e autenticação.
- **Tech Stack:** `React` `Node.js` `Express` `REST API` `Vercel`

---

### 💼 Experiência & Engenharia Corporativa
**Experiência Recente como Desenvolvedor Full Stack na Valiant Group (04/2025 – 08/2026):**
- **Middleware Fiscal & Integração ERP:** Desenvolvimento do núcleo de middleware para sincronização contínua com o ERP Linx e processamento automatizado de documentos fiscais eletrônicos (NF-e, NFS-e, CT-e), otimizando o tempo de resposta e validação de regras fiscais.
- **Agente de Conectividade Windows:** Construção de agente de alta disponibilidade em C#/.NET (Windows Service) com máquina de estados resiliente e túneis VPN WireGuard dedicados para comunicação segura com servidores on-premise de clientes.
- **Backoffice & Arquitetura Multi-Tenant:** Implementação e evolução de painel administrativo em PHP/Laravel com isolamento de dados por cliente, exportação analítica e controle de acesso granular baseado em papéis (RBAC).

---

### 📊 Master Tech Stack

| Categoria | Stack & Ferramentas |
| :--- | :--- |
| **Linguagens** | ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white) |
| **Frontend & WebGL** | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) |
| **Backend & APIs** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white) ![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white) ![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white) |
| **Bancos & Mensageria** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white) |
| **AI & Orquestração** | ![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75C2?style=for-the-badge&logo=googlegemini&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-007ACC?style=for-the-badge&logo=model-context-protocol&logoColor=white) ![RAG](https://img.shields.io/badge/RAG_&_LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) |
| **Infra & DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![GitHub_Actions](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white) ![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) |

---

### 📈 GitHub Ecosystem Stats
<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=brunocsilva41&show_icons=true&theme=dracula&hide_border=true" alt="GitHub Stats" height="180" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=brunocsilva41&layout=compact&theme=dracula&hide_border=true" alt="Top Langs" height="180" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=brunocsilva41&theme=dracula&hide_border=true" alt="GitHub Streak" height="180" />
</p>

---

### 📬 Conecte-se Comigo
- **Status Atual:** 🟢 **Disponível para novas oportunidades** (Open to Work — Remoto / Híbrido em São Paulo e região)
- **LinkedIn:** [linkedin.com/in/dev-bruno-silva](https://www.linkedin.com/in/dev-bruno-silva)
- **Portfólio 3D:** [portfolio-bruno.bcs-consult.me](https://portfolio-bruno.bcs-consult.me/) • [Código Fonte](https://github.com/brunocsilva41/Portifolio-BrunoSilvaDev)
- **Email:** [brunocesar.social@gmail.com](mailto:brunocesar.social@gmail.com)

---
<p align="center">
  <i>"Construindo soluções robustas através de engenharia rigorosa e inteligência autônoma."</i>
</p>
