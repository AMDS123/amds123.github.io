---
layout: post
title: "Bayesian Image Quality Transfer with CNNs: Exploring Uncertainty in dMRI Super-Resolution"
date: 2017-05-30 09:37:57
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Inference Deep_Learning
author: Ryutaro Tanno, Daniel E. Worrall, Aurobrata Ghosh, Enrico Kaden, Stamatios N. Sotiropoulos, Antonio Criminisi, Daniel C. Alexander
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we investigate the value of uncertainty modeling in 3D super-resolution with convolutional neural networks (CNNs). Deep learning has shown success in a plethora of medical image transformation problems, such as super-resolution (SR) and image synthesis. However, the highly ill-posed nature of such problems results in inevitable ambiguity in the learning of networks. We propose to account for intrinsic uncertainty through a per-patch heteroscedastic noise model and for parameter uncertainty through approximate Bayesian inference in the form of variational dropout. We show that the combined benefits of both lead to the state-of-the-art performance SR of diffusion MR brain images in terms of errors compared to ground truth. We further show that the reduced error scores produce tangible benefits in downstream tractography. In addition, the probabilistic nature of the methods naturally confers a mechanism to quantify uncertainty over the super-resolved output. We demonstrate through experiments on both healthy and pathological brains the potential utility of such an uncertainty measure in the risk assessment of the super-resolved images for subsequent clinical use.

##### Abstract (translated by Google)
在这项工作中，我们调查了卷积神经网络（CNNs）三维超分辨率不确定性建模的价值。深度学习在诸如超分辨率（SR）和图像合成等大量医学图像变换问题中显示出成功。但是，这些问题的高度不适应性导致了网络学习中不可避免的模糊性。我们建议通过每贴片异方差噪声模型来解释固有的不确定性，并通过近似贝叶斯推理以变分丢失的形式解释参数不确定性。我们表明，两者的综合好处导致扩散MR脑图像的状态的最先进的性能SR在错误方面比地面事实。我们进一步表明，下降的误差分数在下游纤维束成像中产生实际的益处。另外，方法的概率本质自然赋予一种机制来量化超分辨输出的不确定性。我们通过对健康和病理性大脑的实验来证明这样的不确定性测量在超分辨图像的风险评估中的潜在效用以用于随后的临床使用。

##### URL
[https://arxiv.org/abs/1705.00664](https://arxiv.org/abs/1705.00664)

##### PDF
[https://arxiv.org/pdf/1705.00664](https://arxiv.org/pdf/1705.00664)

