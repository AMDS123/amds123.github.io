---
layout: post
title: "Deep Matching Prior Network: Toward Tighter Multi-oriented Text Detection"
date: 2017-03-04 09:40:41
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Yuliang Liu, Lianwen Jin
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting incidental scene text is a challenging task because of multi-orientation, perspective distortion, and variation of text size, color and scale. Retrospective research has only focused on using rectangular bounding box or horizontal sliding window to localize text, which may result in redundant background noise, unnecessary overlap or even information loss. To address these issues, we propose a new Convolutional Neural Networks (CNNs) based method, named Deep Matching Prior Network (DMPNet), to detect text with tighter quadrangle. First, we use quadrilateral sliding windows in several specific intermediate convolutional layers to roughly recall the text with higher overlapping area and then a shared Monte-Carlo method is proposed for fast and accurate computing of the polygonal areas. After that, we designed a sequential protocol for relative regression which can exactly predict text with compact quadrangle. Moreover, a auxiliary smooth Ln loss is also proposed for further regressing the position of text, which has better overall performance than L2 loss and smooth L1 loss in terms of robustness and stability. The effectiveness of our approach is evaluated on a public word-level, multi-oriented scene text database, ICDAR 2015 Robust Reading Competition Challenge 4 "Incidental scene text localization". The performance of our method is evaluated by using F-measure and found to be 70.64%, outperforming the existing state-of-the-art method with F-measure 63.76%.

##### Abstract (translated by Google)
由于多方位，透视失真，文字大小，颜色和尺度的变化，检测附带的场景文本是一项具有挑战性的任务。回顾性研究只侧重于使用矩形边界框或水平滑动窗口对文本进行定位，这可能会导致背景噪声过多，不必要的重叠甚至信息丢失。为了解决这些问题，我们提出了一种新的基于卷积神经网络（CNNs）的方法，称为深匹配先验网络（DMPNet），以检测更紧密的四边形文本。首先，我们在几个特定的​​中间卷积图层中使用四边形滑动窗口来粗略地回想到具有较高重叠区域的文本，然后提出共享的蒙特卡罗（Monte-Carlo）方法来快速而准确地计算多边形区域。之后，我们设计了一个相对回归的顺序协议，可以准确地预测紧凑四边形文本。此外，还提出辅助平滑Ln损失进一步回归文本的位置，在稳健性和稳定性方面，整体性能优于L2损失和平滑的L1损失。我们的方法的有效性是在一个公开的字级，多导向的场景文本数据库，ICDAR 2015年健壮阅读竞赛挑战赛4“附带场景文本本地化”上评估的。我们的方法的性能通过使用F-measure来评估，发现为70.64％，优于现有的最新方法，F-measure为63.76％。

##### URL
[https://arxiv.org/abs/1703.01425](https://arxiv.org/abs/1703.01425)

##### PDF
[https://arxiv.org/pdf/1703.01425](https://arxiv.org/pdf/1703.01425)

