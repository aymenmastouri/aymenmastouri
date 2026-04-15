# Hi, I'm Aymen

## AI Solution Architect | Berlin

Solution Architect with 10+ years of experience in enterprise IT architecture, project delivery, and technical leadership. Currently building AI-powered platforms and running them on self-hosted Kubernetes infrastructure.

### What I work with

**AI/ML:** LiteLLM, Ollama, RAG, Prompt Engineering, Vector Search (Qdrant), LLM Observability (Langfuse), Experiment Tracking (MLflow)

**Languages:** Python, Java, TypeScript

**Cloud & Infra:** Kubernetes (k3s), ArgoCD (GitOps), Traefik, cert-manager, Sealed Secrets, Prometheus, Grafana, Loki, Alertmanager

**Architecture:** C4 Model, Arc42, TOGAF, iSAQB

### Featured Projects

| Project | Description |
|---------|------------|
| [SDLC Pilot](https://github.com/aymenmastouri/aicodegencrew) | AI-powered SDLC automation — analyzes codebases, generates architecture docs (C4/Arc42), plans development work. 9-phase pipeline, 745+ tests, on-premises ready. |

### AI Lab Platform

Self-hosted sovereign AI platform running on k3s with full GitOps (ArgoCD App-of-Apps):

| Layer | Components |
|-------|-----------|
| **SSO** | Authentik (OIDC/SAML) |
| **LLM Runtime** | Ollama + LiteLLM Proxy |
| **AI Tools** | Open WebUI, SDLC Pilot, Langfuse, MLflow |
| **Data** | Qdrant (Vector DB), PostgreSQL |
| **Observability** | Prometheus, Grafana, Alertmanager, Loki + Promtail |
| **Infra** | k3s, ArgoCD, Traefik, cert-manager, Sealed Secrets |

12 HTTPS endpoints, automated TLS, auto-sync with self-heal.

### Architecture Decisions I Can Talk About

- **Pipeline+LLM over Multi-Agent**: Why single LLM calls beat agent loops (0% loops, 2x faster, 3x fewer tokens)
- **Evidence-First RAG**: Why LLMs should never guess about code — deterministic facts first, LLM synthesis second
- **GitOps for AI Infra**: Managing 10+ AI services with ArgoCD sync-waves and App-of-Apps
- **On-Prem AI**: Running LLMs, vector stores, and full observability on a single VPS

### Let's connect

- [LinkedIn](https://linkedin.com/in/aymen-mastouri)
- Email: aymen@aymenmastouri.io
