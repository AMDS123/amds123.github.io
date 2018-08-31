---
layout: post
title: "Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks"
date: 2018-08-30 06:48:43
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
图像到图像转换是一类视觉和图形问题，其目标是使用对齐图像对的训练集来学习输入图像和输出图像之间的映射。但是，对于许多任务，将无法使用配对的培训数据。我们提出了一种方法，用于学习在没有配对示例的情况下将图像从源域$ X $转换为目标域$ Y $。我们的目标是学习映射$ G：X \ rightarrow Y $，这样来自$ G（X）$的图像分布与使用对抗性损失的分配$ Y $无法区分。因为这种映射严重受限，我们将它与逆映射$ F：Y \ rightarrow X $耦合并引入循环一致性损失以推动$ F（G（X））\大约X $（反之亦然）。定性结果显示在几个不存在配对训练数据的任务中，包括采集样式转移，物体变形，季节转移，照片增强等。对几种先前方法的定量比较证明了我们方法的优越性。

##### URL
[http://arxiv.org/abs/1703.10593](http://arxiv.org/abs/1703.10593)

##### PDF
[http://arxiv.org/pdf/1703.10593](http://arxiv.org/pdf/1703.10593)

