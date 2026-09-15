# Awesome-Prompt-Testing-Platform

## Top Prompt Testing Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on LLM Evaluation, Prompt Testing, Red Teaming, Datasets, Metrics & CI/CD Gates*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Prompt Testing**. These tools help teams systematically evaluate prompts, agents, and RAG pipelines with automated metrics, human feedback, red-teaming, and regression testing in development and CI/CD.



**Examples** include Promptfoo, Braintrust, LangSmith, Humanloop, DeepEval, Ragas, Confident AI, Galileo, PromptLayer, Helicone, Promptfoo Cloud, Langfuse, Agenta, and PromptPerfect (the category leaders).



**Open-source emphasis**: Prompt and LLM evaluation has a rich open-source ecosystem. **Promptfoo**, **DeepEval**, **Ragas**, **Langfuse**, **Agenta**, and related frameworks are widely used for offline testing, red-teaming, and CI gates. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



| Platform | Description | Starting Tier Price | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Promptfoo](https://www.promptfoo.dev/)** | Leading open-source LLM evaluation and red-teaming tool with cloud options; supports declarative configs, multi-model comparison, and CI/CD integration. | $50/month (Team plan) | Free forever (100% free open-source CLI/core; Cloud free tier for individuals) |
| **[Braintrust](https://www.braintrust.dev/)** | Evaluation-first platform for datasets, scoring, experiments, and production monitoring of LLM applications. | $249/month (Pro plan) | Free Starter plan (1 GB data/mo, 10k scores/mo, 1M trace spans, 14-day retention, $10/mo model credits) |
| **[LangSmith](https://www.langchain.com/langsmith)** | LangChain’s platform for tracing, evaluation, datasets, and prompt experimentation tightly integrated with LangChain/LangGraph. | $39/seat/month (Plus plan) | Free Developer plan (5,000 traces/mo, 1 seat, 14-day retention) |
| **[Humanloop](https://humanloop.com/)** | Enterprise prompt engineering and evaluation platform (Note: platform sunset announced Sept 2025). | Custom / Enterprise | Free trial (2 team members, 50 eval runs, 10,000 logs/mo) |
| **[DeepEval / Confident AI](https://www.confident-ai.com/)** | Open-source evaluation framework (DeepEval) with a commercial platform (Confident AI) for metrics, CI gates, and production monitoring. | $19.99/user/month (Starter plan) | Free Forever plan (2 seats, 1 project, 5 test runs/week, 1 GB trace data/mo, 7-day retention) |
| **[Ragas](https://docs.ragas.io/)** | Open-source RAG evaluation framework often paired with commercial or self-hosted observability tools. | Open-Source / Self-Hosted | Free forever (100% open-source Python framework; self-hosted limits depend on infrastructure) |
| **[Galileo](https://www.galileo.ai/)** | LLM evaluation and observability platform focused on quality, hallucination detection, and production insights. | $100/month (Pro plan billed annually) | Free plan (5,000 traces/mo, unlimited users and custom evaluations) |
| **[PromptLayer](https://www.promptlayer.com/)** | Prompt management and evaluation platform with versioning, logging, and testing capabilities. | $49/month (Pro plan) | Free plan (2,500 requests/mo, 10 playground runs/day, 10MB dataset storage) |
| **[Helicone](https://www.helicone.ai/)** | LLM observability platform that supports logging and analysis useful for prompt performance evaluation. | $79/month (Pro plan) | Free Hobby plan (10,000 requests/mo, 1 GB storage, 7-day retention, 1 seat) |
| **[Langfuse](https://www.langfuse.com/)** | Open-source LLM engineering platform with strong evaluation, datasets, experiments, and tracing (cloud and self-hosted). | $59/month (Team plan) | Free Hobby Cloud plan (50,000 units/mo, 2 users, 30-day retention) or unlimited self-hosted OSS |
| **[Agenta](https://agenta.ai/)** | Open-source LLMOps platform focused on prompt engineering, evaluation, and collaboration. | $49/month (Pro plan) | Free Hobby Cloud plan (5,000 agent runs/mo, 2 team members) or unlimited self-hosted OSS |
| **[PromptPerfect](https://promptperfect.jina.ai/)** | Tools aimed at optimizing and testing prompt quality. | $9.50/month (Standard plan) | Free plan (20 initial signup credits / up to 3 prompts/day) & 3-day free trial on paid plans |



## Open-Source GitHub Projects

- **[Promptfoo](https://github.com/promptfoo/promptfoo)**  

  Open-source CLI and library for evaluating prompts, agents, and RAGs. Supports red-teaming, vulnerability scanning, multi-model comparison, and CI/CD integration (MIT).



- **[DeepEval](https://github.com/confident-ai/deepeval)**  

  Open-source Python evaluation framework with research-backed metrics, pytest integration, and support for unit-test style LLM testing.



- **[Ragas](https://github.com/explodinggradients/ragas)**  

  Open-source framework specifically designed for evaluating Retrieval-Augmented Generation (RAG) pipelines with reference-free and reference-based metrics.



- **[Langfuse](https://github.com/langfuse/langfuse)**  

  Open-source LLM observability and evaluation platform with datasets, experiments, LLM-as-judge, and prompt-linked scoring.



- **[Agenta](https://github.com/Agenta-AI/agenta)**  

  Open-source platform for prompt engineering, versioning, evaluation, and collaborative testing of LLM applications.



- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)**  

  Open-source observability and evaluation toolkit for LLM and embedding workflows.



- **[Inspect AI and other evaluation harnesses](https://github.com/)**  

  Additional open frameworks for structured evaluation of language models and agents.



- **[Custom metric and LLM-as-judge open libraries](https://github.com/)**  

  Community implementations of scoring functions, judges, and evaluation pipelines.



- **[Red-teaming and adversarial testing open tools](https://github.com/)**  

  Projects focused on security and robustness testing of prompts and agents (Promptfoo is a primary example).



- **[Dataset management and experiment tracking open components](https://github.com/)**  

  Tools that support versioning of evaluation datasets and comparison of experiment runs.



### Additional Strong Open-Source Options

- Using **Promptfoo** for declarative multi-model testing and red-teaming in CI.

- Adopting **DeepEval** for pytest-native metric gates and regression testing.

- Applying **Ragas** when evaluating RAG systems specifically.

- Combining **Langfuse** or **Agenta** for end-to-end evaluation + observability + prompt management.

- Running open evaluation frameworks locally and in CI while optionally sending results to a hosted platform.

- Accepting that polished collaborative UIs, enterprise dataset management, and managed production monitoring still favor commercial platforms (Braintrust, LangSmith, Galileo, Confident AI, etc.).



**Frameworks for building custom systems**: Choose an open eval framework (Promptfoo, DeepEval, and/or Ragas) → define datasets and metrics → run evaluations in CI/CD → track experiments and link to prompts via Langfuse or similar → promote only versions that pass quality gates. This stack is fully open and production-proven for many teams. Commercial platforms remain useful when teams want a unified managed experience or advanced collaboration features.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Prompt and LLM evaluation tools process application outputs and often production data. Ensure appropriate data handling, privacy controls, and security practices, especially when self-hosting. Evaluation results are only as good as the metrics and datasets used. This list is not security or operational advice.



---

**Made for AI engineers, evaluation specialists, and teams building reliable LLM applications.**

Let's keep prompt testing rigorous, automated, and as open as practical.
