> [!IMPORTANT]
>
> # REPOSITORY MOVED
>
> **This repository has been moved to: [https://github.com/FranzDiebold/gen-ai-template](https://github.com/FranzDiebold/gen-ai-template)**
>
> Please update your references and bookmarks. This repository is now archived and will no longer be maintained.

# Ollama Jupyter Open WebUI Template 🚀

A template for your kickstart into GenAI! 🎁

It combines [Ollama](https://ollama.com/), [Jupyter](https://jupyter.org/) and [Open WebUI](https://openwebui.com/)!

## How to use

To spin up the "application" run:

`make run`

This will spin up the following services:

- [`localhost:8888/<TOKEN_HERE>`](http://localhost:8888): [JupyterLab](https://jupyterlab.readthedocs.io/en/latest/)
- [`localhost:8080`](http://localhost:8080): [Open WebUI](https://openwebui.com/)

## `app` folder

If you work with Jupyter, you can use the `app` folder to store your notebooks and other files.
You can add your requirements to the `app/requirements.txt` file, and they will be installed in the Jupyter container.

## Preload Ollama models

If you want to preload models, just add them to the `ollama/models_to_preload.txt` file.
