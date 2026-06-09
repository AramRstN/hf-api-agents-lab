# AI Models, APIs, and Agents Lab

Hands-on laboratory for exploring:

* Reusing pre-trained Machine Learning models
* Hugging Face models and pipelines
* Large Language Models (LLMs)
* OpenAI APIs
* Local LLMs with Ollama
* Building user interfaces with Gradio

---

## Learning Goals

By the end of this lab you will be able to:

* Reuse existing AI models instead of training from scratch
* Use Hugging Face models for inference
* Interact with LLMs through APIs
* Run local LLMs using Ollama
* Understand the foundations of AI agents

---

## Repository Structure

```text
hf-api-agents-lab/
│
├── notebooks/
│   ├── 00_setup.ipynb
│   ├── 01_hf_model_reuse.ipynb
│   ├── 02_hf_reuse_model_for_prediction.ipynb
│   ├── 03_openai_api.ipynb
│   └── 04_gradio_ui.ipynb
│
├── requirements.txt
├── .env
└── README.md
```

---

## Before Class

1. Install Ollama
2. Download at least one local model

```bash
ollama pull llama3.2
```

or

```bash
ollama pull qwen3:4b
```

3. Fork this repository
4. Clone your fork
5. Run:

```bash
notebooks/00_setup.ipynb
```

and make sure all checks pass successfully.

---

## During the Lab

Complete the exercises directly in your fork of this repository.

All coding activities will be performed together during the session.

---

## Submission

At the end of the lab:

```bash
git add .
git commit -m "Completed lab exercises"
git push
```

Then create a Pull Request from your fork back to the original repository.

Your Pull Request will be considered your lab submission.

---

## Useful Resources

* Ollama: https://ollama.com
* Hugging Face: https://huggingface.co
* OpenAI: https://platform.openai.com
* Gradio: https://gradio.app
