---
layout: post
title: "Stable and Controllable Neural Texture Synthesis and Style Transfer Using Histogram Losses"
date: 2017-02-01 23:30:20
categories: arXiv_CV
tags: arXiv_CV Style_Transfer CNN Optimization
author: Eric Risser, Pierre Wilmot, Connelly Barnes
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, methods have been proposed that perform texture synthesis and style transfer by using convolutional neural networks (e.g. Gatys et al. [2015,2016]). These methods are exciting because they can in some cases create results with state-of-the-art quality. However, in this paper, we show these methods also have limitations in texture quality, stability, requisite parameter tuning, and lack of user controls. This paper presents a multiscale synthesis pipeline based on convolutional neural networks that ameliorates these issues. We first give a mathematical explanation of the source of instabilities in many previous approaches. We then improve these instabilities by using histogram losses to synthesize textures that better statistically match the exemplar. We also show how to integrate localized style losses in our multiscale framework. These losses can improve the quality of large features, improve the separation of content and style, and offer artistic controls such as paint by numbers. We demonstrate that our approach offers improved quality, convergence in fewer iterations, and more stability over the optimization.

##### Abstract (translated by Google)
最近，已经提出了通过使用卷积神经网络执行纹理合成和样式转移的方法（例如，Gatys等人[2015,2016]）。这些方法令人兴奋，因为它们在某些情况下可以创造出具有最先进质量的结果。然而，在本文中，我们展示了这些方法在纹理质量，稳定性，必要的参数调整以及缺少用户控制方面也有局限性。本文提出了一个基于卷积神经网络的多尺度综合管道，改善了这些问题。我们首先给出了许多以前的方法中的不稳定性来源的数学解释。然后，我们通过使用直方图损失来合成更好的统计匹配的纹理来改善这些不稳定性。我们还展示了如何在我们的多尺度框架中集成本地化风格的损失。这些损失可以提高大特征的质量，改善内容和风格的分离，并提供数字绘画的艺术控制。我们证明了我们的方法提供了改进的质量，更少的迭代收敛以及更多的优化稳定性。

##### URL
[https://arxiv.org/abs/1701.08893](https://arxiv.org/abs/1701.08893)

##### PDF
[https://arxiv.org/pdf/1701.08893](https://arxiv.org/pdf/1701.08893)

