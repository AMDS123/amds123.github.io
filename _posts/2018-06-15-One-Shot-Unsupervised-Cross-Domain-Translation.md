---
layout: post
title: "One-Shot Unsupervised Cross Domain Translation"
date: 2018-06-15 16:03:36
categories: arXiv_CV
tags: arXiv_CV
author: Sagie Benaim, Lior Wolf
mathjax: true
---

* content
{:toc}

##### Abstract
Given a single image x from domain A and a set of images from domain B, our task is to generate the analogous of x in B. We argue that this task could be a key AI capability that underlines the ability of cognitive agents to act in the world and present empirical evidence that the existing unsupervised domain translation methods fail on this task. Our method follows a two step process. First, a variational autoencoder for domain B is trained. Then, given the new sample x, we create a variational autoencoder for domain A by adapting the layers that are close to the image in order to directly fit x, and only indirectly adapt the other layers. Our experiments indicate that the new method does as well, when trained on one sample x, as the existing domain transfer methods, when these enjoy a multitude of training samples from domain A. Our code is made publicly available at https://github.com/sagiebenaim/OneShotTranslation

##### Abstract (translated by Google)
给定一个来自域A的图像x和来自域B的一组图像，我们的任务是产生与B相似的x。我们认为，这个任务可能是一个关键的AI功能，它强调了认知主体的行为能力世界和目前的经验证据表明，现有的无监督域翻译方法在这项任务上失败了。我们的方法遵循两个步骤。首先，训练域B的变分自动编码器。然后，给定新的样本x，我们为域A创建一个变分自动编码器，方法是调整靠近图像的图层以便直接拟合x，并间接调整其他图层。我们的实验表明，当在一个样本x上训练时，新方法也可以作为现有的域转移方法，当这些方法从域A中获得大量训练样本时，我们的代码将在https：// github上公开。 COM / sagiebenaim / OneShotTranslation

##### URL
[http://arxiv.org/abs/1806.06029](http://arxiv.org/abs/1806.06029)

##### PDF
[http://arxiv.org/pdf/1806.06029](http://arxiv.org/pdf/1806.06029)

