---
layout: archive
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Download [CV](http://hbx-hbx.github.io/files/CV__English_.pdf)

Education
======

* B.Eng. in Computer Science and Technology, Tsinghua University, Beijing, China, 2020-2024
* PhD candidate in Computer Science and Technology, Tsinghua University, Beijing, China, 2024-2029 (expected)

Academic
======

* **GPA**: 3.97 / 4.00, **Rank**: 4/181
* Courses of **A+** : **English for Academic Purposes (A): Spoken Communication**, Probability and Statistics, Physics for Scientists and Engineers B(2), **Artificial Neural Networks**, Diploma Project(Thesis)
* Courses of **A** : Fundamentals of Computer Science, **Fundamentals of Programming, Programing and Training, Foundation of Object-Oriented Programming, Assembly Language Programming, Calculus A(1), Calculus A(2), Linear Algebra, Advanced Topics in Linear Algebra, Discrete Mathematics(1)**, Physics for Scientists and Engineers B(1), Introduction to Artificial Intelligence, Software Engineering, **Digital Logic Circuit, Digital Logic Experimentation**, Fundamentals of Computer Graphics, Introduction to Modern Cryptography, **Principles of Signal Processing**, **Principles and Practice of Compiler Construction**, Introduction to High Performance Computing, **Operating Systems**, Database Special Topic Training, **Cybersecurity Fundamentals**
* A member of THUNLP (THU Natural Language Processing Group), advised by Associate Professor Zhiyuan Liu.

Publications
======

(*indicates equal contribution)

- **Process Reinforcement through Implicit Rewards** [[Blog\]](https://curvy-check-498.notion.site/Process-Reinforcement-through-Implicit-Rewards-15f4fcb9c42180f1b498cc9b2eaf896f)<br>
  Ganqu Cui\*, Lifan Yuan\*, Zefan Wang\*, Hanbin Wang\*, Wendi Li\*, **Bingxiang He\***, Yuchen Fan\*, Tianyu Yu\*, Qixin Xu\*, Weize Chen, Jiarui Yuan, Huayu Chen, Kaiyan Zhang, Xingtai Lv, Shuo Wang, Yuan Yao, Xu Han, Hao Peng, Yu Cheng, Zhiyuan Liu, Maosong Sun, Bowen Zhou, Ning Ding
  *ICML 2025 Submission* [[code](https://github.com/PRIME-RL/PRIME)]

- **EscapeBench: Pushing Language Models to Think Outside the Box** [[Paper\]](https://arxiv.org/abs/2412.13549)<br>
  Cheng Qian, Peixuan Han, Qinyu Luo, **Bingxiang He**, Xiusi Chen, Yuji Zhang, Hongyi Du, Jiarui Yao, Xiaocheng Yang, Denghui Zhang, Yunzhu Li, Heng Ji
  *ACL 2025 Submission* [[code](https://github.com/qiancheng0/EscapeBench)]

- **Zero-Shot Generalization during Instruction Tuning: Insights from Similarity and Granularity** [[Paper\]](https://arxiv.org/abs/2406.11721)<br>
  **Bingxiang He\***, Ning Ding\*, Cheng Qian\*, Jia Deng, Ganqu Cui, Lifan Yuan, Haiwen Hong, Huan-ang Gao, Longtao Huang, Hui Xue, Huimin Chen, Zhiyuan Liu, Maosong Sun
  *ACL 2025 Submission* [[code](https://github.com/thunlp/Dynamics-of-Zero-Shot-Generalization)]

- **Tell Me More! Towards Implicit User Intention Understanding of Language Model Driven Agents** [[Paper\]](https://arxiv.org/abs/2402.09205)<br>
  Cheng Qian\*, **Bingxiang He\***, Zhong Zhuang, Jia Deng, Yujia Qin, Xin Cong, Zhong Zhang, Jie Zhou, Yankai Lin, Zhiyuan Liu, Maosong Sun.<br>
  *ACL 2024 Main* [[code](https://github.com/HBX-hbx/Mistral-Interact)]

- **UltraFeedback: Boosting Language Models with High-quality Feedback** [[Paper\]](https://arxiv.org/abs/2310.01377)<br>
  Ganqu Cui\*, Lifan Yuan\*, Ning Ding, Guanming Yao, **Bingxiang He**, Wei Zhu, Yuan Ni, Guotong Xie, Ruobing Xie, Yankai Lin, Zhiyuan Liu, Maosong Sun.<br>
  *ICML 2024 Poster*

- **Beat LLMs at Their Own Game: Zero-Shot LLM-Generated Text Detection via Querying ChatGPT** [[Paper\]](https://aclanthology.org/2023.emnlp-main.463)<br>
  Biru Zhu, Lifan Yuan, Ganqu Cui, Yangyi Chen, Chong Fu, **Bingxiang He**, Yangdong Deng, Zhiyuan Liu, Maosong Sun, Ming Gu.<br>
  *EMNLP 2023 Main* [[code](https://github.com/thunlp/LLM-generated-text-detection)]

- **A Unified Evaluation of Textual Backdoor Learning: Frameworks and Benchmarks** [[Paper]](https://arxiv.org/abs/2206.08514)  **(Spotlight)**<br>
  Ganqu Cui\*, Lifan Yuan\*, **Bingxiang He**, Yangyi Chen, Zhiyuan Liu, Maosong Sun.<br>
  *NeurIPS Datasets & Benchmarks 2022* [[code]](https://github.com/thunlp/OpenBackdoor)

# Projects

+ **OpenBackdoor: An open-source toolkit for textual backdoor attack and defense [[GitHub]](https://github.com/thunlp/OpenBackdoor) [[Paper]](https://arxiv.org/abs/2206.08514)**
  + Summarize three practical scenarios of attack methods based on their accessibility and goals.
  + Conclude novel metrics for three evaluation dimensions and recommend scenario-specified evaluation methodologies.
  + Develop an open-source toolkit OpenBackdoor and conduct extensive benchmark experiments.
  + Propose **CUBE**, a simple yet strong baseline method targeting purifying poisoned datasets.
+ **Tell Me More: Implementation and evaluation of Mistral-Interact [[GitHub]](https://github.com/OpenBMB/Tell_Me_More) [[Paper]](https://arxiv.org/abs/2402.09205)**
  + Better understanding of user judgments
  + Comprehensive summarization of user intentions
  + Enhanced model-user interaction experience
  + Comparable performance with closed-source GPT-4

+ **UltraFeedback: A large-scale, fine-grained, diverse preference dataset [[GitHub]](https://github.com/OpenBMB/UltraFeedback) [[Paper]](https://arxiv.org/abs/2310.01377)**
  + **Scale**: UltraFeedback consists of 64k prompts, 256k responses and high-quality feedback. RLHF researchers could further construct around 340k comparison pairs to train their reward models.
  + **Diversity**: We collect prompts from various sources and query a diverse set of state-of-the-art open-source and prestigious models. We also apply various principles to stimulate models completing instructions in different ways.
  + **High-density**: UltraFeedback provides both numerical and textual feedback. Moreover, we wrote fine-grained annotation documents to help rate responses in all dimensions.

+ **PRIME: Scalable RL solution for advanced reasoning of language models [[GitHub]](https://github.com/PRIME-RL/PRIME) [[Blog]](https://curvy-check-498.notion.site/Process-Reinforcement-through-Implicit-Rewards-15f4fcb9c42180f1b498cc9b2eaf896f)**
  + We present **PRIME** (**P**rocess **R**einforcement through **IM**plicit R**E**wards), an open-source solution for online RL with process rewards, to advance reasoning abilities of language models **beyond imitation or distillation.**
  + With PRIME, starting from Qwen2.5-Math-7B-Base, our trained model Eurus-2-7B-PRIME achieves **26.7% pass@1 on AIME 2024**, surpassing GPT-4o and Qwen2.5-Math-7B-Instruct. We achieve this **with only 1/10 data of Qwen Math (230K SFT + 150K RL).**
  + We also explore inference-time scaling and train EurusPRM, a **SOTA-level math PRM** that pushes the boundary even further.



<!-- Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

Honors & Awards
======

* Second Prize in Freshmen Scholarship, Tsinghua University. (09, 2020)
* Second Prize in National Undergraduate Physics Competition, Beijing Physics Society. (04, 2021)
* Comprehensive Merit Scholarship of Tsinghua for the 2020-2021 school year, Dept. of CST. (10, 2021)
* Third Prize in THU Challenge Cup Academic Competition, Tsinghua University. (04, 2022)
* Comprehensive Merit Scholarship of Tsinghua for the 2021-2022 school year, Dept. of CST. (10, 2022)
* Comprehensive Merit Scholarship of Tsinghua for the 2022-2023 school year, Dept. of CST. (10, 2023)
* Five Star ZiJing Volunteer Award, Tsinghua University Communist Youth League Committee. (05, 2024)
* Outstanding Paper Award for Diploma Project, Tsinghua University. (06, 2024)
* Outstanding Graduate Award, Beijing Municipal Education Commission. (06, 2024)

Skills & Expertise 
======

* Platform: Linux, Windows
* Tool: Git, SSH, Make, Tmux, Markdown, LaTeX
* Computer Language: C/C++ == Python > JavaScript == TypeScript > SQL
* Full-stack development: React, Django, Nginx, MySQL
* Rich experience in state-of-the-art deep learning techniques.
