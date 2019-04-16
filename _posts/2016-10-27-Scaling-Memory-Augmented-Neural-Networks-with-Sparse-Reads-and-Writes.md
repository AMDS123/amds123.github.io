---
layout: post
title: "Scaling Memory-Augmented Neural Networks with Sparse Reads and Writes"
date: 2016-10-27 22:38:05
categories: arXiv_CV
tags: arXiv_CV Sparse Language_Model Recognition
author: Jack W Rae, Jonathan J Hunt, Tim Harley, Ivo Danihelka, Andrew Senior, Greg Wayne, Alex Graves, Timothy P Lillicrap
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks augmented with external memory have the ability to learn algorithmic solutions to complex tasks. These models appear promising for applications such as language modeling and machine translation. However, they scale poorly in both space and time as the amount of memory grows --- limiting their applicability to real-world domains. Here, we present an end-to-end differentiable memory access scheme, which we call Sparse Access Memory (SAM), that retains the representational power of the original approaches whilst training efficiently with very large memories. We show that SAM achieves asymptotic lower bounds in space and time complexity, and find that an implementation runs $1,\!000\times$ faster and with $3,\!000\times$ less physical memory than non-sparse models. SAM learns with comparable data efficiency to existing models on a range of synthetic tasks and one-shot Omniglot character recognition, and can scale to tasks requiring $100,\!000$s of time steps and memories. As well, we show how our approach can be adapted for models that maintain temporal associations between memories, as with the recently introduced Differentiable Neural Computer.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1610.09027](https://arxiv.org/abs/1610.09027)

##### PDF
[https://arxiv.org/pdf/1610.09027](https://arxiv.org/pdf/1610.09027)

