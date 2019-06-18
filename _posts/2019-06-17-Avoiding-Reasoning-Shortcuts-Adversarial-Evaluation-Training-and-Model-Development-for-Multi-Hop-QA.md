---
layout: post
title: "Avoiding Reasoning Shortcuts: Adversarial Evaluation, Training, and Model Development for Multi-Hop QA"
date: 2019-06-17 17:03:57
categories: arXiv_AI
tags: arXiv_AI Adversarial QA
author: Yichen Jiang, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-hop question answering requires a model to connect multiple pieces of evidence scattered in a long context to answer the question. In this paper, we show that in the multi-hop HotpotQA (Yang et al., 2018) dataset, the examples often contain reasoning shortcuts through which models can directly locate the answer by word-matching the question with a sentence in the context. We demonstrate this issue by constructing adversarial documents that create contradicting answers to the shortcut but do not affect the validity of the original answer. The performance of strong baseline models drops significantly on our adversarial evaluation, indicating that they are indeed exploiting the shortcuts rather than performing multi-hop reasoning. After adversarial training, the baseline's performance improves but is still limited on the adversarial evaluation. Hence, we use a control unit that dynamically attends to the question at different reasoning hops to guide the model's multi-hop reasoning. We show that this 2-hop model trained on the regular data is more robust to the adversaries than the baseline model. After adversarial training, this 2-hop model not only achieves improvements over its counterpart trained on regular data, but also outperforms the adversarially-trained 1-hop baseline. We hope that these insights and initial improvements will motivate the development of new models that combine explicit compositional reasoning with adversarial training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07132](http://arxiv.org/abs/1906.07132)

##### PDF
[http://arxiv.org/pdf/1906.07132](http://arxiv.org/pdf/1906.07132)

