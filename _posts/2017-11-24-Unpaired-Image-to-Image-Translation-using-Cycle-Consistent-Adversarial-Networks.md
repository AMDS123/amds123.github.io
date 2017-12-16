---
layout: post
title: "Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks"
date: 2017-11-24 01:37:05
categories: arXiv_CV
tags: arXiv_CV Adversarial Style_Transfer Quantitative
author: Jun-Yan Zhu, Taesung Park, Phillip Isola, Alexei A. Efros
mathjax: true
---

* content
{:toc}

##### Abstract
Image-to-image translation is a class of vision and graphics problems where the goal is to learn the mapping between an input image and an output image using a training set of aligned image pairs. However, for many tasks, paired training data will not be available. We present an approach for learning to translate an image from a source domain $X$ to a target domain $Y$ in the absence of paired examples. Our goal is to learn a mapping $G: X \rightarrow Y$ such that the distribution of images from $G(X)$ is indistinguishable from the distribution $Y$ using an adversarial loss. Because this mapping is highly under-constrained, we couple it with an inverse mapping $F: Y \rightarrow X$ and introduce a cycle consistency loss to push $F(G(X)) \approx X$ (and vice versa). Qualitative results are presented on several tasks where paired training data does not exist, including collection style transfer, object transfiguration, season transfer, photo enhancement, etc. Quantitative comparisons against several prior methods demonstrate the superiority of our approach.

##### Abstract (translated by Google)
图像到图像的转换是一类视觉和图形问题，其目标是使用对齐的图像对的训练集来学习输入图像和输出图像之间的映射。但是，对于许多任务，配对的培训数据将不可用。我们提出了一种方法，用于在缺少配对示例的情况下将图像从源域$ X $转换为目标域$ Y $。我们的目标是学习映射$ G：X \ rightarrow Y $，使$ G（X）$中的图像分布与使用敌对损失的分布$ Y $无法区分。因为这个映射的约束非常不足，所以我们将它和一个逆映射$ F：Y \ rightarrow X $耦合起来，并引入一个循环一致性损失来推导$ F（G（X））\ approx X $（反之亦然）。定性结果是在不存在配对训练数据（包括收集风格转移，对象变形，季节转移，照片增强等）的若干任务中呈现的。针对若干先前方法的定量比较证明了我们的方法的优越性。

##### URL
[https://arxiv.org/abs/1703.10593](https://arxiv.org/abs/1703.10593)

##### PDF
[https://arxiv.org/pdf/1703.10593](https://arxiv.org/pdf/1703.10593)

