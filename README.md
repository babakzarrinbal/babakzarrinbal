### Babak Zarrinbal

Cloud & Platform Engineer — Kubernetes, GitOps, LLM Infrastructure. Düsseldorf, Germany.

14+ years in software, 10+ years leading engineering teams. Currently building multi-cloud
(Azure/GCP) Kubernetes platforms and agentic AI systems at Douglas. Active upstream
contributor to [kgateway](https://github.com/kgateway-dev/kgateway) (CNCF Envoy-based
API/AI Gateway).

**[zarrinbal.org](https://zarrinbal.org)** · **[Résumé (PDF)](./resume.pdf)** · [LinkedIn](https://www.linkedin.com/in/babak-zarrinbal/) · [babak.zarrinbal@gmail.com](mailto:babak.zarrinbal@gmail.com)

---

**Open source — kgateway (CNCF)**

- [PR #14231](https://github.com/kgateway-dev/kgateway/pull/14231) — fixed XListenerSet status validation *(merged)*
- [PR #13592](https://github.com/kgateway-dev/kgateway/pull/13592) — exposed `headersToClient` in ext-authz responses *(merged)*
- [Issue #14363](https://github.com/kgateway-dev/kgateway/issues/14363) — root-caused a readiness race on a 3,500+ cluster production gateway (proxies serving partial xDS config after scale-up); validated the fix with a 1M-request load test — merged upstream as [PR #14380](https://github.com/kgateway-dev/kgateway/pull/14380)

**Experience**

- **Douglas** — Cloud Ops Engineer *(Mar 2025–present)*: multi-cloud IaC (Azure DevOps + GCP, Terraform), implemented kgateway from scratch and migrated all production routing onto it, standalone agentic apps on Claude/Gemini with RAG and memory management, containerized dynamic Azure self-hosted CI/CD agents autoscaled with Karpenter + KEDA
- **managbl.ai** *(acquired by casavi, Sep 2025)* — Head of DevOps / Development Manager *(Apr 2024–Mar 2025)*: vLLM-served, fine-tuned Hugging Face models on masked/anonymized data; RAG pipeline for contract/provider cross-checking; migrated infra to Kubernetes with spot instances
- **Retraced** — Team Lead / Technical Manager *(Feb 2022–Mar 2024)*: architecture overhaul and dockerization at a blockchain-based fashion supply-chain traceability platform (2,000+ brands/suppliers); shipped AI-assisted document management (OpenAI/Anthropic) and a Corrective/Preventive Actions feature over a dynamic Oracle DB schema
- **Tecnotree** — Technical Manager *(Sep 2016–Feb 2022)*: managed ~25 engineers across 5 teams delivering DCBS (Digital Convergent Billing System), used by operators including Ooredoo

**Skills**

AI/LLM: vLLM, Hugging Face, fine-tuning, RAG, agentic apps · Platform: Kubernetes, ArgoCD,
Karpenter, kgateway/Envoy, cert-manager, Kyverno, KEDA, Terraform · Cloud: GCP, Azure, AWS,
Oracle Cloud
