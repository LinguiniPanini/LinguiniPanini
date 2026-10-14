# Hi, I'm Luis Alberto González Escamilla 👋

**Software & Systems Engineer · Cloud Infrastructure (AWS) & AI Automation**  
📍 Jalisco, Mexico · ✉️ [luisal.gonzaleze@gmail.com](mailto:luisal.gonzaleze@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/luis-alberto-gonzalez-escamilla)

---

### About Me
I build and operate resilient cloud infrastructure, event-driven distributed systems, and AI-powered automation workflows. 

At **TendencIA Systems**, I owned the production reliability of AI voice and chat agents processing **10,000+ executions per month**, implementing serverless webhook pipelines, LLM tracing & observability (Langfuse), and automated cost reporting. My focus is engineering scalable, secure systems on **AWS (EKS, Lambda, SQS, S3, RDS, IAM)** following least-privilege principles and GitOps automation.

---

### Tech Stack & Core Competencies

```
Cloud & DevOps     │ AWS (EKS, EC2, Lambda, S3, SQS, SNS, RDS, SES, IAM), Kubernetes, Docker, Terraform, GitHub Actions, Linux
AI & Automation    │ LLM Agents, Langfuse (Tracing/Observability), RAG, Vector Search, n8n, Vapi, Prompt Engineering
Backend & Systems  │ Python, TypeScript, Node.js, FastAPI, PostgreSQL, Supabase, MySQL, DynamoDB, Redis, REST APIs
Architecture       │ Event-Driven, Microservices, Serverless, FinOps / Cost Governance, Least-Privilege Security
```

---

### Featured Cloud & Engineering Projects

#### 🚀 [AWS EKS Microservices Platform](https://github.com/LinguiniPanini/aws-eks-microservices-platform)
*Distributed sales and invoicing microservices platform orchestrated on AWS EKS.*
- Multi-container architecture with 4 decoupled services in Docker (`api`, `pdf-generator`, `notifier`, `receipt-worker`).
- Asynchronous message buffering via **Amazon SQS**, asset storage in **Amazon S3**, and email alerts via **Amazon SNS**.
- Relational state persistence with **Amazon RDS PostgreSQL** and zero-downtime rolling updates on Kubernetes.

#### ⚡ [AWS Serverless Order & Invoicing Pipeline](https://github.com/LinguiniPanini/aws-serverless-order-pipeline)
*Event-driven serverless architecture orchestrated with AWS Step Functions.*
- Stateful state machine coordinating 8 Python **AWS Lambda** functions with shared custom Lambda Layers.
- Asynchronous queue decoupling with **Amazon SQS**, document storage in **Amazon S3**, and automated delivery with **Amazon SES**.
- 100% automated infrastructure provisioning script via AWS CLI, IAM, and Amazon API Gateway.

#### 🧠 [MLOps Pipeline on AWS](https://github.com/LinguiniPanini/MLemons)
*End-to-end computer vision MLOps architecture orchestrated on AWS.*
- Full Infrastructure as Code (IaC) written in **Terraform** managing IAM, S3, DynamoDB, and CloudWatch.
- Deep learning inference hosted on **AWS SageMaker Endpoint**, orchestrated through **Step Functions** and **Lambda**.

#### 📬 [AWS SQS Event-Driven Order Processor](https://github.com/LinguiniPanini/aws-sqs-event-processor)
*High-throughput decoupled queue processing system.*
- Message buffering using **Amazon SQS** (long-polling and visibility timeout retry logic) to prevent traffic dropouts.
- Continuous background worker daemon on **Amazon EC2** persisting transactional records into **Amazon RDS PostgreSQL**.
- Strict **IAM Least-Privilege** security policy governance. Includes architectural diagram and video walkthrough.

#### 🔄 [Kubernetes GitOps CI/CD Pipeline](https://github.com/LinguiniPanini/k8s-cicd-pipeline)
*Continuous integration and automated deployment pipeline.*
- Automated multi-stage GitHub Actions workflows (`integrate`, `delivery`, `deploy`).
- Automated testing on pull requests, Docker Hub image publishing with semantic versioning, and rolling deployments to Kubernetes.

#### 🛠️ [Universal File Converter](https://github.com/LinguiniPanini/universal-file-converter)
*Full-stack document processing service with automated AWS infrastructure.*
- Automated provisioning of EC2 instances, Nginx reverse proxy, and systemd daemons.
- **S3 Lifecycle Policies** for cost optimization and automatic 24-hour artifact garbage collection.
- 30 unit/integration tests with `pytest` and `moto` AWS mocking.

---

### Production Track Record
- **10,000+ Monthly AI Executions:** Engineered and maintained conversational phone and chat agent pipelines connecting telephony (Vapi, Twilio) to CRMs.
- **Incident Response & Observability:** Integrated Langfuse tracing and automated Vitest suites, drastically cutting MTTR on production incidents.
- **FinOps & Cost Governance:** Built serverless data pipelines ingesting webhook events to deliver per-client cost and usage reporting.

---

### Let's Connect
- **LinkedIn:** [linkedin.com/in/luis-alberto-gonzalez-escamilla](https://www.linkedin.com/in/luis-alberto-gonzalez-escamilla)
- **Email:** [luisal.gonzaleze@gmail.com](mailto:luisal.gonzaleze@gmail.com)
