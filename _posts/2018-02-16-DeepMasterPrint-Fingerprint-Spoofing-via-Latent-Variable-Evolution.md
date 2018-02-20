---
layout: post
title: "DeepMasterPrint: Fingerprint Spoofing via Latent Variable Evolution"
date: 2018-02-16 22:42:13
categories: arXiv_CV
tags: arXiv_CV Adversarial Recognition
author: Philip Bontrager, Aditi Roy, Julian Togelius, Nasir Memon
mathjax: true
---

* content
{:toc}

##### Abstract
Biometric authentication is important for a large range of systems, including but not limited to consumer electronic devices such as phones. Understanding the limits of and attacks on such systems is therefore crucial. This paper presents an attack on fingerprint recognition system using MasterPrints, synthetic fingerprints that are capable of spoofing multiple people's fingerprints. The method described is the first to generate complete image-level Masterprints, and further exceeds the attack accuracy of previous methods that could not produce complete images. The method, Latent Variable Evolution, is based on training a Generative Adversarial Network on a set of real fingerprint images. Stochastic search in the form of the Covariance Matrix Adaptation Evolution Strategy is then used to search for latent variable (inputs) to the generator network that optimize the number of matches from a fingerprint recognizer. We find MasterPrints that a commercial fingerprint system matches to 23% of all users in a strict security setting, and 77% of all users at a looser security setting. The underlying method is likely to have broad usefulness for security research as well as in aesthetic domains.

##### Abstract (translated by Google)
生物识别认证对于大量系统非常重要，包括但不限于消费类电子设备，如手机。因此了解这些系统的限制和攻击是至关重要的。本文介绍了一种使用MasterPrints指纹识别系统的攻击手段，它能够欺骗多人的指纹。所描述的方法是首先生成完整的图像级主印迹，并且进一步超过了先前方法的不能产生完整图像的攻击精度。该方法潜变量进化基于在一组真实指纹图像上训练生成对抗网络。然后使用协方差矩阵自适应演化策略形式的随机搜索来搜索发生器网络的潜在变量（输入），以优化来自指纹识别器的匹配数量。我们发现MasterPrints指出，商业指纹系统在严格的安全设置中与所有用户中的23％相匹配，并且77％的所有用户在较宽松的安全设置下。潜在的方法可能对安全性研究以及审美领域具有广泛的用处。

##### URL
[http://arxiv.org/abs/1705.07386](http://arxiv.org/abs/1705.07386)

##### PDF
[http://arxiv.org/pdf/1705.07386](http://arxiv.org/pdf/1705.07386)

