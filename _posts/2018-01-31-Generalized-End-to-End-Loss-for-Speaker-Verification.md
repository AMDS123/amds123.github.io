---
layout: post
title: "Generalized End-to-End Loss for Speaker Verification"
date: 2018-01-31 22:11:24
categories: arXiv_CL
tags: arXiv_CL
author: Li Wan, Quan Wang, Alan Papir, Ignacio Lopez Moreno
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new loss function called generalized end-to-end (GE2E) loss, which makes the training of speaker verification models more efficient than our previous tuple-based end-to-end (TE2E) loss function. Unlike TE2E, the GE2E loss function updates the network in a way that emphasizes examples that are difficult to verify at each step of the training process. Additionally, the GE2E loss does not require an initial stage of example selection. With these properties, our model with the new loss function decreases speaker verification EER by more than 10%, while reducing the training time by 60% at the same time. We also introduce the MultiReader technique, which allows us to do domain adaptation - training a more accurate model that supports multiple keywords (i.e. "OK Google" and "Hey Google") as well as multiple dialects.

##### Abstract (translated by Google)
在本文中，我们提出了一种称为广义端到端（GE2E）丢失的新损失函数，这使得说话者验证模型的训练比我们以前的基于元组的端到端（TE2E）损失函数更有效。与TE2E不同的是，GE2E丢失功能以一种强调难以在训练过程的每一步中验证的例子的方式更新网络。此外，GE2E损失不需要选择示例的初始阶段。有了这些特性，我们的模型具有新的损失函数，使说话人验证EER减少了10％以上，同时减少了60％的训练时间。我们还介绍了MultiReader技术，该技术允许我们进行域名适应 - 培养支持多个关键字（即“OK Google”和“Hey Google”）以及多个方言的更准确的模型。

##### URL
[http://arxiv.org/abs/1710.10467](http://arxiv.org/abs/1710.10467)

##### PDF
[http://arxiv.org/pdf/1710.10467](http://arxiv.org/pdf/1710.10467)

