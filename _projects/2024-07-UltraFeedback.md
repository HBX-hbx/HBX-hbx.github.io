---
title: "UltraFeedback"
excerpt: "A large-scale, fine-grained, diverse preference dataset (and models).<br/><img src='/images/hbx/project_ultrafeedback.png'>"
collection: projects
date: 2024-07-01
---

[**GitHub Repo**](https://github.com/openbmb/UltraFeedback)

**Introduction:**

UltraFeedback is a large-scale, fine-grained, diverse preference dataset, used for training powerful reward models and critic models. We collect about 64k prompts from diverse resources (including UltraChat, ShareGPT, Evol-Instruct, TruthfulQA, FalseQA, and FLAN, see here for dataset statistics). We then use these prompts to query multiple LLMs (see here for model lists) and generate 4 different responses for each prompt, resulting in a total of 256k samples.

To collect high-quality preference and textual feedback, we design a fine-grained annotation instruction, which contains 4 different aspects, namely instruction-following, truthfulness, honesty and helpfulness. We then ask GPT-4 to annotate the collected samples based on the instruction.

**Features:**

* Scale: UltraFeedback consists of 64k prompts, 256k responses and high-quality feedback. RLHF researchers could further construct around 340k comparison pairs to train their reward models.
* Diversity: As a preference dataset, diversity is the core requirement for UltraFeedback. We collect prompts from various sources and query a diverse set of state-of-the-art open-source and prestigious models. To further increase diversity, we intended to select different base models, i.e., LLaMA, Falcon, StarChat, MPT, GPT and Bard. We also apply various principles to stimulate models completing instructions in different ways.
* High-density: UltraFeedback provides both numerical and textual feedback. Moreover, we wrote fine-grained annotation documents to help rate responses in all dimensions