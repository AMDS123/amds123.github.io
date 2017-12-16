---
layout: post
title: "Adversarial Images for Variational Autoencoders"
date: 2016-12-01 05:59:57
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Pedro Tabacof, Julia Tavares, Eduardo Valle
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate adversarial attacks for autoencoders. We propose a procedure that distorts the input image to mislead the autoencoder in reconstructing a completely different target image. We attack the internal latent representations, attempting to make the adversarial input produce an internal representation as similar as possible as the target's. We find that autoencoders are much more robust to the attack than classifiers: while some examples have tolerably small input distortion, and reasonable similarity to the target image, there is a quasi-linear trade-off between those aims. We report results on MNIST and SVHN datasets, and also test regular deterministic autoencoders, reaching similar conclusions in all cases. Finally, we show that the usual adversarial attack for classifiers, while being much easier, also presents a direct proportion between distortion on the input, and misdirection on the output. That proportionality however is hidden by the normalization of the output, which maps a linear layer into non-linear probabilities.

##### Abstract (translated by Google)
我们调查autoencoders的敌对攻击。我们提出一个程序，使输入图像变形，误导自编码器重建完全不同的目标图像。我们攻击内部的潜在表征，试图使对抗性输入产生与目标类似的内部表示。我们发现自动编码器对分类器的攻击比分类器更加鲁棒：虽然一些例子具有可接受的小输入失真，并且与目标图像具有合理的相似性，但在这些目标之间存在一个准线性的折衷。我们报告MNIST和SVHN数据集的结果，并测试常规确定性自编码器，在所有情况下得出类似的结论。最后，我们表明，对分类器来说，通常的对抗性攻击虽然容易得多，但也在输入失真和输出错误方面呈现出直接的比例。然而，这种比例是由输出的归一化隐藏的，它将线性层映射为非线性概率。

##### URL
[https://arxiv.org/abs/1612.00155](https://arxiv.org/abs/1612.00155)

##### PDF
[https://arxiv.org/pdf/1612.00155](https://arxiv.org/pdf/1612.00155)

