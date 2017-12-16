---
layout: post
title: "Improving automated multiple sclerosis lesion segmentation with a cascaded 3D convolutional neural network approach"
date: 2017-02-16 06:23:14
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Sergi Valverde, Mariano Cabezas, Eloy Roura, Sandra González-Villà, Deborah Pareto, Joan-Carles Vilanova, LLuís Ramió-Torrentà, Àlex Rovira, Arnau Oliver, Xavier Lladó
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel automated method for White Matter (WM) lesion segmentation of Multiple Sclerosis (MS) patient images. Our approach is based on a cascade of two 3D patch-wise convolutional neural networks (CNN). The first network is trained to be more sensitive revealing possible candidate lesion voxels while the second network is trained to reduce the number of misclassified voxels coming from the first network. This cascaded CNN architecture tends to learn well from small sets of training data, which can be very interesting in practice, given the difficulty to obtain manual label annotations and the large amount of available unlabeled Magnetic Resonance Imaging (MRI) data. We evaluate the accuracy of the proposed method on the public MS lesion segmentation challenge MICCAI2008 dataset, comparing it with respect to other state-of-the-art MS lesion segmentation tools. Furthermore, the proposed method is also evaluated on two private MS clinical datasets, where the performance of our method is also compared with different recent public available state-of-the-art MS lesion segmentation methods. At the time of writing this paper, our method is the best ranked approach on the MICCAI2008 challenge, outperforming the rest of 60 participant methods when using all the available input modalities (T1-w, T2-w and FLAIR), while still in the top-rank (3rd position) when using only T1-w and FLAIR modalities. On clinical MS data, our approach exhibits a significant increase in the accuracy segmenting of WM lesions when compared with the rest of evaluated methods, highly correlating ($r \ge 0.97$) also with the expected lesion volume.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的白质（WM）病变图像多发性硬化（MS）病变分割的自动化方法。我们的方法是基于两个3D拼片式卷积神经网络（CNN）的级联。训练第一网络以更灵敏地揭示可能的候选病变体素，同时训练第二网络以减少来自第一网络的误分类体素的数目。由于难以获得人工标签注释和大量可用的未标记的磁共振成像（MRI）数据，这种级联的CNN架构倾向于从小的训练数据集中学习，这在实践中可能是非常有趣的。我们评估所提出的方法在公共MS病灶分割挑战MICCAI2008数据集上的准确性，并将其与其他现有技术的MS病灶分割工具进行比较。此外，所提出的方法也在两个私人MS临床数据集上进行评估，其中我们的方法的性能还与不同的最近公开的现有技术的MS病灶分割方法进行比较。在撰写本文时，我们的方法是MICCAI2008挑战中排名最好的方法，在使用所有可用的输入模式（T1-w，T2-w和FLAIR）时优于60个参与方法中的其余方法，而仍处于当只使用T1-w和FLAIR模式时，排名第一（第三位）。在临床MS数据上，与其余评估方法相比，我们的方法在WM病变的精确度分割方面显示出显着增加，也与期望的病变体积高度相关（$ r \ ge 0.97 $）。

##### URL
[https://arxiv.org/abs/1702.04869](https://arxiv.org/abs/1702.04869)

##### PDF
[https://arxiv.org/pdf/1702.04869](https://arxiv.org/pdf/1702.04869)

