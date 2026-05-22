# Background

• 8+ years across Software Engineering, Analytics, and Generative AI, specialized in Agentic RAG, and LLM and vLLM workflow delivery.

• Led a team of 6 to built governed RAG + MCP workflows using LangChain, LangGraph with multi-step graphs (state, routing, retries, HITL) and tool wiring with MLOps and Observability.

• Hands-on with Parent-Child, Contextual-aware, and Semantic chunking, tuned via retrieval recall@k and grounded/citation scoring.

• Built deterministic PDF parsing pipelines (tables, multi-column) producing structured JSON + metadata ready for chunking. Implemented hybrid retrieval (BM25 + vector) with reranker, tuned top-k, filters, and citation/provenance.  


## Domain/Sector Expertise:

• Logistics & Supply Chain, Hospitality, CPG/Retail.


## Technical Expertise: 

• Languages/REST: Python (with OOPS and Generic Programming, and Pytest), SQL , Shell , Yaml, FastAPI

• GenAI : Prompt Engineering, Retrieval‑Augmented Generation (RAG), LangChain, LangGraph, LangSmith, Co-pilot, Hugging Face, LLM, vLLM

• Retrieval & Chunking: Parent-Child, Contextual-aware, Semantic chunking, BM25 + vector hybrid retrieval, Reranking, citation/provenance

• Cloud/DevOps: GCP, Azure, Docker , K8s (EKS) , Terraform , Jenkins, GitHub Actions

• Data : BigQuery, MongoDB, SQL Server, Vector stores (Pinecone)

• ML and LLM Ops & Observability : Mlflow, LangSmith, Kserve, DVC, Prometheus, Grafana


## Education (MSc, MTech, BTech)

• M.Sc. – Mathematical Modelling and Machine Learning | University College Cork, Cork, Ireland


## Experience and Core Competency

• Generative AI & LLM Systems: Shipped LangChain and LangGraph based LLM workflows into production, including RAG pipelines, multi-step reasoning flows, and agentic graphs with state and routing serving live enterprise users.

• Working knowledge of GCP and Azure services and basic networking (VPC, load balancers) used to run production AI workloads.

• Containerized production AI services with Docker, including multi-stage builds to reduce image size and speed up rollouts. Built and operated CI/CD pipelines using GitHub Actions that take code commits through to Kubernetes deployments.

• Ran Kubernetes (EKS) workloads in production for ML and AI services, including GitOps style sync for manifests.

• Built and deployed REST APIs using FastAPI for model inference, serving live traffic with structured JSON outputs.


## GenAI Based Agentic RAG (LangGraph)

• Built and deployed a production RAG pipeline that converts enterprise documents and tabular data into grounded, searchable answers for live users.

• Implemented the data ingestion layer to extract and preprocess content (cleaning, normalization, metadata tagging) running on a scheduled pipeline.

• Applied Parent-Child, Contextual-aware, and Semantic chunking, compared them on a labeled test set, and promoted the winning strategy into production.

• Generated vector embeddings and stored them in Pinecone for similarity-based retrieval at production scale.

• Deployed a hybrid retriever (BM25 + vector with top-K search) with a reranker stage to improve precision on real user queries.

• Designed and shipped prompt templates that guide the LLM for context-aware, citation-backed outputs.

• Integrated the LLM with the retrieval pipeline in production to produce grounded answers and reduce hallucination.

• Structured the live RAG pipeline into modular components (ingestion, parsing, chunking, embedding, retrieval, generation) so each stage can be scaled and replaced independently.


## Document Parsing Pipeline,MLOps & Model Deployment

• Operationalized MLOps workflows covering model training, versioning, and lifecycle management for production systems. Served ML and LLM models in production behind FastAPI endpoints and used Kserve for standardized inference. 

• Containerized ML workloads with Docker and deployed on Kubernetes using Deployment and Ingress patterns in production clusters.

• Automated training and deployment readiness using CI/CD so artifacts flow into production without manual steps.

• Stood up a deterministic PDF parsing pipeline in production covering tables, multi-column layouts, and mixed text/figure pages. Produced structured JSON with page-level metadata (page number, section, table IDs, bounding boxes) ready for downstream chunking and embedding. 

• Handled edge cases: rotated pages, merged table cells, scanned vs digital PDF detection, repeated headers/footers, and boilerplate stripping. 

• Modularized ingestion, parsing, normalization, and JSON output as independently testable stages, validated using Pytest before promotion.

• Kept parsing deterministic and idempotent so the same source PDF always yields the same JSON, supporting reliable re-indexing in production.


## Kubernetes Deployment and Orchestration (EKS )

• Operated Kubernetes workloads on EKS in production for AI & analytics services. 

• Authored and maintained Deployment, Service, and Ingress YAML manifests serving live traffic. 

• Configured path-based and host-based routing through an Ingress Controller in production. 

• Used GitOps style sync workflows to keep production manifests aligned with the cluster state. 

• Enabled near zero-downtime deployments through automated sync and rollout strategies.


## CI/CD pipeline implementation 

• Designed and run CI/CD pipelines using GitHub Actions that build and deploy to production environments. Integrated automated testing (Pytest) and deployment stages so every release is validated before going live. 

• Containerized applications and managed the Docker image lifecycle for production rollouts. 

• Enabled consistent deployments across dev, staging, and production environments. Reduced deployment time and manual intervention for production releases.
