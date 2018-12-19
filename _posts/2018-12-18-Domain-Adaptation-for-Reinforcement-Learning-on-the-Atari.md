---
layout: post
title: "Domain Adaptation for Reinforcement Learning on the Atari"
date: 2018-12-18 16:08:57
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge Reinforcement_Learning Transfer_Learning
author: Thomas Carr, Maria Chli, George Vogiatzis
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning agents have recently been successful across a variety of discrete and continuous control tasks; however, they can be slow to train and require a large number of interactions with the environment to learn a suitable policy. This is borne out by the fact that a reinforcement learning agent has no prior knowledge of the world, no pre-existing data to depend on and so must devote considerable time to exploration. Transfer learning can alleviate some of the problems by leveraging learning done on some source task to help learning on some target task. Our work presents an algorithm for initialising the hidden feature representation of the target task. We propose a domain adaptation method to transfer state representations and demonstrate transfer across domains, tasks and action spaces. We utilise adversarial domain adaptation ideas combined with an adversarial autoencoder architecture. We align our new policies' representation space with a pre-trained source policy, taking target task data generated from a random policy. We demonstrate that this initialisation step provides significant improvement when learning a new reinforcement learning task, which highlights the wide applicability of adversarial adaptation methods; even as the task and label/action space also changes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07452](http://arxiv.org/abs/1812.07452)

##### PDF
[http://arxiv.org/pdf/1812.07452](http://arxiv.org/pdf/1812.07452)

