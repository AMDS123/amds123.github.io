---
layout: post
title: "Unsupervised Cross-Domain Image Generation"
date: 2016-11-07 18:14:57
categories: arXiv_CV
tags: arXiv_CV GAN Face
author: Yaniv Taigman, Adam Polyak, Lior Wolf
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of transferring a sample in one domain to an analog sample in another domain. Given two related domains, S and T, we would like to learn a generative function G that maps an input sample from S to the domain T, such that the output of a given function f, which accepts inputs in either domains, would remain unchanged. Other than the function f, the training data is unsupervised and consist of a set of samples from each domain. The Domain Transfer Network (DTN) we present employs a compound loss function that includes a multiclass GAN loss, an f-constancy component, and a regularizing component that encourages G to map samples from T to themselves. We apply our method to visual domains including digits and face images and demonstrate its ability to generate convincing novel images of previously unseen entities, while preserving their identity.

##### Abstract (translated by Google)
我们研究将一个域中的样本转移到另一个域中的模拟样本的问题。给定两个相关的域S和T，我们想要学习一个生成函数G，它将输入样本从S映射到域T，使得在任一域中接受输入的给定函数f的输出将保持不变。除了函数f之外，训练数据是无监督的并且由来自每个域的一组样本组成。我们提出的域转移网络（DTN）采用复合损失函数，包括多类GAN损失，f恒常成分和鼓励G将样本从T映射到自己的正则化成分。我们将我们的方法应用到视觉领域，包括数字和脸部图像，并展示其能够产生以前看不见的实体令人信服的新形象，同时保留其身份。

##### URL
[https://arxiv.org/abs/1611.02200](https://arxiv.org/abs/1611.02200)

##### PDF
[https://arxiv.org/pdf/1611.02200](https://arxiv.org/pdf/1611.02200)

