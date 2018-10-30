---
layout: post
title: "RecurJac: An Efficient Recursive Algorithm for Bounding Jacobian Matrix of Neural Networks and Its Applications"
date: 2018-10-28 09:25:08
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN
author: Huan Zhang, Pengchuan Zhang, Cho-Jui Hsieh
mathjax: true
---

* content
{:toc}

##### Abstract
The Jacobian matrix (or the gradient for single-output networks) is directly related to many important properties of neural networks, such as the function landscape, stationary points, (local) Lipschitz constants and robustness to adversarial attacks. In this paper, we propose a recursive algorithm, RecurJac, to compute both upper and lower bounds for each element in the Jacobian matrix of a neural network with respect to network's input, and the network can contain a wide range of activation functions. As a byproduct, we can efficiently obtain a (local) Lipschitz constant, which plays a crucial role in neural network robustness verification, as well as the training stability of GANs. Experiments show that (local) Lipschitz constants produced by our method is of better quality than previous approaches, thus providing better robustness verification results. Our algorithm has polynomial time complexity, and its computation time is reasonable even for relatively large networks. Additionally, we use our bounds of Jacobian matrix to characterize the landscape of the neural network, for example, to determine whether there exist stationary points in a local neighborhood. Source code available at https://github.com/huanzhang12/RecurJac-Jacobian-Bounds.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11783](http://arxiv.org/abs/1810.11783)

##### PDF
[http://arxiv.org/pdf/1810.11783](http://arxiv.org/pdf/1810.11783)

