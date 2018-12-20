---
layout: post
title: "AlphaX: eXploring Neural Architectures with Deep Neural Networks and Monte Carlo Tree Search"
date: 2018-12-19 07:47:47
categories: arXiv_AI
tags: arXiv_AI Image_Caption Object_Detection Style_Transfer Caption Detection
author: Linnan Wang, Yiyang Zhao, Yuu Jinnai, Rodrigo Fonseca
mathjax: true
---

* content
{:toc}

##### Abstract
We present AlphaX, a fully automated agent that designs complex neural architectures from scratch. AlphaX explores the exponential search space with a distributed Monte Carlo Tree Search (MCTS) and a Meta-Deep Neural Network (DNN). MCTS intrinsically improves the search efficiency by dynamically balancing the exploration and exploitation at fine-grained states, while Meta-DNN predicts the network accuracy to guide the search, and to provide an estimated reward to speed up the rollout. As the search progresses, AlphaX also generates the training data for Meta-DNN. So, the learning of Meta-DNN is end-to-end. In 14 days with only 16 GPUs (1832 samples), AlphaX found an architecture that reaches the state-of-the-art accuracies on both CIFAR-10(97.18%) and ImageNet(75.5% top-1 and 92.2% top-5). This demonstrates up to 10$\times$ speedup over the original searching for NASNet that used 500 GPUs in 4 days (20000 samples). In addition, we show the searched architecture improves a variety of vision applications ranging from Neural Style Transfer, to Image Captioning and Object Detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.07440](http://arxiv.org/abs/1805.07440)

##### PDF
[http://arxiv.org/pdf/1805.07440](http://arxiv.org/pdf/1805.07440)

