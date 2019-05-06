---
layout: post
title: "Improving Neural Architecture Search Image Classifiers via Ensemble Learning"
date: 2019-03-14 20:17:33
categories: arXiv_CV
tags: arXiv_CV Knowledge NAS CNN
author: Vladimir Macko, Charles Weill, Hanna Mazzawi, Javier Gonzalvo
mathjax: true
---

* content
{:toc}

##### Abstract
Finding the best neural network architecture requires significant time, resources, and human expertise. These challenges are partially addressed by neural architecture search (NAS) which is able to find the best convolutional layer or cell that is then used as a building block for the network. However, once a good building block is found, manual design is still required to assemble the final architecture as a combination of multiple blocks under a predefined parameter budget constraint. A common solution is to stack these blocks into a single tower and adjust the width and depth to fill the parameter budget. However, these single tower architectures may not be optimal. Instead, in this paper we present the AdaNAS algorithm, that uses ensemble techniques to compose a neural network as an ensemble of smaller networks automatically. Additionally, we introduce a novel technique based on knowledge distillation to iteratively train the smaller networks using the previous ensemble as a teacher. Our experiments demonstrate that ensembles of networks improve accuracy upon a single neural network while keeping the same number of parameters. Our models achieve comparable results with the state-of-the-art on CIFAR-10 and sets a new state-of-the-art on CIFAR-100.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.06236](https://arxiv.org/abs/1903.06236)

##### PDF
[https://arxiv.org/pdf/1903.06236](https://arxiv.org/pdf/1903.06236)

