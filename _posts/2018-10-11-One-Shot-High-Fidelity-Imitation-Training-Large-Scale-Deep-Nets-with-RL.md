---
layout: post
title: "One-Shot High-Fidelity Imitation: Training Large-Scale Deep Nets with RL"
date: 2018-10-11 13:46:18
categories: arXiv_AI
tags: arXiv_AI Sparse Knowledge
author: Tom Le Paine, Sergio Gómez Colmenarejo, Ziyu Wang, Scott Reed, Yusuf Aytar, Tobias Pfaff, Matt W. Hoffman, Gabriel Barth-Maron, Serkan Cabi, David Budden, Nando de Freitas
mathjax: true
---

* content
{:toc}

##### Abstract
Humans are experts at high-fidelity imitation -- closely mimicking a demonstration, often in one attempt. Humans use this ability to quickly solve a task instance, and to bootstrap learning of new tasks. Achieving these abilities in autonomous agents is an open problem. In this paper, we introduce an off-policy RL algorithm (MetaMimic) to narrow this gap. MetaMimic can learn both (i) policies for high-fidelity one-shot imitation of diverse novel skills, and (ii) policies that enable the agent to solve tasks more efficiently than the demonstrators. MetaMimic relies on the principle of storing all experiences in a memory and replaying these to learn massive deep neural network policies by off-policy RL. This paper introduces, to the best of our knowledge, the largest existing neural networks for deep RL and shows that larger networks with normalization are needed to achieve one-shot high-fidelity imitation on a challenging manipulation task. The results also show that both types of policy can be learned from vision, in spite of the task rewards being sparse, and without access to demonstrator actions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05017](https://arxiv.org/abs/1810.05017)

##### PDF
[https://arxiv.org/pdf/1810.05017](https://arxiv.org/pdf/1810.05017)

