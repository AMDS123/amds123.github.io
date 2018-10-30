---
layout: post
title: "A Hitchhiker's Guide On Distributed Training of Deep Neural Networks"
date: 2018-10-28 09:37:47
categories: arXiv_AI
tags: arXiv_AI Survey Deep_Learning Gradient_Descent
author: Karanbir Chahal, Manraj Singh Grover, Kuntal Dey
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has led to tremendous advancements in the field of Artificial Intelligence. One caveat however is the substantial amount of compute needed to train these deep learning models. Training a benchmark dataset like ImageNet on a single machine with a modern GPU can take upto a week, distributing training on multiple machines has been observed to drastically bring this time down. Recent work has brought down ImageNet training time to a time as low as 4 minutes by using a cluster of 2048 GPUs. This paper surveys the various algorithms and techniques used to distribute training and presents the current state of the art for a modern distributed training framework. More specifically, we explore the synchronous and asynchronous variants of distributed Stochastic Gradient Descent, various All Reduce gradient aggregation strategies and best practices for obtaining higher throughout and lower latency over a cluster such as mixed precision training, large batch training and gradient compression.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11787](http://arxiv.org/abs/1810.11787)

##### PDF
[http://arxiv.org/pdf/1810.11787](http://arxiv.org/pdf/1810.11787)

