---
layout: post
title: "Regularizing Neural Networks for Future Trajectory Prediction via Inverse Reinforcement Learning"
date: 2019-07-10 06:00:51
categories: arXiv_CV
tags: arXiv_CV Regularization Reinforcement_Learning RNN Prediction
author: Dooseop Choi, Kyoungwook Min, Jeongdan Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Predicting distant future trajectories of agents in a dynamic scene is not an easy problem because the future trajectory of an agent is affected by not only his/her past trajectory but also the scene contexts. To tackle this problem, we propose a model based on recurrent neural networks (RNNs) and a novel method for training the model. The proposed model is based on an encoder-decoder architecture where the encoder encodes inputs (past trajectories and scene context information) while the decoder produces a trajectory from the context vector given by the encoder. We train the networks of the proposed model to produce a future trajectory, which is the closest to the true trajectory, while maximizing a reward from a reward function. The reward function is also trained at the same time to maximize the margin between the rewards from the ground-truth trajectory and its estimate. The reward function plays the role of a regularizer for the proposed model so the trained networks are able to better utilize the scene context information for the prediction task. We evaluated the proposed model on several public datasets. Experimental results show that the prediction performance of the proposed model is much improved by the regularization, which outperforms the-state-of-the-arts in terms of accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04525](http://arxiv.org/abs/1907.04525)

##### PDF
[http://arxiv.org/pdf/1907.04525](http://arxiv.org/pdf/1907.04525)

