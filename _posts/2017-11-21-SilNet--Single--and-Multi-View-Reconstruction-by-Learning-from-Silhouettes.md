---
layout: post
title: "SilNet : Single- and Multi-View Reconstruction by Learning from Silhouettes"
date: 2017-11-21 16:33:18
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Olivia Wiles, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
The objective of this paper is 3D shape understanding from single and multiple images. To this end, we introduce a new deep-learning architecture and loss function, SilNet, that can handle multiple views in an order-agnostic manner. The architecture is fully convolutional, and for training we use a proxy task of silhouette prediction, rather than directly learning a mapping from 2D images to 3D shape as has been the target in most recent work. We demonstrate that with the SilNet architecture there is generalisation over the number of views -- for example, SilNet trained on 2 views can be used with 3 or 4 views at test-time; and performance improves with more views. We introduce two new synthetics datasets: a blobby object dataset useful for pre-training, and a challenging and realistic sculpture dataset; and demonstrate on these datasets that SilNet has indeed learnt 3D shape. Finally, we show that SilNet exceeds the state of the art on the ShapeNet benchmark dataset, and use SilNet to generate novel views of the sculpture dataset.

##### Abstract (translated by Google)
本文的目的是从单幅和多幅图像的三维形状理解。为此，我们引入了一个新的深度学习架构和损失函数，SilNet，它可以以一种与命令无关的方式处理多个视图。该架构是完全卷积的，对于训练，我们使用轮廓预测的代理任务，而不是直接学习从2D图像到3D形状的映射，这已经是最近的工作中的目标。我们证明了，与SilNet架构有一个概括的视图数量 - 例如，SilNet在2个视图上训练，可以在测试时使用3个或4个视图;性能提高了更多的意见。我们引入了两个新的合成数据集：一个对预训练有用的blobby对象数据集，以及一个具有挑战性和逼真性的雕塑数据集;并在这些数据集上展示SilNet的确已经学会了3D形状。最后，我们展示了SilNet超出了ShapeNet基准数据集的最新技术水平，并使用SilNet生成了雕塑数据集的新视图。

##### URL
[https://arxiv.org/abs/1711.07888](https://arxiv.org/abs/1711.07888)

##### PDF
[https://arxiv.org/pdf/1711.07888](https://arxiv.org/pdf/1711.07888)

