---
layout: post
title: "Capturing Localized Image Artifacts through a CNN-based Hyper-image Representation"
date: 2017-11-14 04:32:16
categories: arXiv_CV
tags: arXiv_CV Image_Caption Detection Relation
author: Parag Shridhar Chandakkar, Baoxin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Training deep CNNs to capture localized image artifacts on a relatively small dataset is a challenging task. With enough images at hand, one can hope that a deep CNN characterizes localized artifacts over the entire data and their effect on the output. However, on smaller datasets, such deep CNNs may overfit and shallow ones find it hard to capture local artifacts. Thus some image-based small-data applications first train their framework on a collection of patches (instead of the entire image) to better learn the representation of localized artifacts. Then the output is obtained by averaging the patch-level results. Such an approach ignores the spatial correlation among patches and how various patch locations affect the output. It also fails in cases where few patches mainly contribute to the image label. To combat these scenarios, we develop the notion of hyper-image representations. Our CNN has two stages. The first stage is trained on patches. The second stage utilizes the last layer representation developed in the first stage to form a hyper-image, which is used to train the second stage. We show that this approach is able to develop a better mapping between the image and its output. We analyze additional properties of our approach and show its effectiveness on one synthetic and two real-world vision tasks - no-reference image quality estimation and image tampering detection - by its performance improvement over existing strong baselines.

##### Abstract (translated by Google)
训练深度CNN以捕获相对较小的数据集中的局部图像伪影是一项具有挑战性的任务。如果手头有足够的图像，人们可以希望深度CNN能够描述整个数据上的局部伪像及其对输出的影响。然而，在较小的数据集上，如此深的CNN可能会过度适应，而浅层的CNN则很难捕捉到本地的文物。因此，一些基于图像的小数据应用程序首先在一系列补丁（而不是整个图像）上训练框架，以更好地学习本地化文物的表示。然后通过平均补丁级结果来获得输出。这种方法忽略了斑块之间的空间相关性以及各个斑块位置如何影响输出。在很少的补丁主要影响图像标签的情况下也失败。为了对付这些情况，我们开发了超图像表示的概念。我们的CNN有两个阶段。第一阶段是对补丁进行培训。第二阶段利用第一阶段开发的最后一层表示形成超图像，用于训练第二阶段。我们证明这种方法能够在图像和输出之间形成更好的映射。我们分析了我们方法的附加属性，并通过在现有强基线上的性能改进，在一个合成和两个真实世界的视觉任务（无参考图像质量估计和图像篡改检测）上显示其有效性。

##### URL
[https://arxiv.org/abs/1711.04945](https://arxiv.org/abs/1711.04945)

##### PDF
[https://arxiv.org/pdf/1711.04945](https://arxiv.org/pdf/1711.04945)

