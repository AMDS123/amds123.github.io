---
layout: post
title: "DeepFirearm: Learning Discriminative Feature Representation for Fine-grained Firearm Retrieval"
date: 2018-06-08 06:45:32
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN Classification Recognition
author: Jiedong Hao, Jing Dong, Wei Wang, Tieniu Tan
mathjax: true
---

* content
{:toc}

##### Abstract
There are great demands for automatically regulating inappropriate appearance of shocking firearm images in social media or identifying firearm types in forensics. Image retrieval techniques have great potential to solve these problems. To facilitate research in this area, we introduce Firearm 14k, a large dataset consisting of over 14,000 images in 167 categories. It can be used for both fine-grained recognition and retrieval of firearm images. Recent advances in image retrieval are mainly driven by fine-tuning state-of-the-art convolutional neural networks for retrieval task. The conventional single margin contrastive loss, known for its simplicity and good performance, has been widely used. We find that it performs poorly on the Firearm 14k dataset due to: (1) Loss contributed by positive and negative image pairs is unbalanced during training process. (2) A huge domain gap exists between this dataset and ImageNet. We propose to deal with the unbalanced loss by employing a double margin contrastive loss. We tackle the domain gap issue with a two-stage training strategy, where we first fine-tune the network for classification, and then fine-tune it for retrieval. Experimental results show that our approach outperforms the conventional single margin approach by a large margin (up to 88.5% relative improvement) and even surpasses the strong triplet-loss-based approach.

##### Abstract (translated by Google)
自动调节社交媒体中令人震惊的枪支图像的不合适外观或在取证中识别枪支类型有很大的需求。图像检索技术有很大的潜力来解决这些问题。为了促进这方面的研究，我们介绍了Firearm 14k，这是一个包含167个类别中超过14,000幅图像的大型数据集。它可以用于细粒度的识别和枪械图像的检索。最近在图像检索方面的进展主要是通过对用于检索任务的现有技术卷积神经网络进行微调来实现的。传统的单边保证金对比损失以其简单性和良好性能而闻名，已被广泛使用。我们发现它在火器14k数据集上表现不佳，原因如下：（1）在训练过程中，正负图像对造成的损失不平衡。 （2）这个数据集和ImageNet之间存在巨大的领域差距。我们建议通过采用双倍保证金对比损失来应对不平衡损失。我们采用两阶段培训策略处理领域差距问题，我们首先对网络进行分类优化，然后对其进行微调以供检索。实验结果表明，我们的方法大幅优于常规单一利润率方法（高达88.5％的相对改进），甚至超过强大的基于三重损失的方法。

##### URL
[http://arxiv.org/abs/1806.02984](http://arxiv.org/abs/1806.02984)

##### PDF
[http://arxiv.org/pdf/1806.02984](http://arxiv.org/pdf/1806.02984)

