---
layout: post
title: "Generation of Policy-Level Explanations for Reinforcement Learning"
date: 2019-05-28 19:33:49
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Deep_Learning Relation
author: Nicholay Topin, Manuela Veloso
mathjax: true
---

* content
{:toc}

##### Abstract
Though reinforcement learning has greatly benefited from the incorporation of neural networks, the inability to verify the correctness of such systems limits their use. Current work in explainable deep learning focuses on explaining only a single decision in terms of input features, making it unsuitable for explaining a sequence of decisions. To address this need, we introduce Abstracted Policy Graphs, which are Markov chains of abstract states. This representation concisely summarizes a policy so that individual decisions can be explained in the context of expected future transitions. Additionally, we propose a method to generate these Abstracted Policy Graphs for deterministic policies given a learned value function and a set of observed transitions, potentially off-policy transitions used during training. Since no restrictions are placed on how the value function is generated, our method is compatible with many existing reinforcement learning methods. We prove that the worst-case time complexity of our method is quadratic in the number of features and linear in the number of provided transitions, $O(|F|^2 |tr\_samples|)$. By applying our method to a family of domains, we show that our method scales well in practice and produces Abstracted Policy Graphs which reliably capture relationships within these domains.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12044](http://arxiv.org/abs/1905.12044)

##### PDF
[http://arxiv.org/pdf/1905.12044](http://arxiv.org/pdf/1905.12044)

