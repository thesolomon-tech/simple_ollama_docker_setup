# Simple Docker Setup For Ollama and Open WebUI

A simple Docker Compose that runs Ollama and Open WebUI ( a front end interface like Chatgpt for Ollama) on the CPU.

After cloning the repository run `docker compose up -d`

If you want to close the repository, run `docker compose down`

Also, to install a model into ollama, run `docker exec ollama -it`, which will allow you to access the terminal of the ollama container. Then, install a model of your choice from [Ollama](https://ollama.com/library) via `ollama run <model_name>`

> [!NOTE]
> Key IP addresses are http://localhost:11434 for ollama and http://localhost:8080 for Open WebUI.

> [!TIP]
>  If you want Ollama to run on your GPU further setup is required. Refer to the official Docker page: https://hub.docker.com/r/ollama/ollama
