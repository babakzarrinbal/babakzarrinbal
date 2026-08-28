### Babak Zarrinbal

**Cloud & Platform Engineer** — Kubernetes, GitOps, LLM Infrastructure. Düsseldorf, Germany.

14+ years in software, 10+ years leading engineering teams. I build and run multi-cloud
(Azure/GCP) Kubernetes platforms and agentic AI systems at Douglas, and contribute fixes
upstream to [kgateway](https://github.com/kgateway-dev/kgateway), the CNCF Envoy-based
API/AI Gateway.

What I'm good at: **root-causing production distributed-systems failures end to end** —
from running cluster state down to upstream source — fixing the cause rather than the
symptom, and pushing the fix back upstream.

**[zarrinbal.org](https://zarrinbal.org)** · [Résumé (PDF)](https://zarrinbal.org/resume.pdf) · [LinkedIn](https://www.linkedin.com/in/babak-zarrinbal/) · babak.zarrinbal@gmail.com

---

#### Open source

**kgateway** (CNCF — Envoy-based API/AI Gateway)

- **[PR #14231](https://github.com/kgateway-dev/kgateway/pull/14231)** *(merged)* — fixed XListenerSet status validation. The legacy CRD still required `status.listeners[*].port` after the promoted type dropped the field, so every reconcile cycle failed to patch status. Shipped with 8 table-driven unit tests.
- **[PR #13592](https://github.com/kgateway-dev/kgateway/pull/13592)** *(merged)* — exposed `headersToClient` in ext-authz responses.
- **[Issue #14363](https://github.com/kgateway-dev/kgateway/issues/14363)** *(root-caused)* — a readiness race causing proxies to serve partial xDS config after scale-up, on a production gateway fronting **3,500+ clusters**. Validated the fix with a **1M-request load test**; merged upstream as [PR #14380](https://github.com/kgateway-dev/kgateway/pull/14380).

**Supply-chain security**

- **[Shai-Hulud 2.0 Detector](https://github.com/babakzarrinbalmasouleh-douglas/Shai-Hulud-2.0-Detector)** — GitHub Action published to the **GitHub Marketplace**, detecting npm packages compromised in the Shai-Hulud 2.0 attack: 790+ malicious packages, suspicious install scripts, TruffleHog activity and secrets exfiltration, with SARIF output.

---

#### Experience

**Douglas** — Cloud Ops Engineer *(Mar 2025 – present)*
Multi-cloud IaC (Terraform across Azure DevOps + GCP) for production and staging clusters ·
implemented kgateway from scratch and migrated all production routing onto it ·
standalone agentic apps on Claude/Gemini with RAG and memory management under strict
data-handling constraints · containerised dynamic Azure self-hosted CI/CD agents autoscaled
with Karpenter + KEDA ScaledJob · manages a team of DevOps engineers.

**managbl.ai** *(acquired by casavi, Sep 2025)* — Head of DevOps / Development Manager *(Apr 2024 – Mar 2025)*
vLLM-served, fine-tuned Hugging Face models on masked/anonymised data for intent
classification · RAG pipeline for real-time contract and provider cross-checking ·
migrated infrastructure to Kubernetes on spot instances to cut compute cost while scaling.
Technology now serves 150+ customers via casavi.

**Retraced** — Team Lead / Technical Manager *(Feb 2022 – Mar 2024)*
Blockchain supply-chain traceability for fashion, 2,000+ brands and suppliers. Led the
architecture overhaul into dockerised services; shipped AI-assisted document management
(OpenAI/Anthropic) and a Corrective/Preventive Actions feature over a dynamic open-schema
Oracle data layer.

**Tecnotree** — Technical Manager *(Sep 2016 – Feb 2022)*
Delivered DCBS (Digital Convergent Billing System), used by operators including Ooredoo.
Managed ~25 engineers across 5 rotating teams, plus QC and a 4-person DevOps team on
Rancher-based Kubernetes.

---

#### Stack

**Platform** Kubernetes · ArgoCD · Terraform · kgateway/Envoy · Gateway API · Karpenter · KEDA · cert-manager · Kyverno · Helm · Docker
**Cloud** GCP · Azure · AWS · Oracle Cloud · Azure DevOps
**AI/LLM** vLLM · Hugging Face · fine-tuning · RAG · agentic apps · OpenAI · Anthropic · Gemini
**Observability** Prometheus/Mimir · Grafana · Loki · Datadog · Dynatrace · Instana
**Languages** Go · Python · TypeScript/Node.js · Java · Bash
