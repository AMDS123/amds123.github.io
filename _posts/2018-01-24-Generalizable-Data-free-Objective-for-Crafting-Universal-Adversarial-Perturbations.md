---
layout: post
title: "Generalizable Data-free Objective for Crafting Universal Adversarial Perturbations"
date: 2018-01-24 17:36:57
categories: arXiv_AI
tags: arXiv_AI Adversarial Segmentation Semantic_Segmentation Optimization Inference Deep_Learning Recognition
author: Konda Reddy Mopuri, Aditya Ganeshan, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning models are susceptible to adversarial perturbations: small changes to input that can cause large changes in output. It is also demonstrated that there exist input-agnostic perturbations, called universal adversarial perturbations, which can change the inference of target model on most of the data samples. However, existing methods to craft universal perturbations are (i) task specific, (ii) require samples from the training data distribution, and (iii) perform complex optimizations. Also, because of the data dependence, fooling ability of the crafted perturbations is proportional to the available training data. In this paper, we present a novel, generalizable and data-free objective for crafting universal adversarial perturbations. Independent of the underlying task, our objective achieves fooling via corrupting the extracted features at multiple layers. Therefore, the proposed objective is generalizable to craft image-agnostic perturbations across multiple vision tasks such as object recognition, semantic segmentation and depth estimation. In the practical setting of black-box attacking scenario, we show that our objective outperforms the data dependent objectives to fool the learned models. Further, via exploiting simple priors related to the data distribution, our objective remarkably boosts the fooling ability of the crafted perturbations. Significant fooling rates achieved by our objective emphasize that the current deep learning models are now at an increased risk, since our objective generalizes across multiple tasks without the requirement of training data for crafting the perturbations.

##### Abstract (translated by Google)
机器学习模型容易受到对抗干扰：对输入的小改动可能会导致输出的巨大变化。还证明了存在输入不可知的扰动，称为通用对抗扰动，它可以改变大部分数据样本上目标模型的推理。然而，现有的制造通用扰动的方法是（i）任务特定的，（ii）需要来自训练数据分布的样本，以及（iii）执行复杂的优化。另外，由于数据的依赖性，制造的扰动的愚弄能力与可用的训练数据成正比。在本文中，我们提出了一个新的，可概括的，无数据的目标来制造普遍的对抗性扰动。与潜在的任务无关，我们的目标通过破坏多层提取的特征来实现愚弄。因此，所提出的目标是可推广的，以在多视觉任务（例如对象识别，语义分割和深度估计）上形成图像不可知的扰动。在黑箱攻击的实际情况下，我们表明，我们的目标胜过数据依赖目标来欺骗学习模型。此外，通过利用与数据分布相关的简单先验，我们的目标显着地提高了制造扰动的愚弄能力。我们的目标所达到的显着愚弄率强调，目前的深度学习模型现在处于增加的风险之中，因为我们的目标在多个任务中进行概括而不需要训练数据来制造扰动。

##### URL
[http://arxiv.org/abs/1801.08092](http://arxiv.org/abs/1801.08092)

##### PDF
[http://arxiv.org/pdf/1801.08092](http://arxiv.org/pdf/1801.08092)

