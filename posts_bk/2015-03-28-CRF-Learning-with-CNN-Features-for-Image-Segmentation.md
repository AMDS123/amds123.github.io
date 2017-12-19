---
layout: post
title: "CRF Learning with CNN Features for Image Segmentation"
date: 2015-03-28 04:05:09
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Inference
author: Fayao Liu, Guosheng Lin, Chunhua Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Conditional Random Rields (CRF) have been widely applied in image segmentations. While most studies rely on hand-crafted features, we here propose to exploit a pre-trained large convolutional neural network (CNN) to generate deep features for CRF learning. The deep CNN is trained on the ImageNet dataset and transferred to image segmentations here for constructing potentials of superpixels. Then the CRF parameters are learnt using a structured support vector machine (SSVM). To fully exploit context information in inference, we construct spatially related co-occurrence pairwise potentials and incorporate them into the energy function. This prefers labelling of object pairs that frequently co-occur in a certain spatial layout and at the same time avoids implausible labellings during the inference. Extensive experiments on binary and multi-class segmentation benchmarks demonstrate the promise of the proposed method. We thus provide new baselines for the segmentation performance on the Weizmann horse, Graz-02, MSRC-21, Stanford Background and PASCAL VOC 2011 datasets.

##### Abstract (translated by Google)
条件随机场（CRF）已被广泛应用于图像分割。尽管大多数研究依赖于手工特征，但我们在此建议利用预先训练的大卷积神经网络（CNN）来生成用于CRF学习的深层特征。深CNN在ImageNet数据集上进行训练，并转移到图像分割处以构建超像素的电位。然后使用结构化支持向量机（SSVM）学习CRF参数。为了充分利用上下文信息进行推理，我们构建空间相关的共现成对势，并将其结合到能量函数中。这更喜欢标记经常在特定空间布局中共同出现的对象对，并且同时避免在推理期间难以置信的标记。二进制和多类分割基准的大量实验证明了所提出的方法的前景。因此，我们为Weizmann马，Graz-02，MSRC-21，Stanford背景和PASCAL VOC 2011数据集的分割表现提供了新的基准。

##### URL
[https://arxiv.org/abs/1503.08263](https://arxiv.org/abs/1503.08263)

##### PDF
[https://arxiv.org/pdf/1503.08263](https://arxiv.org/pdf/1503.08263)

