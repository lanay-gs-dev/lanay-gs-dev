# La-Nay Grant

AI Solutions Engineer building enterprise GenAI and RAG applications with AWS architecture, governance, and risk-aware delivery.

I bring 10+ years of experience across enterprise risk, data governance, automation, and analytics. My work focuses on turning messy business knowledge into AI systems that are useful, explainable, and practical to operate.

## Current Focus

- Retrieval-Augmented Generation (RAG)
- Enterprise AI application design
- AWS cloud architecture
- Python-based AI workflows
- Document processing and knowledge retrieval
- Responsible AI, governance, and risk-aware delivery

## Featured Projects

### Enterprise RAG Application

Status: Local RAG pipeline complete; AWS backend deployment slice implemented; AWS-native RAG expansion planned  
Repository: [enterprise-rag-application](https://github.com/lanay-gs-dev/enterprise-rag-application)  
Stack: Python, FastAPI, Streamlit, Chroma, sentence-transformers, Docker, GitHub Actions, AWS S3, IAM, ECR, ECS/Fargate, ALB, CloudWatch, unittest

A document-based RAG application for answering questions from internal documents with traceable evidence, metadata validation, retrieval, citations, and refusal behavior.

Implemented now:

- Markdown document ingestion with required metadata validation
- Deterministic paragraph-aware chunking with stable chunk IDs
- Local embeddings and Chroma vector search
- Retrieval layer that returns ranked evidence chunks
- Deterministic answer/refusal response contract
- Streamlit demo interface
- FastAPI `/ask` endpoint returning answer, citations, refusal status, and retrieved evidence
- Dockerized FastAPI backend deployed to AWS using ECR, ECS/Fargate, Application Load Balancer, IAM task roles, and CloudWatch logs
- S3 document storage layout with prefix-based access-control policies for public, internal, confidential, owner, and engineer access patterns
- GitHub Actions workflow for automated unit tests
- Tests across ingestion, chunking, embeddings, vector storage, retrieval, refusal behavior, and API responses

AWS production mapping / next expansion:

- S3 for document storage
- Lambda, ECS tasks, or Glue for ingestion jobs
- Bedrock embeddings or SageMaker for managed embedding generation
- OpenSearch Serverless or Bedrock Knowledge Bases for managed vector search
- ECS/Fargate for the FastAPI service
- CloudWatch, IAM, and Secrets Manager for operations and security
- Bedrock for grounded LLM answer generation

### Small Business Operations Insights

Status: Planning / MVP build  
Implemented now: sample data, public project framing, and MVP workflow design  
Planned next: data loading, metrics, retention flags, and weekly owner summary

A lightweight analytics and AI reporting project for a small service-based business, focused on turning spreadsheet-style data into retention insights, activity trends, and a plain-English weekly owner summary.

Focus areas:

- Business process analysis
- Requirements discovery
- Sample data design
- Retention and activity metrics
- Practical GenAI use cases for small business operations

This project demonstrates how AI can be applied to real operational problems without overcomplicating the solution.

## Tools & Technologies

Python · FastAPI · Streamlit · Chroma · sentence-transformers · Docker · GitHub Actions · unittest · AWS architecture · S3 · IAM · ECR · ECS/Fargate · ALB · CloudWatch · Lambda · Bedrock · OpenSearch · SQL · Snowflake · Databricks · Tableau · GitHub

## Now

Building AI engineering portfolio projects focused on enterprise RAG, document processing, retrieval, evaluation, and AWS architecture patterns.

AWS Certified AI Practitioner scheduled for August 2026. Continuing AWS Solutions Architecture study through project-based system design.

[LinkedIn](https://www.linkedin.com/in/lanaygrant)
