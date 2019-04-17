---
layout: post
title: "SparseMask: Differentiable Connectivity Learning for Dense Image Prediction"
date: 2019-04-16 13:13:53
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Prediction Gradient_Descent
author: Huikai Wu, Junge Zhang, Kaiqi Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we aim at automatically searching an efficient network architecture for dense image prediction. Particularly, we follow the encoder-decoder style and focus on automatically designing a connectivity structure for the decoder. To achieve that, we first design a densely connected network with learnable connections named Fully Dense Network, which contains a large set of possible final connectivity structures. We then employ gradient descent to search the optimal connectivity from the dense connections. The search process is guided by a novel loss function, which pushes the weight of each connection to be binary and the connections to be sparse. The discovered connectivity achieves competitive results on two segmentation datasets, while runs more than three times faster and requires less than half parameters compared to state-of-the-art methods. An extensive experiment shows that the discovered connectivity is compatible with various backbones and generalizes well to other dense image prediction tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07642](http://arxiv.org/abs/1904.07642)

##### PDF
[http://arxiv.org/pdf/1904.07642](http://arxiv.org/pdf/1904.07642)

