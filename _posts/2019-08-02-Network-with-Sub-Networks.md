---
layout: post
title: "Network with Sub-Networks"
date: 2019-08-02 09:04:28
categories: arXiv_CV
tags: arXiv_CV Inference
author: Ninnart Fuengfusin, Hakaru Tamukoh
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce network with sub-network, a neural network which their weight layer could be removed into sub-neural networks on demand during inference. This method provides selectivity in the number of weight layer. To develop the parameters which could be used in both base and sub-neural networks models, firstly, the weights and biases are copied from sub-models to base-model. Each model is forwarded separately. Gradients from both networks are averaged and, used to update both networks. From the empirical experiment, our base-model achieves the test-accuracy that is comparable to the regularly trained models, while it maintains the ability to remove the weight layers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00763](http://arxiv.org/abs/1908.00763)

##### PDF
[http://arxiv.org/pdf/1908.00763](http://arxiv.org/pdf/1908.00763)

