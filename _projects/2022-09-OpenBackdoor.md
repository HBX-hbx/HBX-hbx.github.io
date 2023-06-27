---
title: "A Unified Evaluation of Textual Backdoor Learning: Frameworks and Benchmarks"
excerpt: "NeurIPS 2022 Datasets & Benchmarks. The pipe of Openbackdoor toolkit: <br/><img src='/images/hbx/pipeline.png'>"
collection: projects
date: 2022-09-17
---



Background:

* The differences between real-world scenarios (e.g. releasing poisoned datasets or models) are neglected, and we argue that each scenario has its own constraints and concerns, thus requires specific evaluation protocols.
* The evaluation metrics only consider whether the attacks could flip the models’ predictions on poisoned samples and retain performances on benign samples, but ignore that poisoned samples should also be stealthy and semantic-preserving.

Contributions:

* Summarize three practical scenarios of attack methods based on their accessibility and goals.
* Conclude novel metrics for three evaluation dimensions and recommend scenario-specified evaluation methodologies.
* Develop an open-source toolkit [OpenBackdoor](https://github.com/thunlp/OpenBackdoor) and conduct extensive benchmark experiments.
* Propose **CUBE**, a simple yet strong baseline method targeting purifying poisoned datasets.