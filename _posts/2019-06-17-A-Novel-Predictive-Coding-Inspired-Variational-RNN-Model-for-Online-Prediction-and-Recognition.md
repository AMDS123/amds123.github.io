---
layout: post
title: "A Novel Predictive-Coding-Inspired Variational RNN Model for Online Prediction and Recognition"
date: 2019-06-17 14:59:40
categories: arXiv_AI
tags: arXiv_AI Optimization Inference RNN Prediction Recognition
author: Ahmadreza Ahmadi, Jun Tani
mathjax: true
---

* content
{:toc}

##### Abstract
This study introduces PV-RNN, a novel variational RNN inspired by the predictive-coding ideas. The model learns to extract the probabilistic structures hidden in fluctuating temporal patterns by dynamically changing the stochasticity of its latent states. Its architecture attempts to address two major concerns of variational Bayes RNNs: how can latent variables learn meaningful representations and how can the inference model transfer future observations to the latent variables. PV-RNN does both by introducing adaptive vectors mirroring the training data, whose values can then be adapted differently during evaluation. Moreover, prediction errors during backpropagation, rather than external inputs during the forward computation, are used to convey information to the network about the external data. For testing, we introduce error regression for predicting unseen sequences as inspired by predictive coding that leverages those mechanisms. The model introduces a weighting parameter, the meta-prior, to balance the optimization pressure placed on two terms of a lower bound on the marginal likelihood of the sequential data. We test the model on two datasets with probabilistic structures and show that with high values of the meta-prior the network develops deterministic chaos through which the data's randomness is imitated. For low values, the model behaves as a random process. The network performs best on intermediate values, and is able to capture the latent probabilistic structure with good generalization. Analyzing the meta-prior's impact on the network allows to precisely study the theoretical value and practical benefits of incorporating stochastic dynamics in our model. We demonstrate better prediction performance on a robot imitation task with our model using error regression compared to a standard variational Bayes model lacking such a procedure.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01339](http://arxiv.org/abs/1811.01339)

##### PDF
[http://arxiv.org/pdf/1811.01339](http://arxiv.org/pdf/1811.01339)

