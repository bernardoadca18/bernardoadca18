<div align="center">

[English](README.md) | [Português](README.pt-br.md)

# Bernardo Alves Aguiar da Cunha  
### <span style="color: #4CAF50">Desenvolvedor Fullstack & Engenheiro de IA</span> | Sistemas RAG / LLM

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bernardo-alves-aguiar-da-cunha-b06364218)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bernardoadca18)

</div>

## Sobre Mim

Desenvolvedor fullstack e engenheiro de IA especializado em sistemas de IA Generativa e RAG production-grade — busca híbrida, reranking cross-encoder, arquiteturas multi-tenant — e orquestração multi-provedor de LLMs. Atuo como arquiteto e único desenvolvedor em todo o ciclo: levantamento de requisitos, arquitetura, implementação, deploy e correção de falhas em produção. Base sólida em backend com Python (FastAPI, SQLAlchemy async) e Java (Spring Boot), com ecossistema completo em TypeScript/React no frontend, além de React Native para mobile. Background complementar em DevOps, Docker e observabilidade (Prometheus/Grafana).

## Habilidades Técnicas

### **IA & RAG**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

### **Frontend**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### **Backend**
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

### **Banco de Dados**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### **DevOps & Outras Tecnologias**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

## Experiência Profissional

### **Desenvolvedor Fullstack & Engenheiro de IA**  
`Dez 2023 - Presente`

Arquiteto e único desenvolvedor em projetos independentes de ponta a ponta — do levantamento de requisitos e arquitetura até implementação, deploy e correção de falhas em produção — com foco em IA Generativa, RAG e infraestrutura de LLMs.

#### Projetos em Destaque:

- **any-assistant (RAG multi-domínio)**  
  Arquitetura RAG multi-domínio (FastAPI + React 19) com busca híbrida no Qdrant (vetores densos + esparsos/BM25), decomposição de queries via LLM e reranking cross-encoder. Inclui motor de ingestão Code-to-Doc que transforma código-fonte em documentação semântica de forma idempotente, com checkpoints SHA-256 para escala de dezenas de milhares de arquivos.

- **Faceless Content Engine (pipeline autônomo de vídeo)**  
  Sistema autônomo de produção de vídeos com pipeline assíncrono de 5 fases (ideação, roteirização, áudio, assets e renderização), orquestrando LLMs cloud e locais (Gemini, Ollama/Qwen), TTS zero-shot (F5-TTS) validado via Faster-Whisper (WER médio < 5%) e renderização programática com Remotion/React — reduzindo o trabalho manual do fluxo original em mais de 90%.

- **Gateway Unificado de LLMs (LiteLLM Proxy)**  
  Gateway de API production-grade em Docker que unifica múltiplos provedores de LLM sob um único endpoint OpenAI-compatible, com pooling de chaves de API (11x de aumento nos rate limits efetivos), fallback hierárquico e stack completa de observabilidade (Prometheus/Grafana).

- **CreditFlow (Plataforma de Gestão de Empréstimos)**  
  Arquitetei e desenvolvi sozinho um ecossistema completo de 4 aplicações — API REST, dashboard admin, portal institucional e app mobile — cobrindo desde a captação de clientes até o acompanhamento de parcelas. Backend Java/Spring Boot (Security/JWT, RBAC), frontends em Next.js, app mobile React Native/Expo, integração de pagamentos via PIX e trilha de auditoria. Operou em produção até a empresa cliente encerrar as atividades.

## Formação Acadêmica

- **Bacharelado em Ciência da Computação**  
  Centro Universitário Una | `Jan 2022 - Jul 2026 (Concluído)`

- **Curso de Desenvolvimento de Software**  
  Instituto de Gestão e Tecnologia da Informação (IGTI) | `Mai 2021 - Jul 2021`

## Certificações

- **AWS Academy Cloud Foundations** – Amazon Web Services
- **HCSA-VMS / HCSA-Access Control / HCSA-Alarm** – Hikvision

## Contato

- **Email:** bernardoalvesaguiar16@gmail.com  
- **LinkedIn:** [linkedin.com/in/bernardo-alves-aguiar-da-cunha-b06364218](https://www.linkedin.com/in/bernardo-alves-aguiar-da-cunha-b06364218)  
- **GitHub:** [github.com/bernardoadca18](https://github.com/bernardoadca18)

---
