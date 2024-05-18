# AGENTIC-RAG-DOCKER
Docker implementation of a AGENTIC-RAG System

# Description

This repo explains the docker implementation of AGENTIC-RAG with Gradio and Ollama.

The docker is build based on Work from [THIS REPO](https://github.com/swastikmaiti/AGENTIC-RAG.git). Here we only describe the docker framework. For detail
implementation of AGENTIC-RAG refer to the provided repo.

# File descrition
- Dockerfile: This dockerfile build image of our AGENTIC-RAG implemeted with Gradio App
- compose.yaml: The compose file is required as we need to start various services(container) for our System to Work.
    - Gradio : Main Application
    - Ollama Server : Run Local LLM
    - Ollama Pull : To pull the LLM Model into Ollama Server
