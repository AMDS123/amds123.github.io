---
layout: post
title: "Fast Task-Aware Architecture Inference"
date: 2019-02-15 12:00:24
categories: arXiv_CV
tags: arXiv_CV NAS Optimization Inference Deep_Learning
author: Efi Kokiopoulou, Anja Hauth, Luciano Sbaiz, Andrea Gesmundo, Gabor Bartok, Jesse Berent
mathjax: true
---

* content
{:toc}

##### Abstract
Neural architecture search has been shown to hold great promise towards the automation of deep learning. However in spite of its potential, neural architecture search remains quite costly. To this point, we propose a novel gradient-based framework for efficient architecture search by sharing information across several tasks. We start by training many model architectures on several related (training) tasks. When a new unseen task is presented, the framework performs architecture inference in order to quickly identify a good candidate architecture, before any model is trained on the new task. At the core of our framework lies a deep value network that can predict the performance of input architectures on a task by utilizing task meta-features and the previous model training experiments performed on related tasks. We adopt a continuous parametrization of the model architecture which allows for efficient gradient-based optimization. Given a new task, an effective architecture is quickly identified by maximizing the estimated performance with respect to the model architecture parameters with simple gradient ascent. It is key to point out that our goal is to achieve reasonable performance at the lowest cost. We provide experimental results showing the effectiveness of the framework despite its high computational efficiency.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1902.05781](https://arxiv.org/abs/1902.05781)

##### PDF
[https://arxiv.org/pdf/1902.05781](https://arxiv.org/pdf/1902.05781)

