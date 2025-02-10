---
layout: post
title:  "Recallfilai part 1: requirements and tech stack"
date:   2025-02-10 00:00:46 +0100
categories:
    - '2025'
    - tech
    - recallfilai
permalink: /recallfilai/
---

### What is:
Document store with AI capabilities (**recallfilai** because AI is the hot word as of now) is the new year's opensource project for 2025. 

### **Features**:
* Upload, store, download documents.
* Support text files, pdf, word, audio, video,
* Accept a url and download the page as a content.
* Support for dynamic metadata.
* Malware detection.
* Basic search (metadata & content).
* Vector search.
* RAG.
* Multi-tenant.
* OIDC authn/authz.
* TBD ...

### **Technologies**:
Backend: Python + FastAPI + LangChain + RabbitMQ
ML: Ollama.
Database: Qdrant
Storage: Mongo, S3 (Mongo)
Authn/authz: Keycloak
Frontend: Typescript + ReactJS + Bootstrap

### **Resources**
(this section will be updated frequently)
* https://qdrant.tech/documentation/
