# Salut, je suis Thomas Jarrier 👋

### 🛠 Engineering Manager & Lead Tech → Ingénieur IA
**Backend & systèmes agentiques LLM** · Basé à **Nantes** 🇫🇷

J'accompagne les équipes tech sur les problèmes complexes : refonte d'architectures, décisions techniques structurantes et intégration de l'IA générative en production. Aujourd'hui, je vais délibérément au **cœur technique de l'IA** — je construis des systèmes agentiques à la main pour en maîtriser les mécanismes, pas seulement les frameworks.

> 💡 Ma conviction : **on apprend en construisant.** Chaque brique se valide par un build qui tourne et une éval mesurée — jamais par une doc lue.

---

### 🚀 En bref

- 🔭 **Aujourd'hui** : Engineering Manager chez **Anytime** (groupe Crédit Coopératif), en bascule vers un rôle d'**Ingénieur IA**.
- 🤖 **Focus actuel** : conception de **systèmes agentiques LLM** — orchestration (LangGraph), outillage d'agents (MCP), et évaluation rigoureuse.
- 🏗️ **Architecture** : Clean & Hexagonal Architecture, provider-agnostic, décisions tracées et argumentées.
- 👨‍🏫 **Transmission** : ancien enseignant vacataire à l'IUT de Laval (React, Vue.js, développement mobile) et mentor d'équipes.

---

### 🤖 Ingénierie IA — ce que je construis

Des systèmes LLM **codés à la main d'abord**, pour comprendre chaque abstraction avant de l'adopter :

- **Agents from scratch** : boucle **ReAct** sans framework (model + tool registry + gestion honnête des erreurs d'outil), tool-calling en *structured output* forcé.
- **Orchestration** : **LangGraph** (StateGraph, reducers custom, edges conditionnelles), persistance & checkpointing (`SqliteSaver`), **Human-in-the-Loop** (`interrupt` / `resume`), streaming, routing superviseur.
- **Outillage d'agents** : serveurs **MCP** (FastMCP) et clients, contrats de données **Pydantic** partagés, agents hybrides sync/async.
- **Patterns avancés** : réimplémentation OSS du pattern *Claude Code* (**DeepAgents**) — FS virtuel, planning, sous-agents typés & superviseur.
- **RAG** : indexation **Chroma** + embeddings, agent RAG câblé de bout en bout.
- **Évaluation** : harness **LLM-as-judge** (rubric multi-critères, sortie structurée), calibration vs labels humains, gates de non-régression.
- **Provider-agnostic** : OpenAI, **Google Gemini**, **Mistral** (angle RGPD/EU), modèles **locaux** (LM Studio) — approche *free-first*.

---

### 🧰 Stack technique

| Catégorie | Technologies & Outils |
| :--- | :--- |
| **IA / LLM** | ![Python](https://img.shields.io/badge/python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white) ![NestJS](https://img.shields.io/badge/nestjs-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Symfony](https://img.shields.io/badge/symfony-%23000000.svg?style=flat-square&logo=symfony&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=flat-square&logo=php&logoColor=white) |
| **Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB) |
| **DevOps & Infra** | ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=flat-square&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/ansible-%23EE0000.svg?style=flat-square&logo=ansible&logoColor=white) |
| **Leadership** | Roadmap & delivery · Décisions d'architecture · Mentoring & recrutement · Agile / DORA |

---

### 🌟 Projets & réalisations

- 🤖 **Montée en compétence IA (build-driven)** : une série de projets d'ingénierie LLM construits brique par brique — prompting → agents from scratch → LangGraph → MCP → DeepAgents → harness d'éval. Chaque phase se clôt par un build qui tourne.
- 📦 **[php-specification](https://github.com/tjarrier/php-specification)** : bibliothèque pour implémenter le *Specification Pattern* de manière fluide en PHP.
- 🐳 **[symfony-docker-image-to-ci](https://github.com/tjarrier/symfony-docker-image-to-ci)** : image Docker prête pour la CI d'applications Symfony / React.
- ⚙️ **Infrastructure as Code** : provisionnement **Terraform** et configuration **Ansible**.

---

### 🎯 Comment je travaille

- **Comprendre en profondeur** — maîtriser le *pourquoi* et les mécanismes, jamais copier-coller à l'aveugle.
- **Honnêteté technique** — un statut se prouve par le code, pas par une déclaration. Je distingue toujours ce qui est réellement construit de ce qui est cadré.
- **Décisions tracées** — chaque choix d'architecture est argumenté et documenté.
- **Bilingue** — français pour l'échange, anglais pour le technique (code, ADRs, identifiants).

---

### 📈 Statistiques GitHub

![Stats GitHub de Thomas](https://github-readme-stats.vercel.app/api?username=tjarrier&show_icons=true&theme=radical&count_private=true&hide_border=true)
![Langages les plus utilisés](https://github-readme-stats.vercel.app/api/top-langs/?username=tjarrier&layout=compact&theme=radical&hide_border=true)

---

### 📫 Me contacter

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thomas-jarrier-469208130)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/ellioudal)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jarriert@gmail.com)
