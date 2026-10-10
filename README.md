# Alex Meneguolo Boscolo

**Senior Site Reliability Engineer · AI Infrastructure · Cloud Solutions Architect**
Remote from Rio de Janeiro, Brazil · 9+ years in cloud and infrastructure

I run production infrastructure for a fintech, including an on-prem RKE2 GPU cluster
(13× NVIDIA H200) that serves around 10 vLLM models behind a LiteLLM gateway.
My work covers Kubernetes, Terraform, observability, and LLM serving.

### Projects
- **[aiops-sre-agent](https://github.com/alexboscolo954/aiops-sre-agent)**: an alert triage agent for Kubernetes. It's built on LangChain, with MCP servers for its tools, and every action needs human approval. It's tested end-to-end on kind, with least-privilege RBAC and evals on recorded failures.
- **[llm-serving-k8s](https://github.com/alexboscolo954/llm-serving-k8s)**: vLLM on Kubernetes behind a LiteLLM gateway. The CPU path runs in CI on kind. The GPU path covers FP8, time-slicing and OpenCost.
- **[slo-as-code](https://github.com/alexboscolo954/slo-as-code)**: SLOs as code with Sloth. The burn-rate alerts are unit-tested and mutation-tested, then proven end to end with Prometheus and Alertmanager.
- **[terraform-eks-platform](https://github.com/alexboscolo954/terraform-eks-platform)**: an opinionated EKS platform on the community modules, tested without an AWS account (terraform test with mocks, Moto, checkov, mutation tests).

**Outside work**
- **[portfolio-goal-planner](https://github.com/alexboscolo954/portfolio-goal-planner)**: Monte Carlo and mean-variance planning toward a savings goal.
- **[prediction-market-lab](https://github.com/alexboscolo954/prediction-market-lab)**: Polymarket analytics: price-jump detection, the liquidity-reward math, and a paper-traded market maker with a fenced live mode.

### What I work with
- **Kubernetes:** RKE2, EKS, AKS, OpenShift, Rancher, Helm, Cilium
- **AI infra:** vLLM, LiteLLM, NVIDIA GPU Operator, AWS Bedrock, SageMaker, OpenCost
- **IaC & CI/CD:** Terraform, Ansible, CloudFormation, GitLab CI, GitHub Actions
- **Observability:** Prometheus, Grafana, Datadog, OpenTelemetry, SLOs
- **Cloud:** AWS, Azure

### Certifications
CKA · CKS · LFCS · AWS Solutions Architect Associate · AWS AI Practitioner ·
Azure DevOps Engineer Expert · Terraform Associate

### Contact
[LinkedIn](https://linkedin.com/in/alexmeneguolo) · Open to remote B2B contract roles
