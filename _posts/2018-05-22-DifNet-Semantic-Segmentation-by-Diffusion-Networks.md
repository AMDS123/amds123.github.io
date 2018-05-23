---
layout: post
title: "DifNet: Semantic Segmentation by Diffusion Networks"
date: 2018-05-22 02:38:00
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Prediction Detection
author: Peng Jiang, Fanglin Gu, Changhe Tu, Baoquan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNNs) have recently shown state of the art performance on semantic segmentation tasks, however they still suffer from problems of poor boundary localization and spatial fragmented predictions. The difficulties lie in the requirement of making dense predictions from a long path model all at once, since details are hard to keep when data goes through deeper layers. Instead, in this work, we decompose this difficult task into two relative simple sub-tasks: seed detection which is required to predict initial predictions without need of wholeness and preciseness, and similarity estimation which measures the possibility of any two nodes belong to the same class without need of knowing which class they are. We use one branch for one sub-task each, and apply a cascade of random walks base on hierarchical semantics to approximate a complex diffusion process which propagates seed information to the whole image according to the estimated similarities. The proposed DifNet consistently produces improvements over the baseline models with the same depth and with equivalent number of parameters, and also achieves promising performance on Pascal VOC and Pascal Context dataset. Our DifNet is trained end-to-end without complex loss functions.

##### Abstract (translated by Google)
最近，深度神经网络（DNN）展示了语义分割任务的最新性能，然而他们仍然遭遇不良边界定位和空间分散预测的问题。困难在于需要一次从长路径模型进行密集预测，因为当数据经过更深层次时，细节很难保持。相反，在这项工作中，我们将这个困难的任务分解为两个相对简单的子任务：预测初始预测所需的种子检测，而不需要完整性和准确性，以及测量任何两个节点属于相同的可能性的相似性估计而不需要知道他们是哪一类。我们对每个子任务分别使用一个分支，并且基于分层语义应用级联的随机漫步来近似复杂的扩散过程，根据估计的相似性将种子信息传播到整个图像。所提出的DifNet一直在基线模型上产生相同深度和相同数量参数的改进，并且在Pascal VOC和Pascal上下文数据集上也取得了令人满意的性能。我们的DifNet是端对端培训，没有复杂的损失功能。

##### URL
[http://arxiv.org/abs/1805.08015](http://arxiv.org/abs/1805.08015)

##### PDF
[http://arxiv.org/pdf/1805.08015](http://arxiv.org/pdf/1805.08015)

