# Omar Boukherys

**Senior Data Scientist · State Engineer in Statistics · Morocco**

I take data work from the first statistical question all the way to production: machine learning pipelines, LLM applications that cite their sources, streaming data platforms, and the cloud infrastructure underneath.
Much of my work focuses on banking: fraud detection and regulatory compliance.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Omar%20Boukherys-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/omar-boukherys-a891191b2)
[![Email](https://img.shields.io/badge/Email-omarboukheryspro%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:omarboukheryspro@gmail.com)

---

## What I do

| | |
|---|---|
| **Statistics & machine learning** | Modeling, validation design, imbalanced data, uncertainty. Models trained, registered, deployed and monitored, not left in a notebook. |
| **LLM applications** | Retrieval-augmented assistants with sourced answers, tool-using agents, voice bots, guardrails and evaluation. |
| **Data engineering** | Batch and streaming pipelines, lakehouses, orchestration, data quality and reconciliation. |
| **Cloud & operations** | AWS, Azure and GCP, infrastructure as code, Kubernetes, monitoring and incident response. |

## Featured projects

### Banking & fraud

| Project | What it shows |
|---|---|
| [**FraudStream Platform**](https://github.com/omarboukherys/fraudstream-platform) | Real-time bank fraud detection at scale: Kafka, Spark Structured Streaming in Scala with per-customer state, Cassandra, Airflow/PySpark, BigQuery and Kubernetes, plus an agent that investigates each alert with evidence and an audit trail. |
| [**SageMaker MLOps pipeline**](https://github.com/omarboukherys/aws-sagemaker-mlops-pipeline) | XGBoost on imbalanced fraud data, Model Registry, real-time endpoint and Model Monitor on AWS. |
| [**Real-time ML inference**](https://github.com/omarboukherys/aws-realtime-ml-inference) | Fully serverless scoring: Kinesis, Lambda, a SageMaker XGBoost endpoint and SNS alerts on suspicious transactions. |
| [**Compliance assistant on Azure**](https://github.com/omarboukherys/assistant-conformite-azure) | Helps bank advisors find sourced answers in Moroccan laws 31-08 and 103-12, in French or Arabic. Azure AI Search, Microsoft Foundry, and a Power BI report with row-level security. |
| [**Regulatory assistant for bank advisors**](https://github.com/omarboukherys/assistant-reglementaire-ia) | A Power Apps app backed by Amazon Bedrock that answers regulatory questions from official texts, citing document and page. |

### Data platforms

| Project | What it shows |
|---|---|
| [**ADF → Airflow 3 migration**](https://github.com/omarboukherys/adf-to-astronomer-migration) | A daily Azure Blob → Snowflake load migrated from Azure Data Factory to Airflow 3 on Astronomer with dbt. Both orchestrators loaded the same 90 files: 11 of 11 reconciliation checks pass, reruns are idempotent and every row traces back to its source file. |
| [**Morocco Data Platform**](https://github.com/omarboukherys/de_project) | Open-source platform on weather and air quality for 12 Moroccan cities: NiFi, S3 storage, Spark, Dremio, dbt, Airflow, Prometheus/Grafana and OpenMetadata. *In progress.* |

### LLM agents & assistants

| Project | What it shows |
|---|---|
| [**Bedrock RAG assistant**](https://github.com/omarboukherys/aws-bedrock-rag-assistant) | Answers with citations over complex PDFs (financial reports, tables). Layout-aware parsing with Docling; S3 Vectors chosen over OpenSearch Serverless for about 90% lower cost on small and medium corpora. |
| [**Voice agent on AWS**](https://github.com/omarboukherys/aws-voice-agent) | Books appointments and answers FAQs, built two ways: a web voice pipeline (Transcribe, Bedrock, Polly) and a real phone bot (Amazon Connect, Lex), with Bedrock Guardrails. |
| [**IT support agent + ServiceNow**](https://github.com/omarboukherys/aws-support-agent-servicenow) | A Lex bot and a Bedrock AgentCore agent sharing one TypeScript backend that creates and tracks ServiceNow incidents. |
| [**Mira**](https://github.com/omarboukherys/mira-companion) | Multi-user conversational agent built with LangGraph: routing, short- and long-term memory (SQLite, Qdrant), image generation, text-to-speech, web and Telegram interfaces. |

### Software engineering & operations

| Project | What it shows |
|---|---|
| [**Smart Checkout**](https://github.com/omarboukherys/smart-checkout-ai) | Omnichannel checkout as event-driven microservices: Java 21, Spring Boot, Kafka, PostgreSQL, MongoDB. Saga with transactional outbox, hexagonal architecture, idempotent APIs, and an assistant that reviews suspicious payments while a human decides. |
| [**Production Monitoring Lab**](https://github.com/omarboukherys/prod-monitoring-lab) | A simulated production environment: Prometheus, Grafana, Alertmanager, Elasticsearch and Kibana, batch SLA tracking, injected incidents, runbooks and automatic triage. |
| [**UiPath platform on AWS**](https://github.com/omarboukherys/uipath-aws-platform) | Terraform for an automation platform on AWS: three-tier VPC across three availability zones, remote state, robot scaling. *In progress.* |

## Open-source contributions

| Project | What I did | Status |
|---|---|---|
| [LiteLLM](https://github.com/BerriAI/litellm) | Gemini batch embeddings are now billed from Google's own usage data, so image, video and audio inputs are no longer counted as free. [#49682](https://github.com/BerriAI/litellm/pull/49682) | ![PR state](https://img.shields.io/github/pulls/detail/state/BerriAI/litellm/49682) |
| [DSPy](https://github.com/stanfordnlp/dspy) | `Evaluate`'s JSON export now handles dates and enums (including as dictionary keys) and `Prediction` / `Example` values, and never leaves a half-written file. [#10797](https://github.com/stanfordnlp/dspy/pull/10797) | ![PR state](https://img.shields.io/github/pulls/detail/state/stanfordnlp/dspy/10797) |
| [scikit-learn](https://github.com/scikit-learn/scikit-learn) | Showed that `LinearDiscriminantAnalysis` gives different results with the `svd` and `lsqr` / `eigen` solvers when custom priors are set, and proposed two fixes. [#35254](https://github.com/scikit-learn/scikit-learn/issues/35254) | ![Issue state](https://img.shields.io/github/issues/detail/state/scikit-learn/scikit-learn/35254) |

## Toolbox

| | |
|---|---|
| **Languages** | Python · SQL · Scala · Java · TypeScript |
| **ML & statistics** | scikit-learn · XGBoost · PyTorch · TensorFlow · pandas · Amazon SageMaker |
| **LLM stack** | LangGraph · LangChain · Amazon Bedrock · Azure AI Search · Microsoft Foundry · Gemini · Groq · Qdrant · LiteLLM · DSPy |
| **Data** | Spark · Kafka · Airflow · dbt · Snowflake · BigQuery · Cassandra · PostgreSQL · MongoDB · NiFi · Dremio |
| **Cloud & DevOps** | AWS · Azure · GCP · Terraform · Kubernetes · Docker · GitHub Actions |
| **Monitoring & BI** | Prometheus · Grafana · Elasticsearch · Kibana · Power BI · Power Apps |
