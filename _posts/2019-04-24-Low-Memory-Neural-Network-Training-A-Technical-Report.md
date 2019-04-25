---
layout: post
title: "Low-Memory Neural Network Training: A Technical Report"
date: 2019-04-24 03:44:58
categories: arXiv_CV
tags: arXiv_CV Image_Classification Inference Classification Deep_Learning
author: Nimit Sharad Sohoni, Christopher Richard Aberger, Megan Leszczynski, Jian Zhang, Christopher Ré
mathjax: true
---

* content
{:toc}

##### Abstract
Memory is increasingly often the bottleneck when training neural network models. Despite this, techniques to lower the overall memory requirements of training have been less widely studied compared to the extensive literature on reducing the memory requirements of inference. In this paper we study a fundamental question: How much memory is actually needed to train a neural network? To answer this question, we profile the overall memory usage of training on two representative deep learning benchmarks -- the WideResNet model for image classification and the DynamicConv Transformer model for machine translation -- and comprehensively evaluate four standard techniques for reducing the training memory requirements: (1) imposing sparsity on the model, (2) using low precision, (3) microbatching, and (4) gradient checkpointing. We explore how each of these techniques in isolation affects both the peak memory usage of training and the quality of the end model, and explore the memory, accuracy, and computation tradeoffs incurred when combining these techniques. Using appropriate combinations of these techniques, we show that it is possible to the reduce the memory required to train a WideResNet-28-2 on CIFAR-10 by up to 60.7x with a 0.4% loss in accuracy, and reduce the memory required to train a DynamicConv model on IWSLT'14 German to English translation by up to 8.7x with a BLEU score drop of 0.15.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.10631](https://arxiv.org/abs/1904.10631)

##### PDF
[https://arxiv.org/pdf/1904.10631](https://arxiv.org/pdf/1904.10631)

