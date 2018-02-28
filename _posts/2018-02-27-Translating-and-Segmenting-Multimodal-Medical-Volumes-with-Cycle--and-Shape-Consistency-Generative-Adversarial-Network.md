---
layout: post
title: "Translating and Segmenting Multimodal Medical Volumes with Cycle- and Shape-Consistency Generative Adversarial Network"
date: 2018-02-27 00:10:13
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation CNN
author: Zizhao Zhang, Lin Yang, Yefeng Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Synthesized medical images have several important applications, e.g., as an intermedium in cross-modality image registration and as supplementary training samples to boost the generalization capability of a classifier. Especially, synthesized computed tomography (CT) data can provide X-ray attenuation map for radiation therapy planning. In this work, we propose a generic cross-modality synthesis approach with the following targets: 1) synthesizing realistic looking 3D images using unpaired training data, 2) ensuring consistent anatomical structures, which could be changed by geometric distortion in cross-modality synthesis and 3) improving volume segmentation by using synthetic data for modalities with limited training samples. We show that these goals can be achieved with an end-to-end 3D convolutional neural network (CNN) composed of mutually-beneficial generators and segmentors for image synthesis and segmentation tasks. The generators are trained with an adversarial loss, a cycle-consistency loss, and also a shape-consistency loss, which is supervised by segmentors, to reduce the geometric distortion. From the segmentation view, the segmentors are boosted by synthetic data from generators in an online manner. Generators and segmentors prompt each other alternatively in an end-to-end training fashion. With extensive experiments on a dataset including a total of 4,496 CT and magnetic resonance imaging (MRI) cardiovascular volumes, we show both tasks are beneficial to each other and coupling these two tasks results in better performance than solving them exclusively.

##### Abstract (translated by Google)
合成的医学图像具有几个重要的应用，例如作为跨模态图像配准中的媒介和作为辅助训练样本以提高分类器的泛化能力。特别是，合成计算机断层扫描（CT）数据可以为放射治疗计划提供X射线衰减图。在这项工作中，我们提出了一个通用的跨模态综合方法，其具有以下目标：1）使用不成对的训练数据合成逼真的3D图像; 2）确保一致的解剖结构，这可以通过跨模态合成中的几何失真来改变; 3）通过使用具有有限训练样本的模态的合成数据改进体积分割。我们表明，这些目标可以通过一个端到端的三维卷积神经网络（CNN）来实现，该网络由互利的发生器和分割器组成，用于图像合成和分割任务。对发生器进行对抗性损失，循环一致性损失以及由分割器监督的形状一致性损失进行训练，以减少几何失真。从分段视图中，分段器通过来自发电机的合成数据以在线方式提升。发生器和分割器以端到端的训练方式互相提示对方。通过对数据集进行广泛的实验，包括总共4496个CT和磁共振成像（MRI）心血管容量，我们显示这两个任务对彼此都有益处，并且将这两个任务结合起来获得比仅仅解决它们更好的性能。

##### URL
[https://arxiv.org/abs/1802.09655](https://arxiv.org/abs/1802.09655)

##### PDF
[https://arxiv.org/pdf/1802.09655](https://arxiv.org/pdf/1802.09655)

