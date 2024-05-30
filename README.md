# AGENTIC-RAG-DOCKER
Docker implementation of a AGENTIC-RAG System

# Description

This repo explains the docker implementation of AGENTIC-RAG with Gradio and Ollama.

The docker is build based on Work from [THIS REPO](https://github.com/swastikmaiti/AGENTIC-RAG.git). Here we only describe the docker framework. For detail
implementation of AGENTIC-RAG refer to the provided repo.

# Docker Architecture

![alt text](https://github.com/swastikmaiti/AGENTIC-RAG-DOCKER/blob/baa956f3792ed16033e2db990be853e9c3141b97/docker-architecture-1.png)

# File descrition
- Dockerfile: This dockerfile build image of our AGENTIC-RAG implemeted with Gradio App
- compose.yaml: The compose file is required as we need to start various services(container) for our System to Work.
    - Gradio : Main Application
    - Ollama Server : Run Local LLM
    - Ollama Pull : To pull the LLM Model into Ollama Server
# How to RUN
- All the work is developed in LINUX env so we need a LINUX system with atleast 8GB RAM.
- Make sure docker is installed in the System
- To build image and start the container run `docker compose up --build`. Building image will take time to pull all the LLM models required to run the APP.

# TL:DR:

Docker image for AGENTIC-RAG Gradio App
```
git clone https://github.com/swastikmaiti/AGENTIC-RAG-DOCKER.git
cd AGENTIC-RAG-DOCKER
cd Docker_Compose
docker compose up
```

# Acknowledgement
- Thanks to Docker Hub for wonderful documentation on GenAI containerization. [Chekout their docs](https://docs.docker.com/guides/use-case/genai-pdf-bot)

#
### If you find the repo helpful, please drop a ⭐
