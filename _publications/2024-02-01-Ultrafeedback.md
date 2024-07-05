---
title: "ULTRAFEEDBACK: Boosting Language Models with Scaled AI Feedback"
collection: publications
permalink: /publication/2024-02-01-Ultrafeedback
excerpt: 'We finally present UltraFeedback, a large-scale, high-quality, and diversified AI feedback dataset, which contains over 1 million GPT-4 feedback for 250k user-assistant conversations from various aspects. Built upon UltraFeedback, we align a LLaMA-based model by best-of-n sampling and reinforcement learning, demonstrating its exceptional performance on chat benchmarks.'
date: 2024-02-01
venue: '<b>ICML Poster</b>'
paperurl: 'https://arxiv.org/abs/2310.01377'
citation: 'Ultrafeedback: Boosting language models with high-quality feedback
G Cui, L Yuan, N Ding, G Yao, B He, W Zhu, Y Ni, G Xie, Z Liu… - arXiv preprint arXiv:2310.01377, 2023'

---

Learning from human feedback has become a pivot technique in aligning large language models (LLMs) with human preferences. However, acquiring vast and premium human feedback is bottlenecked by time, labor, and human capability, resulting in small sizes or limited topics of current datasets. This further hinders feedback learning as well as alignment research within the open-source community. To address this issue, we explore how to go beyond human feedback and collect high-quality AI feedback automatically for a scalable alternative. Specifically, we identify scale and diversity as the key factors for feedback data to take effect. Accordingly, we first broaden instructions and responses in both amount and breadth to encompass a wider range of user-assistant interactions. Then, we meticulously apply a series of techniques to mitigate annotation biases for more reliable AI feedback. We finally present UltraFeedback, a large-scale, high-quality, and diversified AI feedback dataset, which contains over 1 million GPT-4 feedback for 250k user-assistant conversations from various aspects. Built upon UltraFeedback, we align a LLaMA-based model by best-of-n sampling and reinforcement learning, demonstrating its exceptional performance on chat benchmarks. Our work validates the effectiveness of scaled AI feedback data in constructing strong open-source chat language models, serving as a solid foundation for future feedback learning research.

[Download paper here](https://arxiv.org/abs/2310.01377)

