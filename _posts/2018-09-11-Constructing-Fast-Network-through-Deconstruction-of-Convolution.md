---
layout: post
title: "Constructing Fast Network through Deconstruction of Convolution"
date: 2018-09-11 12:32:20
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yunho Jeon, Junmo Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have achieved great success in various vision tasks; however, they incur heavy resource costs. By using deeper and wider networks, network accuracy can be improved rapidly. However, in an environment with limited resources (e.g., mobile applications), heavy networks may not be usable. This study shows that naive convolution can be deconstructed into a shift operation and pointwise convolution. To cope with various convolutions, we propose a new shift operation called active shift layer (ASL) that formulates the amount of shift as a learnable function with shift parameters. This new layer can be optimized end-to-end through backpropagation and it can provide optimal shift values. Finally, we apply this layer to a light and fast network that surpasses existing state-of-the-art networks.

##### Abstract (translated by Google)
卷积神经网络在各种视觉任务中取得了巨大成功;但是，它们会产生沉重的资源成本。通过使用更深更广的网络，可以快速提高网络精度。然而，在资源有限的环境（例如，移动应用程序）中，重型网络可能不可用。这项研究表明，天真卷积可以解构为移位操作和逐点卷积。为了应对各种卷积，我们提出了一种新的换档操作，称为主动换档层（ASL），它将换档量表示为具有换档参数的可学习功能。这个新层可以通过反向传播进行端到端优化，并且可以提供最佳的移位值。最后，我们将这一层应用于一个超越现有最先进网络的轻快网络。

##### URL
[http://arxiv.org/abs/1806.07370](http://arxiv.org/abs/1806.07370)

##### PDF
[http://arxiv.org/pdf/1806.07370](http://arxiv.org/pdf/1806.07370)

