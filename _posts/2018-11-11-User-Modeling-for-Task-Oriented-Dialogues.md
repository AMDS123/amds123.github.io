---
layout: post
title: "User Modeling for Task Oriented Dialogues"
date: 2018-11-11 08:21:55
categories: arXiv_AI
tags: arXiv_AI Regularization Tracking RNN
author: Izzeddin Gur, Dilek Hakkani-Tur, Gokhan Tur, Pararth Shah
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce end-to-end neural network based models for simulating users of task-oriented dialogue systems. User simulation in dialogue systems is crucial from two different perspectives: (i) automatic evaluation of different dialogue models, and (ii) training task-oriented dialogue systems. We design a hierarchical sequence-to-sequence model that first encodes the initial user goal and system turns into fixed length representations using Recurrent Neural Networks (RNN). It then encodes the dialogue history using another RNN layer. At each turn, user responses are decoded from the hidden representations of the dialogue level RNN. This hierarchical user simulator (HUS) approach allows the model to capture undiscovered parts of the user goal without the need of an explicit dialogue state tracking. We further develop several variants by utilizing a latent variable model to inject random variations into user responses to promote diversity in simulated user responses and a novel goal regularization mechanism to penalize divergence of user responses from the initial user goal. We evaluate the proposed models on movie ticket booking domain by systematically interacting each user simulator with various dialogue system policies trained with different objectives and users.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04369](http://arxiv.org/abs/1811.04369)

##### PDF
[http://arxiv.org/pdf/1811.04369](http://arxiv.org/pdf/1811.04369)

