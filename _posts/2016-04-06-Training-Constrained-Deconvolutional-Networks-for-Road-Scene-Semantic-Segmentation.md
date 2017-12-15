---
layout: post
title: "Training Constrained Deconvolutional Networks for Road Scene Semantic Segmentation"
date: 2016-04-06 09:02:50
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Segmentation CNN Semantic_Segmentation
author: German Ros, Simon Stent, Pablo F. Alcantarilla, Tomoki Watanabe
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we investigate the problem of road scene semantic segmentation using Deconvolutional Networks (DNs). Several constraints limit the practical performance of DNs in this context: firstly, the paucity of existing pixel-wise labelled training data, and secondly, the memory constraints of embedded hardware, which rule out the practical use of state-of-the-art DN architectures such as fully convolutional networks (FCN). To address the first constraint, we introduce a Multi-Domain Road Scene Semantic Segmentation (MDRS3) dataset, aggregating data from six existing densely and sparsely labelled datasets for training our models, and two existing, separate datasets for testing their generalisation performance. We show that, while MDRS3 offers a greater volume and variety of data, end-to-end training of a memory efficient DN does not yield satisfactory performance. We propose a new training strategy to overcome this, based on (i) the creation of a best-possible source network (S-Net) from the aggregated data, ignoring time and memory constraints; and (ii) the transfer of knowledge from S-Net to the memory-efficient target network (T-Net). We evaluate different techniques for S-Net creation and T-Net transferral, and demonstrate that training a constrained deconvolutional network in this manner can unlock better performance than existing training approaches. Specifically, we show that a target network can be trained to achieve improved accuracy versus an FCN despite using less than 1\% of the memory. We believe that our approach can be useful beyond automotive scenarios where labelled data is similarly scarce or fragmented and where practical constraints exist on the desired model size. We make available our network models and aggregated multi-domain dataset for reproducibility.

##### Abstract (translated by Google)
在这项工作中，我们调查使用反卷积网络（DN）道路场景语义分割的问题。在这种情况下，几种约束限制了DN的实际性能：首先，现有像素标记的训练数据的缺乏;其次，嵌入式硬件的存储器限制，这排除了实际使用最先进的DN完全卷积网络（FCN）等体系结构。为了解决第一个约束，我们引入了一个多领域道路场景语义分割（MDRS3）数据集，对六个现有的密集和稀疏标记的数据集的数据进行聚合，以训练我们的模型，以及两个现有的单独数据集来测试它们的泛化性能。我们表明，尽管MDRS3提供了更大的数据量和多样化的数据，但是对内存高效的DN进行端到端的培训并不能产生令人满意的性能。我们提出了一种新的培训策略来克服这个问题，基于（i）从汇总的数据中创建最佳可能的源网络（S-Net），忽略时间和内存的限制; （ii）将知识从S-Net转移到高效率的目标网络（T-Net）。我们评估了不同的S-Net创建和T-net传输技术，并且证明了以这种方式训练一个有约束的反卷积网络可以比现有的训练方法获得更好的性能。具体来说，我们表明，尽管使用少于1％的内存，目标网络可以被训练以实现与FCN相比提高的准确度。我们相信，我们的方法可以超越标签数据同样稀缺或分散的汽车方案，并且在所需的模型尺寸上存在实际的限制。我们提供我们的网络模型和聚合多域数据集的可重复性。

##### URL
[https://arxiv.org/abs/1604.01545](https://arxiv.org/abs/1604.01545)

##### PDF
[https://arxiv.org/pdf/1604.01545](https://arxiv.org/pdf/1604.01545)

