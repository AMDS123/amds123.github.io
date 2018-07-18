---
layout: post
title: "Dual-Path Convolutional Image-Text Embedding with Instance Loss"
date: 2018-07-17 17:38:54
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Language_Model Relation
author: Zhedong Zheng, Liang Zheng, Michael Garrett, Yi Yang, Yi-Dong Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Matching images and sentences demands a fine understanding of both modalities. In this paper, we propose a new system to discriminatively embed the image and text to a shared visual-textual space. In this field, most existing works apply the ranking loss to pull the positive image / text pairs close and push the negative pairs apart from each other. However, directly deploying the ranking loss is hard for network learning, since it starts from the two heterogeneous features to build inter-modal relationship. To address this problem, we propose the instance loss which explicitly considers the intra-modal data distribution. It is based on an unsupervised assumption that each image / text group can be viewed as a class. So the network can learn the fine granularity from every image/text group. The experiment shows that the instance loss offers better weight initialization for the ranking loss, so that more discriminative embeddings can be learned. Besides, existing works usually apply the off-the-shelf features, i.e., word2vec and fixed visual feature. So in a minor contribution, this paper constructs an end-to-end dual-path convolutional network to learn the image and text representations. End-to-end learning allows the system to directly learn from the data and fully utilize the supervision. On two generic retrieval datasets (Flickr30k and MSCOCO), experiments demonstrate that our method yields competitive accuracy compared to state-of-the-art methods. Moreover, in language based person retrieval, we improve the state of the art by a large margin. The code has been made publicly available.

##### Abstract (translated by Google)
匹配图像和句子需要很好地理解这两种形式。在本文中，我们提出了一种新的系统，可以将图像和文本有区别地嵌入到共享的视觉文本空间中。在该字段中，大多数现有作品应用排名损失来拉动正图像/文本对，并将负对彼此分开。然而，直接部署排名损失对于网络学习来说很难，因为它从两个异构特征开始构建模态间关系。为了解决这个问题，我们提出了明确考虑模内数据分布的实例丢失。它基于无人监督的假设，即每个图像/文本组都可以被视为一个类。因此，网络可以从每个图像/文本组中学习细粒度。实验表明，实例丢失为排序损失提供了更好的权重初始化，因此可以学习更多的判别嵌入。此外，现有作品通常应用现成的功能，即word2vec和固定的视觉特征。因此，在一个小的贡献中，本文构建了一个端到端的双路径卷积网络来学习图像和文本表示。端到端学习允许系统直接从数据中学习并充分利用监督。在两个通用检索数据集（Flickr30k和MSCOCO）上，实验表明，与最先进的方法相比，我们的方法可以产生竞争准确性。而且，在基于语言的人物检索中，我们大大提高了现有技术水平。该代码已公开发布。

##### URL
[http://arxiv.org/abs/1711.05535](http://arxiv.org/abs/1711.05535)

##### PDF
[http://arxiv.org/pdf/1711.05535](http://arxiv.org/pdf/1711.05535)

