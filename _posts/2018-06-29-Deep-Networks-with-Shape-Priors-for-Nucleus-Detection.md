---
layout: post
title: "Deep Networks with Shape Priors for Nucleus Detection"
date: 2018-06-29 17:54:41
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Deep_Learning Detection
author: Mohammad Tofighi, Tiantong Guo, Jairam K.P. Vanamala, Vishal Monga
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of cell nuclei in microscopic images is a challenging research topic, because of limitations in cellular image quality and diversity of nuclear morphology, i.e. varying nuclei shapes, sizes, and overlaps between multiple cell nuclei. This has been a topic of enduring interest with promising recent success shown by deep learning methods. These methods train for example convolutional neural networks (CNNs) with a training set of input images and known, labeled nuclei locations. Many of these methods are supplemented by spatial or morphological processing. We develop a new approach that we call Shape Priors with Convolutional Neural Networks (SP-CNN) to perform significantly enhanced nuclei detection. A set of canonical shapes is prepared with the help of a domain expert. Subsequently, we present a new network structure that can incorporate `expected behavior' of nucleus shapes via two components: {\em learnable} layers that perform the nucleus detection and a {\em fixed} processing part that guides the learning with prior information. Analytically, we formulate a new regularization term that is targeted at penalizing false positives while simultaneously encouraging detection inside cell nucleus boundary. Experimental results on a challenging dataset reveal that SP-CNN is competitive with or outperforms several state-of-the-art methods.

##### Abstract (translated by Google)
在微观图像中检测细胞核是一个具有挑战性的研究课题，因为细胞图像质量的限制和核形态的多样性，即不同的核形状，大小和多个细胞核之间的重叠。这是一个持久的兴趣主题，深度学习方法显示了最近的成功。这些方法训练例如卷积神经网络（CNN），其具有训练输入图像集和已知的标记核位置。许多这些方法通过空间或形态学处理来补充。我们开发了一种新方法，我们将其称为带有卷积神经网络（SP-CNN）的Shape Priors，以显着增强细胞核检测。在领域专家的帮助下准备了一组规范形状。随后，我们提出了一种新的网络结构，它可以通过两个组件结合核心形状的“预期行为”：{\ em emibleable}执行核检测的层和一个引导先前信息学习的{\ em固定}处理部分。在分析上，我们制定了一个新的正则化术语，旨在惩罚假阳性，同时鼓励在细胞核边界内进行检测。在具有挑战性的数据集上的实验结果表明SP-CNN与几种最先进的方法竞争或优于几种最先进的方法。

##### URL
[http://arxiv.org/abs/1807.03135](http://arxiv.org/abs/1807.03135)

##### PDF
[http://arxiv.org/pdf/1807.03135](http://arxiv.org/pdf/1807.03135)

