---
layout: post
title: "Linear Disentangled Representation Learning for Facial Actions"
date: 2017-01-11 16:34:29
categories: arXiv_CV
tags: arXiv_CV Sparse GAN Face Represenation_Learning Classification Recognition
author: Xiang Xiang, Trac D. Tran
mathjax: true
---

* content
{:toc}

##### Abstract
Limited annotated data available for the recognition of facial expression and action units embarrasses the training of deep networks, which can learn disentangled invariant features. However, a linear model with just several parameters normally is not demanding in terms of training data. In this paper, we propose an elegant linear model to untangle confounding factors in challenging realistic multichannel signals such as 2D face videos. The simple yet powerful model does not rely on huge training data and is natural for recognizing facial actions without explicitly disentangling the identity. Base on well-understood intuitive linear models such as Sparse Representation based Classification (SRC), previous attempts require a prepossessing of explicit decoupling which is practically inexact. Instead, we exploit the low-rank property across frames to subtract the underlying neutral faces which are modeled jointly with sparse representation on the action components with group sparsity enforced. On the extended Cohn-Kanade dataset (CK+), our one-shot automatic method on raw face videos performs as competitive as SRC applied on manually prepared action components and performs even better than SRC in terms of true positive rate. We apply the model to the even more challenging task of facial action unit recognition, verified on the MPI Face Video Database (MPI-VDB) achieving a decent performance. All the programs and data have been made publicly available.

##### Abstract (translated by Google)
有限的注释数据可用于面部表情和动作单元的识别，使深度网络的训练感到困惑，这可以学习解缠不变的特征。但是，对于训练数据，通常只有几个参数的线性模型是不需要的。在本文中，我们提出了一个优雅的线性模型来解决混淆因素，挑战逼真的多通道信号，如2D人脸视频。简单而强大的模型不依赖于大量的训练数据，而且在识别面部动作的时候很自然，而不需要明确地解开身份。基于众所周知的直观线性模型，如基于稀疏表示的分类（SRC），以前的尝试需要预先明确的解耦，这实际上是不精确的。相反，我们利用跨帧的低秩属性减去潜在的中立面，这些中性面是用稀疏表示对稀疏表示进行稀疏表示的。在扩展的Cohn-Kanade数据集（CK +）上，我们的单面自动方法在原始视频视频上的表现与SRC在手动准备的动作成分上的表现一样具有竞争力，并且在真正的正面率方面表现比SRC更好。我们将该模型应用于面部动作单元识别这一更具挑战性的任务，通过MPI人脸视频数据库（MPI-VDB）验证，获得了不俗的表现。所有的程序和数据已经公开。

##### URL
[https://arxiv.org/abs/1701.03102](https://arxiv.org/abs/1701.03102)

##### PDF
[https://arxiv.org/pdf/1701.03102](https://arxiv.org/pdf/1701.03102)

