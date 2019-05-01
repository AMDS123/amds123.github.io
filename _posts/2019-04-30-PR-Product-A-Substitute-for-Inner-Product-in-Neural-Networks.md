---
layout: post
title: "PR Product: A Substitute for Inner Product in Neural Networks"
date: 2019-04-30 10:43:38
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption CNN Image_Classification RNN Classification Deep_Learning
author: Zhennan Wang, Wenbin Zou, Chen Xu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we analyze the inner product of weight vector and input vector in neural networks from the perspective of vector orthogonal decomposition and prove that the local direction gradient of weight vector decreases as the angle between them gets closer to 0 or $\pi$. We propose the PR Product, a substitute for the inner product, which makes the local direction gradient of weight vector independent of the angle and consistently larger than the one in the conventional inner product while keeping the forward propagation identical. As the basic operation in neural networks, the PR Product can be applied into many existing deep learning modules, so we develop the PR Product version of the fully connected layer, convolutional layer, and LSTM layer. In static image classification, the experiments on CIFAR10 and CIFAR100 datasets demonstrate that the PR Product can robustly enhance the ability of various state-of-the-art classification networks. On the task of image captioning, even without any bells and whistles, our PR Product version of captioning model can compete or outperform the state-of-the-art models on MS COCO dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.13148](http://arxiv.org/abs/1904.13148)

##### PDF
[http://arxiv.org/pdf/1904.13148](http://arxiv.org/pdf/1904.13148)

