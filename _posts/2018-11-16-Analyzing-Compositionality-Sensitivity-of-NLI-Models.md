---
layout: post
title: "Analyzing Compositionality-Sensitivity of NLI Models"
date: 2018-11-16 21:12:24
categories: arXiv_AI
tags: arXiv_AI Adversarial Inference RNN
author: Yixin Nie, Yicheng Wang, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Success in natural language inference (NLI) should require a model to understand both lexical and compositional semantics. However, through adversarial evaluation, we find that several state-of-the-art models with diverse architectures are over-relying on the former and fail to use the latter. Further, this compositionality unawareness is not reflected via standard evaluation on current datasets. We show that removing RNNs in existing models or shuffling input words during training does not induce large performance loss despite the explicit removal of compositional information. Therefore, we propose a compositionality-sensitivity testing setup that analyzes models on natural examples from existing datasets that cannot be solved via lexical features alone (i.e., on which a bag-of-words model gives a high probability to one wrong label), hence revealing the models' actual compositionality awareness. We show that this setup not only highlights the limited compositional ability of current NLI models, but also differentiates model performance based on design, e.g., separating shallow bag-of-words models from deeper, linguistically-grounded tree-based models. Our evaluation setup is an important analysis tool: complementing currently existing adversarial and linguistically driven diagnostic evaluations, and exposing opportunities for future work on evaluating models' compositional understanding.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07033](http://arxiv.org/abs/1811.07033)

##### PDF
[http://arxiv.org/pdf/1811.07033](http://arxiv.org/pdf/1811.07033)

