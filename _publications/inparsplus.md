---
title: "InPars+: Supercharging Synthetic Data Generation for IR"
authors: <b>Matey Krastev</b>, Miklos Hamar, Danilo Toapanta, Jesse Brouwers, Yibin Lei
collection: publications
category: journals
permalink: /publication/inparsplus
excerpt: 'This work revisits and extends synthetic query generation pipelines for Neural Information
Retrieval (NIR) by leveraging the InPars Toolkit, a reproducible, end-to-end framework for
generating training data using large language models (LLMs). We first assess the
reproducibility of the original InPars, InPars-V2, and Promptagator pipelines on the SciFact
benchmark and validate their effectiveness using open-source reranker and generator
models. Building on this foundation, we introduce two key extensions to the pipeline:(1) fine …'
date: 2025-08-25
venue: 'Arxiv pre-print'
thumbnail: /images/publications/inparsplus.png
paperurl: https://arxiv.org/pdf/2508.13930v1
code: https://github.com/danilotpnta/IR2-Project
citation: 'Krastev, M., Hamar, M., Toapanta, D., Brouwers, J., & Lei, Y. (2025). InPars+: Supercharging Synthetic Data Generation for Information Retrieval Systems. arXiv preprint arXiv:2508.13930.'
featured: true
---

# Abstract
This work revisits and extends synthetic query generation pipelines
for Neural Information Retrieval (NIR) by leveraging the InPars
Toolkit, a reproducible, end-to-end framework for generating training data using large language models (LLMs). We first assess the
reproducibility of the original InPars, InPars-V2, and Promptagator
pipelines on the SciFact benchmark and validate their effectiveness
using open-source reranker and generator models. Building on this
foundation, we introduce two key extensions to the pipeline: (1)
fine-tuning a query generator LLM via Contrastive Preference Optimization (CPO) to improve the signal quality in generated queries,
and (2) replacing static prompt templates with dynamic, Chain-of-Thought (CoT) optimized prompts using the DSPy framework. Our
results show that both extensions reduce the need for aggressive filtering while improving retrieval performance. All code, models, and
synthetic datasets are publicly released to support further research:
<https://github.com/danilotpnta/IR2-project>.
