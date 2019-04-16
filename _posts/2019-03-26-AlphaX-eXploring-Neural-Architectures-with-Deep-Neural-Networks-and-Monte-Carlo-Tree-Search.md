---
layout: post
title: "AlphaX: eXploring Neural Architectures with Deep Neural Networks and Monte Carlo Tree Search"
date: 2019-03-26 04:54:53
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Style_Transfer Caption Detection
author: Linnan Wang, Yiyang Zhao, Yuu Jinnai, Yuandong Tian, Rodrigo Fonseca
mathjax: true
---

* content
{:toc}

##### Abstract
We present AlphaX, a fully automated agent that designs complex neural architectures from scratch. AlphaX explores the exponentially grown search space with a distributed Monte Carlo Tree Search (MCTS) and a Meta-Deep Neural Network (DNN). MCTS intrinsically improves the search efficiency by dynamically balancing the exploration and exploitation at fine-grained states, while Meta-DNN predicts the network accuracy to guide the search, and to provide an estimated reward to speed up the rollout. As the search progresses, AlphaX also generates the training data for Meta-DNN. So, the learning of Meta-DNN is end-to-end. In 14 days with only 16 GPUs (1832 samples), AlphaX found an architecture that reaches the state-of-the-art accuracies on both CIFAR-10(97.18%) and ImageNet(75.5% top-1 and 92.2% top-5). This demonstrates up to 10x speedup over the original searching for NASNet that used 500 GPUs in 4 days (20000 samples). On NASBench-101, AlphaX demonstrates 3x and 2.8x speedup over Random Search and Regularized Evolution. Finally, we show the searched architecture improves a variety of vision applications from Neural Style Transfer, to Image Captioning and Object Detection. Our implementation is available at this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.11059](https://arxiv.org/abs/1903.11059)

##### PDF
[https://arxiv.org/pdf/1903.11059](https://arxiv.org/pdf/1903.11059)

