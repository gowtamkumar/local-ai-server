# 🧠 Ollama + Open WebUI (LLM Server via Docker)

This project sets up a local environment to run large language models (LLMs) like **CodeLlama** and **DeepSeek Coder** using [Ollama](https://ollama.com/) and [Open WebUI](https://github.com/open-webui/open-webui), all containerized with Docker.

---

## ✨ Features

- Run open-source LLMs locally
- Pre-pulls and runs models like `codellama` and `deepseek-coder-v2`
- Easy-to-use chat interface via Open WebUI
- Persistent model and data storage
- Ready to use with minimal setup

---

## 📦 Services

| Service       | Description                               | Port        |
|---------------|-------------------------------------------|-------------|
| **Ollama**     | LLM backend, runs and manages models      | `11434`     |
| **Open WebUI** | Frontend interface to interact with LLMs  | `8801` (host) → `8080` (container) |

---

## 🛠️ Requirements

- Docker installed → [Install Docker](https://docs.docker.com/get-docker/)
- Docker Compose → Comes with Docker Desktop or install via:  
  ```bash
  sudo apt install docker-compose
- run server
  ```bash
  docker compose up --build