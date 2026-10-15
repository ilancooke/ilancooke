# Hi, I'm Ilan Cooke 👋

I'm a Data Scientist and ML practitioner with a background in building and operating production machine learning systems, primarily focused on fraud detection, risk assessment, and automated decision-making.

My interests are at the intersection of machine learning, AI engineering, and software systems, particularly building reliable, end-to-end applications that combine ML models, LLMs, data pipelines, and cloud infrastructure. I'm especially interested in LLM evaluation, retrieval-augmented generation (RAG), and turning unstructured data into actionable insights.

I'm continuing to explore these areas through hands-on projects, and I'll be sharing more of that work here as it develops.

Outside of my professional work, I'm a homelabbing enthusiast. I enjoy experimenting with self-hosted services, home automation, networking, infrastructure, and building practical applications that bring these systems together.

## Featured Projects

### Finbot — Financial Data & AI Engineering

A collection of services exploring event-driven data pipelines, cloud infrastructure, LLM-based information extraction, and evaluation using public financial disclosures.

**[Finbot Filings — SEC Filing Discovery & Ingestion](https://github.com/ilancooke/finbot-filings)**

An AWS-based document ingestion service that monitors SEC filings using earnings-aware scheduling, selectively acquires financial reports and exhibits, and stores immutable artifacts in S3. Uses DynamoDB for durable processing state and recovery, and SNS to publish complete filing snapshots for downstream consumers. Includes containerized deployment, infrastructure as code, CI/CD, and observability.

*Technologies: Python, AWS ECS/Fargate, S3, DynamoDB, SNS, CloudWatch, Docker, CDK*

**[Finbot Earnings — LLM Earnings Extraction & Evaluation](https://github.com/ilancooke/finbot-earnings)**

An LLM-powered processing pipeline that transforms financial filings into structured earnings data. Combines multi-document extraction using Amazon Bedrock with evidence validation, event versioning, and recoverable processing. Includes an evaluation framework for testing extraction quality, validation outcomes, cost, and latency against synthetic and reviewed filing datasets.

*Technologies: Python, Amazon Bedrock, LLM evaluation, structured outputs, AWS Lambda, SQS, DynamoDB*

*In development — AWS processing infrastructure implemented and tested offline.*

### [Resume Modifier — LLM-Powered Resume Generation & Evaluation](https://github.com/ilancooke/resume_modifier)

An LLM-powered application that tailors resumes to job descriptions using structured career history, checks generated content against source evidence, and evaluates output quality. Includes an experimentation framework for comparing generation strategies and LLM-based evaluations.

*Technologies: Python, OpenAI API, Anthropic API, LLM evaluation, document processing*

### [Home Dashboard — Home Automation Interface](https://github.com/ilancooke/home-dashboard)

A self-hosted web dashboard integrating weather data, security cameras, whole-home audio, and Home Assistant. Designed for lightweight hardware and deployed in a containerized homelab environment. I use old Kindle Fire tablets with 3D-printed wall mounts to display and interact with the UI.

*Technologies: Python, Flask, REST APIs, Linux, Proxmox*

## Technical Focus

- **Machine Learning:** Classification, risk modeling, gradient boosting, model evaluation, explainability, production ML
- **AI Engineering:** LLM applications, structured extraction, evidence validation, evaluation frameworks, document processing, RAG
- **Software & Infrastructure:** Python, SQL, AWS, event-driven architectures, data pipelines, Docker, REST APIs, infrastructure as code, CI/CD

## Connect

[LinkedIn](https://www.linkedin.com/in/ilancooke/) · [GitHub](https://github.com/ilancooke)
