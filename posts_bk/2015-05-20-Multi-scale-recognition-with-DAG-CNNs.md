---
layout: post
title: "Multi-scale recognition with DAG-CNNs"
date: 2015-05-20 02:52:07
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Recognition
author: Songfan Yang, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
We explore multi-scale convolutional neural nets (CNNs) for image classification. Contemporary approaches extract features from a single output layer. By extracting features from multiple layers, one can simultaneously reason about high, mid, and low-level features during classification. The resulting multi-scale architecture can itself be seen as a feed-forward model that is structured as a directed acyclic graph (DAG-CNNs). We use DAG-CNNs to learn a set of multiscale features that can be effectively shared between coarse and fine-grained classification tasks. While fine-tuning such models helps performance, we show that even "off-the-self" multiscale features perform quite well. We present extensive analysis and demonstrate state-of-the-art classification performance on three standard scene benchmarks (SUN397, MIT67, and Scene15). In terms of the heavily benchmarked MIT67 and Scene15 datasets, our results reduce the lowest previously-reported error by 23.9% and 9.5%, respectively.

##### Abstract (translated by Google)
我们探索多尺度卷积神经网络（CNNs）的图像分类。当前的方法从单个输出层提取特征。通过从多个层次提取特征，可以在分类过程中同时推理高，中，低等特征。由此产生的多尺度架构本身可以被看作是一个前馈模型，它被构造成一个有向无环图（DAG-CNNs）。我们使用DAG-CNN学习一组可以在粗粒度和细粒度分类任务之间有效共享的多尺度特征。虽然微调这些模型有助于提高性能，但我们还是发现即使是“非自我”多尺度特性也表现得相当好。我们在三个标准场景基准（SUN397，MIT67和Scene15）上展示了广泛的分析并展示了最先进的分类性能。就严格基准的MIT67和Scene15数据集而言，我们的结果将先前报告的最低误差分别降低了23.9％和9.5％。

##### URL
[https://arxiv.org/abs/1505.05232](https://arxiv.org/abs/1505.05232)

##### PDF
[https://arxiv.org/pdf/1505.05232](https://arxiv.org/pdf/1505.05232)

