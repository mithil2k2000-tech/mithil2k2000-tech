# Hi, I'm Mithil (Aaron) Nagabathula 👋

**Software engineer in London: backend, full-stack and cloud.**
I build complete systems in Python, TypeScript, Go and C#, and own them end to end: data model, API, UI, tests, CI and the infrastructure they run on in AWS and Azure.

MSc Cloud Computing (placement year) at the University of East London · Security Cloud Engineer at Impact Consulting · Open to software engineering and cloud roles.

🌐 [Portfolio](https://mithil2k2000-tech.github.io/portfolio/) · 💼 [LinkedIn](https://www.linkedin.com/in/mithilaaron/)

## Research (preprints, not yet peer reviewed)

Each repository holds the paper PDF, code, data and results. DOIs and arXiv links will be added when issued.

| Paper | Question and main result |
|---|---|
| [Does an Explanation Stability Score notice data drift?](https://github.com/mithil2k2000-tech/ess-drift-study) | Tests my MSc dissertation's explanation-reliability score: it reproduced (0.881) but never fired across 225 drifted batches; it does detect unreliable models. |
| [Does attack-path awareness help prioritise cloud security findings?](https://github.com/mithil2k2000-tech/attack-path-prioritisation) | 600 synthetic architectures: rule severity beat attack-path ranking; a misspecified probabilistic model came within 0.02 of optimal. |
| [Where should a RAG system enforce access control?](https://github.com/mithil2k2000-tech/rag-access-control-study) | Post-filtering cut recall from 0.61 to 0.37; shared BM25 statistics leaked hidden-document counts exactly; permission-blind caches leaked in ~90% of hits. |
| [Same setting, different verdict](https://github.com/mithil2k2000-tech/iac-scanner-idioms) | 312-case Terraform mutation corpus: scanner verdicts change with how a value is written. |
| [A one-way ratchet: AWS managed IAM policies 2019–2026](https://github.com/mithil2k2000-tech/aws-managed-policy-drift) | 91% of substantive changes to AWS managed policies only add permissions. |
| [What does hybrid post-quantum key exchange cost a microservice?](https://github.com/mithil2k2000-tech/pq-tls-microservices) | X25519MLKEM768 in Go: +2.3 kB and about +50% handshake CPU with ECDSA certificates, no extra round trip. |
| [Smoothness, not quantumness](https://github.com/mithil2k2000-tech/qml-adversarial-robustness) | Small quantum classifiers vs size-matched classical models under attack: the plain circuit was most robust (+7.6 points), the same circuit with data re-uploading least robust; robustness followed gradient size. |
| [A radiograph foundation model did not transfer better than a generic one](https://github.com/mithil2k2000-tech/kneescope-backbone-gate) | Pre-registered knee-OA backbone test: DINOv2 beat RAD-DINO and ImageNet. |
| [From 1.00 to 0.77: dementia prediction on OASIS](https://github.com/mithil2k2000-tech/oasis-leakage) | How target leakage, participant leakage and a cognitive test inflate reported accuracy. |
| [Pennies and pounds: UK payroll shortcuts](https://github.com/mithil2k2000-tech/payroll-shortcuts) | Differential testing against HMRC's exact method over 2 million payslips. |

## Featured projects

| Project | What it is | Stack |
| --- | --- | --- |
| [fintech-network](https://github.com/mithil2k2000-tech/fintech-network) | Full-stack payments platform: double-entry ledger, race-safe payments with row-level locking, risk engine, three React apps on one API. Deployed with Terraform to AWS ECS, plus a Helm chart and an incident drill. | TypeScript, React, Fastify, PostgreSQL, Playwright, Terraform |
| [cx-analytics-platform](https://github.com/mithil2k2000-tech/cx-analytics-platform) | Governed contact-centre analytics: data contracts with quarantine, dbt star schema on DuckDB, semantic metrics layer, [CXO dashboard](https://mithil2k2000-tech.github.io/cx-analytics-platform/) and an AI analyst that can't invent numbers. | Python, dbt, DuckDB, SQL, Claude API |
| [uk-payroll-engine](https://github.com/mithil2k2000-tech/uk-payroll-engine) | UK payroll engine and API built to HMRC's specification: PAYE, National Insurance, student loans and pensions. Matches HMRC's worked examples to the penny; [live demo](https://mithil2k2000-tech.github.io/uk-payroll-engine/) runs the engine as WebAssembly. | Go, REST API, WebAssembly, Docker |
| [enterprise-knowledge-ai](https://github.com/mithil2k2000-tech/enterprise-knowledge-ai) | RAG API where access control runs before retrieval. 98 tests plus a 12-case evaluation suite. | Python, FastAPI, Qdrant, Claude API |
| [confidential-ai-platform](https://github.com/mithil2k2000-tech/confidential-ai-platform) | Secure inference backend with RBAC, AES-256-GCM encryption and an append-only audit trail, plus a React console. 94 tests. | Python, FastAPI, React, TypeScript |
| [azure-uptime-monitor](https://github.com/mithil2k2000-tech/azure-uptime-monitor) | Serverless uptime monitor and status API on managed identity, no storage keys. 15 xUnit tests against Azurite in CI. | C#, .NET 10, Azure Functions, Bicep |
| [aws-account-auditor](https://github.com/mithil2k2000-tech/aws-account-auditor) | Read-only CLI that finds security gaps and wasted spend in an AWS account. 29 tests with moto. | Python, boto3, pytest |
| [sentinelcloud](https://github.com/mithil2k2000-tech/sentinelcloud) | Multi-cloud security governance: threat modelling, policy as code, attack-path simulation. 295 tests. | Python, Terraform, OPA/Rego, Kubernetes |
| [qsafe](https://github.com/mithil2k2000-tech/qsafe) | Finds quantum-vulnerable crypto and protects data with NIST post-quantum algorithms. | Python, ML-KEM, ML-DSA |

## Toolkit

**Languages:** Python · TypeScript · Go · C# · SQL · Bash
**Backend and frontend:** FastAPI · Fastify · Azure Functions · React · Vite · PostgreSQL
**Testing:** Go test · pytest · xUnit · Vitest · Playwright · moto · Azurite
**Cloud and DevOps:** AWS · Azure · Terraform · Bicep · Docker · Kubernetes · Helm · Prometheus · Grafana · GitHub Actions (OIDC)
**Data:** dbt · DuckDB · PostgreSQL · dimensional modelling · data contracts
**AI:** Claude API · RAG · Claude Code · GitHub Copilot
