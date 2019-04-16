---
layout: post
title: "Dual Learning for Machine Translation"
date: 2016-11-01 10:38:29
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning NMT
author: Yingce Xia, Di He, Tao Qin, Liwei Wang, Nenghai Yu, Tie-Yan Liu, Wei-Ying Ma
mathjax: true
---

* content
{:toc}

##### Abstract
While neural machine translation (NMT) is making good progress in the past two years, tens of millions of bilingual sentence pairs are needed for its training. However, human labeling is very costly. To tackle this training data bottleneck, we develop a dual-learning mechanism, which can enable an NMT system to automatically learn from unlabeled data through a dual-learning game. This mechanism is inspired by the following observation: any machine translation task has a dual task, e.g., English-to-French translation (primal) versus French-to-English translation (dual); the primal and dual tasks can form a closed loop, and generate informative feedback signals to train the translation models, even if without the involvement of a human labeler. In the dual-learning mechanism, we use one agent to represent the model for the primal task and the other agent to represent the model for the dual task, then ask them to teach each other through a reinforcement learning process. Based on the feedback signals generated during this process (e.g., the language-model likelihood of the output of a model, and the reconstruction error of the original sentence after the primal and dual translations), we can iteratively update the two models until convergence (e.g., using the policy gradient methods). We call the corresponding approach to neural machine translation \emph{dual-NMT}. Experiments show that dual-NMT works very well on English$\leftrightarrow$French translation; especially, by learning from monolingual data (with 10% bilingual data for warm start), it achieves a comparable accuracy to NMT trained from the full bilingual data for the French-to-English translation task.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1611.00179](https://arxiv.org/abs/1611.00179)

##### PDF
[https://arxiv.org/pdf/1611.00179](https://arxiv.org/pdf/1611.00179)

