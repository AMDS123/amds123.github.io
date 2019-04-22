---
layout: post
title: "Evolving Deep Neural Networks by Multi-objective Particle Swarm Optimization for Image Classification"
date: 2019-03-21 02:55:14
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Optimization Classification
author: Bin Wang, Yanan Sun, Bing Xue, Mengjie Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, convolutional neural networks (CNNs) have become deeper in order to achieve better classification accuracy in image classification. However, it is difficult to deploy the state-of-the-art deep CNNs for industrial use due to the difficulty of manually fine-tuning the hyperparameters and the trade-off between classification accuracy and computational cost. This paper proposes a novel multi-objective optimization method for evolving state-of-the-art deep CNNs in real-life applications, which automatically evolves the non-dominant solutions at the Pareto front. Three major contributions are made: Firstly, a new encoding strategy is designed to encode one of the best state-of-the-art CNNs; With the classification accuracy and the number of floating point operations as the two objectives, a multi-objective particle swarm optimization method is developed to evolve the non-dominant solutions; Last but not least, a new infrastructure is designed to boost the experiments by concurrently running the experiments on multiple GPUs across multiple machines, and a Python library is developed and released to manage the infrastructure. The experimental results demonstrate that the non-dominant solutions found by the proposed algorithm form a clear Pareto front, and the proposed infrastructure is able to almost linearly reduce the running time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09035](http://arxiv.org/abs/1904.09035)

##### PDF
[http://arxiv.org/pdf/1904.09035](http://arxiv.org/pdf/1904.09035)

