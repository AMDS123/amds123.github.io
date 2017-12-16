---
layout: post
title: "Deep TEN: Texture Encoding Network"
date: 2016-12-08 21:27:31
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Hang Zhang, Jia Xue, Kristin Dana
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a Deep Texture Encoding Network (Deep-TEN) with a novel Encoding Layer integrated on top of convolutional layers, which ports the entire dictionary learning and encoding pipeline into a single model. Current methods build from distinct components, using standard encoders with separate off-the-shelf features such as SIFT descriptors or pre-trained CNN features for material recognition. Our new approach provides an end-to-end learning framework, where the inherent visual vocabularies are learned directly from the loss function. The features, dictionaries and the encoding representation for the classifier are all learned simultaneously. The representation is orderless and therefore is particularly useful for material and texture recognition. The Encoding Layer generalizes robust residual encoders such as VLAD and Fisher Vectors, and has the property of discarding domain specific information which makes the learned convolutional features easier to transfer. Additionally, joint training using multiple datasets of varied sizes and class labels is supported resulting in increased recognition performance. The experimental results show superior performance as compared to state-of-the-art methods using gold-standard databases such as MINC-2500, Flickr Material Database, KTH-TIPS-2b, and two recent databases 4D-Light-Field-Material and GTOS. The source code for the complete system are publicly available.

##### Abstract (translated by Google)
我们提出了一个集成在卷积层之上的新型编码层的深度纹理编码网络（Deep-TEN），它将整个字典学习和编码管道移植到单一模型中。目前的方法由不同的组件构建，使用标准的编码器，具有单独的现成特征，例如SIFT描述符或用于材料识别的预先训练的CNN特征。我们的新方法提供了一个端到端的学习框架，其中固有的视觉词汇直接从损失函数中学习。分类器的特征，字典和编码表示都是同时学习的。该表示是无序的，因此对材料和纹理识别特别有用。编码层对鲁棒残差编码器（如VLAD和Fisher矢量）进行了推广，具有丢弃特定领域信息的特性，使学习到的卷积特征更容易传输。此外，还支持使用多种尺寸和类别标签的多个数据集进行联合训练，从而提高识别性能。与使用金标准数据库如MINC-2500，Flickr材料数据库，KTH-TIPS-2b和两个最新数据库4D-Light-Field-Material的现有技术相比，实验结果表现出优越的性能， GTOS。整个系统的源代码是公开的。

##### URL
[https://arxiv.org/abs/1612.02844](https://arxiv.org/abs/1612.02844)

##### PDF
[https://arxiv.org/pdf/1612.02844](https://arxiv.org/pdf/1612.02844)

