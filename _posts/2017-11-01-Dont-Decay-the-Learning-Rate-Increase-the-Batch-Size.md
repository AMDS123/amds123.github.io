---
layout: post
title: "Don't Decay the Learning Rate, Increase the Batch Size"
date: 2017-11-01 18:04:31
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent
author: Samuel L. Smith, Pieter-Jan Kindermans, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
It is common practice to decay the learning rate. Here we show one can usually obtain the same learning curve on both training and test sets by instead increasing the batch size during training. This procedure is successful for stochastic gradient descent (SGD), SGD with momentum, Nesterov momentum, and Adam. It reaches equivalent test accuracies after the same number of training epochs, but with fewer parameter updates, leading to greater parallelism and shorter training times. We can further reduce the number of parameter updates by increasing the learning rate $\epsilon$ and scaling the batch size $B \propto \epsilon$. Finally, one can increase the momentum coefficient $m$ and scale $B \propto 1/(1-m)$, although this tends to slightly reduce the test accuracy. Crucially, our techniques allow us to repurpose existing training schedules for large batch training with no hyper-parameter tuning. We train Inception-ResNet-V2 on ImageNet to $77\%$ validation accuracy in under 2500 parameter updates, efficiently utilizing training batches of 65536 images.

##### Abstract (translated by Google)
衰减学习率是很常见的做法。在这里，我们展示了通常可以在训练和测试集合上获得相同的学习曲线，而不是在训练期间增加批量大小。这个程序对于随机梯度下降（SGD），有动量的新元，涅斯捷罗夫动量和亚当成功。在相同数量的训练时期之后，它达到相同的测试精度，但参数更新较少，导致更大的并行性和更短的训练时间。我们可以通过提高学习率$ \ epsilon $和缩放批量大小$ B \ propto \ epsilon $来进一步减少参数更新次数。最后，可以增加动量系数$ m $和规模$ B \ propto 1 /（1-m）$，但这往往会略微降低测试精度。至关重要的是，我们的技术使我们能够重新调整现有的训练计划，实现大批量训练，无需超参数调整。在2500个参数更新下，我们将ImageNet上的Inception-ResNet-V2训练到$ 77 \％$验证精度，有效地利用训练批次的65536个图像。

##### URL
[https://arxiv.org/abs/1711.00489](https://arxiv.org/abs/1711.00489)

##### PDF
[https://arxiv.org/pdf/1711.00489](https://arxiv.org/pdf/1711.00489)

