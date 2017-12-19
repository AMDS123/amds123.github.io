---
layout: post
title: "Analyzing Stability of Convolutional Neural Networks in the Frequency Domain"
date: 2015-11-16 08:42:10
categories: arXiv_CV
tags: arXiv_CV CNN
author: Elnaz J. Heravi, Hamed H. Aghdam, Domenec Puig
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding the internal process of ConvNets is commonly done using visualization techniques. However, these techniques do not usually provide a tool for estimating the stability of a ConvNet against noise. In this paper, we show how to analyze a ConvNet in the frequency domain using a 4-dimensional visualization technique. Using the frequency domain analysis, we show the reason that a ConvNet might be sensitive to a very low magnitude additive noise. Our experiments on a few ConvNets trained on different datasets revealed that convolution kernels of a trained ConvNet usually pass most of the frequencies and they are not able to effectively eliminate the effect of high frequencies. Our next experiments shows that a convolution kernel which has a more concentrated frequency response could be more stable. Finally, we show that fine-tuning a ConvNet using a training set augmented with noisy images can produce more stable ConvNets.

##### Abstract (translated by Google)
了解ConvNets的内部过程通常是使用可视化技术完成的。但是，这些技术通常不能提供估计ConvNet对噪声稳定性的工具。在本文中，我们展示了如何使用四维可视化技术来分析频域中的ConvNet。使用频域分析，我们显示了ConvNet可能对非常低的加性噪声​​敏感的原因。我们在几个ConvNets上对不同数据集进行训练的实验表明，经过训练的ConvNet的卷积核通常会传递大部分频率，并且不能有效地消除高频的影响。我们接下来的实验表明，具有更集中的频率响应的卷积核可能更稳定。最后，我们展示使用训练集增加噪声图像来微调ConvNet可以产生更稳定的ConvNets。

##### URL
[https://arxiv.org/abs/1511.03042](https://arxiv.org/abs/1511.03042)

##### PDF
[https://arxiv.org/pdf/1511.03042](https://arxiv.org/pdf/1511.03042)

