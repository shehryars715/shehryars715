# Shehryar Ali

**AI Engineer** · Data Science, NUST Islamabad

I study how language models actually behave, then build with them: agents, the backends they run on, and the models underneath. Away from the keyboard, I'm reading or writing.

Before: AI Engineer Intern, Askari Bank Digital Lab.

<p align="center"><a href="https://github.com/shehryars715?tab=repositories"><img src="assets/interests.svg" width="520" alt="LLM research feeds agents (verify), agents ship on backends, and people using what ships raise the next research question."></a></p>

## What I work on

- **LLM research & fine-tuning**: full-parameter SFT with TRL, completion-only loss, placebo-controlled evals, log-prob scoring, HF Transformers
- **Agents & tool use**: LangGraph, tool calling and tool design, guardrails, structured output (Pydantic), agent evals, prompt caching
- **Backend & APIs**: FastAPI, REST and SSE, SQL and NL2SQL, JWT auth, Docker Compose, GitLab CI/CD
- **ML & data**: PyTorch, scikit-learn, pandas, FAISS, MCTS self-play

## What I've built

**[Labs-Agent](https://github.com/shehryars715/Lab-Agent)** · in beta with my classmates<br>
Hand it a lab manual; an agent writes, runs and fixes the code.

<p align="center"><a href="https://github.com/shehryars715/Lab-Agent"><img src="assets/labs-agent.svg" width="520" alt="Labs-Agent flowchart: a lab manual is read in one LLM call; gates check it can run here, and stop with a reason if not; then the agent writes taskN.py and runs it. If the exit code is 0 the task has passed and becomes your files; if not, it reads the error, fixes the code and writes again."></a></p>

**GSD Dashboard** · Askari Bank Digital Lab, 2026<br>
An agentic operations platform answering questions across lease, capex and procurement for 700+ staff.

<p align="center"><a href="https://www.linkedin.com/in/shehryars715/"><img src="assets/gsd-dashboard.svg" width="520" alt="Schematic of the GSD Dashboard for 700+ staff: a sidebar with Dashboard, Lease register, Reports, Audit log and Users; a scanned lease agreement is dropped in, its 38 fields are extracted, and it lands as a new row in the lease register. Built with React, FastAPI, Docling, GPT-OSS and MySQL."></a></p>

**[Finetune](https://github.com/shehryars715/Finetune)** · models on [Hugging Face](https://huggingface.co/shehryars715)<br>
Instruction-tuning two Pythia-410M checkpoints, full-parameter.

<p align="center"><a href="https://github.com/shehryars715/Finetune"><img src="assets/finetune.svg" width="520" alt="Line chart, Finetune: validation loss of the step-50K Pythia-410M checkpoint during one epoch of full-parameter SFT on Alpaca, falling from 1.75 at step 250 to 1.57 at step 1,500; mean token accuracy rose from 58.1% to 61.3%."></a></p>

**[MirrorTest](https://github.com/shehryars715/MirrorTest)** · paper under review<br>
Can LLM judges spot their own writing? Mostly, they just favour a letter.

<p align="center"><a href="https://github.com/shehryars715/MirrorTest"><img src="assets/mirrortest.svg" width="520" alt="Dot plot, MirrorTest placebo: on pairs where both answers are the judge&#x27;s own, the share of runs picking A. Qwen2.5-0.5B 98.9%; Qwen2.5-1.5B 9.7%; Qwen2.5-3B 34.9%; Qwen2.5-7B 98.9%; Qwen2.5-14B 72.0%; Gemma-2-9B 99.7%; Llama-3.2-3B 100.0%; Mistral-7B 99.3%. Chance is 50%; none is close."></a></p>

## Skills

| Area | Stack |
|---|---|
| **Languages** | Python · TypeScript / JavaScript · SQL · C++ · LaTeX |
| **LLMs & fine-tuning** | Hugging Face Transformers · TRL · full-parameter SFT · completion-only loss · LLaMA · Qwen · Pythia · RAG · prompt engineering · zero-shot classification (BART-MNLI) · Gemini API · Ollama |
| **Agents** | LangGraph · LangChain · deepagents · tool calling and tool design · guardrails · structured output (Pydantic) · agent evals · context engineering · prompt caching · human-in-the-loop · NL2SQL |
| **Evaluation & research** | placebo controls · position counterbalancing · first-token log-prob scoring · AUROC and bootstrap CIs · blind eval sets |
| **ML & data** | PyTorch · scikit-learn · Logistic Regression · LightGBM · SMOTE · MCTS self-play · YOLOv8 · MediaPipe · pandas · NumPy · FAISS · ETL pipelines · data cleaning and annotation |
| **Documents & OCR** | Docling · Tesseract OCR · JSON-schema validation · fuzzy matching |
| **Backend & web** | FastAPI · REST · SSE · JWT auth · MySQL · Supabase · React · Vite · Tailwind CSS · Streamlit |
| **DevOps & tools** | Docker · Docker Compose · GitLab CI/CD · Git · AWS Lightsail · Trivy |

## Say hi

<p align="center"><a href="mailto:shehryar0707@gmail.com"><img src="assets/hi-mail.svg" width="206" alt="Email: shehryar0707@gmail.com"></a> <a href="https://www.linkedin.com/in/shehryars715/"><img src="assets/hi-linkedin.svg" width="206" alt="LinkedIn: in/shehryars715"></a> <a href="https://huggingface.co/shehryars715"><img src="assets/hi-hf.svg" width="206" alt="Hugging Face: shehryars715"></a></p>

<p align="center"><sub>shehryar0707@gmail.com</sub></p>
