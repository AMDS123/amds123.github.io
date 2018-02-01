---
layout: post
title: "Recovering from Random Pruning: On the Plasticity of Deep Convolutional Neural Networks"
date: 2018-01-31 13:40:47
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Image_Classification Classification Detection
author: Deepak Mittal, Shweta Bhardwaj, Mitesh M. Khapra, Balaraman Ravindran
mathjax: true
---

* content
{:toc}

##### Abstract
Recently there has been a lot of work on pruning filters from deep convolutional neural networks (CNNs) with the intention of reducing computations. The key idea is to rank the filters based on a certain criterion (say, $l_1$-norm, average percentage of zeros, etc) and retain only the top ranked filters. Once the low scoring filters are pruned away the remainder of the network is fine tuned and is shown to give performance comparable to the original unpruned network. In this work, we report experiments which suggest that the comparable performance of the pruned network is not due to the specific criterion chosen but due to the inherent plasticity of deep neural networks which allows them to recover from the loss of pruned filters once the rest of the filters are fine-tuned. Specifically, we show counter-intuitive results wherein by randomly pruning 25-50\% filters from deep CNNs we are able to obtain the same performance as obtained by using state of the art pruning methods. We empirically validate our claims by doing an exhaustive evaluation with VGG-16 and ResNet-50. Further, we also evaluate a real world scenario where a CNN trained on all 1000 ImageNet classes needs to be tested on only a small set of classes at test time (say, only animals). We create a new benchmark dataset from ImageNet to evaluate such class specific pruning and show that even here a random pruning strategy gives close to state of the art performance. Lastly, unlike existing approaches which mainly focus on the task of image classification, in this work we also report results on object detection. We show that using a simple random pruning strategy we can achieve significant speed up in object detection (74$\%$ improvement in fps) while retaining the same accuracy as that of the original Faster RCNN model.

##### Abstract (translated by Google)
最近，在深度卷积神经网络（CNN）修剪滤波器方面做了大量的工作，目的是减少计算量。关键的想法是根据一定的标准（例如，$ l_1 $ -norm，零的平均百分比等）对过滤器进行排序，并仅保留排名靠前的过滤器。一旦低分的滤波器被修剪掉，网络的其余部分就会被微调，并显示出与原来的未修剪网络相当的性能。在这项工作中，我们报告的实验表明，修剪网络的可比性能不是由于选择了特定的标准，而是由于深层神经网络的固有可塑性，这使得它们能够从修剪过滤器的损失中恢复，过滤器是微调的。具体而言，我们显示反直觉的结果，其中通过从深CNN中随机剪除25-50％的滤波器，我们能够获得与使用现有技术的修剪方法所获得的性能相同的性能。我们用VGG-16和ResNet-50做了详尽的评估，以验证我们的说法。此外，我们还评估了一个真实世界的场景，在这个场景中，在所有1000个ImageNet类上训练的CNN需要在测试时间仅对一小部分类进行测试（比如只有动物）。我们从ImageNet创建了一个新的基准数据集来评估这样的类特定修剪，并且表明即使在这里，随机修剪策略也能提供接近最先进的性能。最后，与现有的主要关注图像分类任务的方法不同，本文还介绍了目标检测的结果。我们证明，使用简单的随机修剪策略，我们可以在保持与原始更快的RCNN模型相同的精度的同时，在对象检测（fps的74 $ \％$改进）中实现显着的加速。

##### URL
[http://arxiv.org/abs/1801.10447](http://arxiv.org/abs/1801.10447)

##### PDF
[http://arxiv.org/pdf/1801.10447](http://arxiv.org/pdf/1801.10447)

