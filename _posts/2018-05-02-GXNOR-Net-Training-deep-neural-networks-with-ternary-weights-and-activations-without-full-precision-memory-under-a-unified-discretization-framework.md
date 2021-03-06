---
layout: post
title: "GXNOR-Net: Training deep neural networks with ternary weights and activations without full-precision memory under a unified discretization framework"
date: 2018-05-02 17:30:40
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Lei Deng, Peng Jiao, Jing Pei, Zhenzhi Wu, Guoqi Li
mathjax: true
---

* content
{:toc}

##### Abstract
There is a pressing need to build an architecture that could subsume these networks under a unified framework that achieves both higher performance and less overhead. To this end, two fundamental issues are yet to be addressed. The first one is how to implement the back propagation when neuronal activations are discrete. The second one is how to remove the full-precision hidden weights in the training phase to break the bottlenecks of memory/computation consumption. To address the first issue, we present a multi-step neuronal activation discretization method and a derivative approximation technique that enable the implementing the back propagation algorithm on discrete DNNs. While for the second issue, we propose a discrete state transition (DST) methodology to constrain the weights in a discrete space without saving the hidden weights. Through this way, we build a unified framework that subsumes the binary or ternary networks as its special cases, and under which a heuristic algorithm is provided at the website this https URL. More particularly, we find that when both the weights and activations become ternary values, the DNNs can be reduced to sparse binary networks, termed as gated XNOR networks (GXNOR-Nets) since only the event of non-zero weight and non-zero activation enables the control gate to start the XNOR logic operations in the original binary networks. This promises the event-driven hardware design for efficient mobile intelligence. We achieve advanced performance compared with state-of-the-art algorithms. Furthermore, the computational sparsity and the number of states in the discrete space can be flexibly modified to make it suitable for various hardware platforms.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1705.09283](https://arxiv.org/abs/1705.09283)

##### PDF
[https://arxiv.org/pdf/1705.09283](https://arxiv.org/pdf/1705.09283)

