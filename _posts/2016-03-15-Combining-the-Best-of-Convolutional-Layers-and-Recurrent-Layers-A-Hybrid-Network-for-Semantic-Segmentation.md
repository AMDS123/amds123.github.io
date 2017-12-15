---
layout: post
title: "Combining the Best of Convolutional Layers and Recurrent Layers: A Hybrid Network for Semantic Segmentation"
date: 2016-03-15 20:10:48
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation RNN
author: Zhicheng Yan, Hao Zhang, Yangqing Jia, Thomas Breuel, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art results of semantic segmentation are established by Fully Convolutional neural Networks (FCNs). FCNs rely on cascaded convolutional and pooling layers to gradually enlarge the receptive fields of neurons, resulting in an indirect way of modeling the distant contextual dependence. In this work, we advocate the use of spatially recurrent layers (i.e. ReNet layers) which directly capture global contexts and lead to improved feature representations. We demonstrate the effectiveness of ReNet layers by building a Naive deep ReNet (N-ReNet), which achieves competitive performance on Stanford Background dataset. Furthermore, we integrate ReNet layers with FCNs, and develop a novel Hybrid deep ReNet (H-ReNet). It enjoys a few remarkable properties, including full-image receptive fields, end-to-end training, and efficient network execution. On the PASCAL VOC 2012 benchmark, the H-ReNet improves the results of state-of-the-art approaches Piecewise, CRFasRNN and DeepParsing by 3.6%, 2.3% and 0.2%, respectively, and achieves the highest IoUs for 13 out of the 20 object classes.

##### Abstract (translated by Google)
完全卷积神经网络（FCNs）建立了语义分割的最新结果。 FCN依靠级联的卷积层和逐层累积层来逐渐扩大神经元的接受范围，从而产生一种间接的建模方式，对远处的上下文依赖进行建模。在这项工作中，我们主张使用直接捕捉全局上下文并导致改进的特征表示的空间循环层（即ReNet层）。我们通过构建一个朴素的ReNet（N-ReNet）来证明ReNet层的有效性，这在Stanford背景数据集上实现了有竞争力的表现。此外，我们将ReNet层与FCN集成在一起，并开发了一种新型混合深度ReNet（H-ReNet）。它具有一些显着的特性，包括完整的图像接受域，端到端的训练和高效的网络执行。在PASCAL VOC 2012基准测试中，H-ReNet分别将分段式，CRFasRNN和DeepParsing分别提高了3.6％，2.3％和0.2％，达到了13个中最高的IoUs 20个对象类。

##### URL
[https://arxiv.org/abs/1603.04871](https://arxiv.org/abs/1603.04871)

##### PDF
[https://arxiv.org/pdf/1603.04871](https://arxiv.org/pdf/1603.04871)

