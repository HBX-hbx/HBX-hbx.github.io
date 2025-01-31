---
title: "PRIME"
excerpt: "The implementation and evaluation of Mistral-Interact, a powerful model that proactively assesses task vagueness, inquires user intentions, and refines them into actionable goals before starting downstream agent task execution. <br/><img src='/images/hbx/project_tellmemore.png'>"
collection: projects
date: 2024-02-01
---

[**GitHub Repo**](https://github.com/OpenBMB/Tell_Me_More)

**Introduction:**

We release Intention-in-Interaction (IN3) benchmark and develop Mistral-Interact, capable of discerning vague instructions and recovering missing details. Mistral-Interact has the following features:

- **Better understanding of user judgments**: Among all the open-source models, Mistral-Interact is the best at predicting task vagueness and missing details that users regard as necessary.

- **Comprehensive summarization of user intentions**: Mistral-Interact is effective in making an explicit and comprehensive summary based on detailed user intentions.

- **Enhanced model-user interaction experience**: Mistral-Interact inquires about missing details in vague tasks more reasonably and friendly than other open-source models, thus promoting a clearer understanding of the user’s implicit intentions.

- **Comparable performance with closed-source GPT-4**: We prove that smaller-scale model experts can approach or even exceed general-purpose large-scale models across various aspects including vagueness judgment, comprehensiveness of summaries, and friendliness of interaction.