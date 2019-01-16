---
layout: post
title: "Self-Supervised Deep Active Accelerated MRI"
date: 2019-01-14 20:13:00
categories: arXiv_CV
tags: arXiv_CV
author: Kyong Hwan Jin, Michael Unser, Kwang Moo Yi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to simultaneously learn to sample and reconstruct magnetic resonance images (MRI) to maximize the reconstruction quality given a limited sample budget, in a self-supervised setup. Unlike existing deep methods that focus only on reconstructing given data, thus being passive, we go beyond the current state of the art by considering both the data acquisition and the reconstruction process within a single deep-learning framework. As our network learns to acquire data, the network is active in nature. In order to do so, we simultaneously train two neural networks, one dedicated to reconstruction and the other to progressive sampling, each with an automatically generated supervision signal that links them together. The two supervision signals are created through Monte Carlo tree search (MCTS). MCTS returns a better sampling pattern than what the current sampling network can give and, thus, a better final reconstruction. The sampling network is trained to mimic the MCTS results using the previous sampling network, thus being enhanced. The reconstruction network is trained to give the highest reconstruction quality, given the MCTS sampling pattern. Through this framework, we are able to train the two networks without providing any direct supervision on sampling.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.04547](https://arxiv.org/abs/1901.04547)

##### PDF
[https://arxiv.org/pdf/1901.04547](https://arxiv.org/pdf/1901.04547)

