---
layout: post
title: "Convolutional Neural Networks for Histopathology Image Classification: Training vs. Using Pre-Trained Networks"
date: 2017-10-11 00:02:53
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Transfer_Learning Classification
author: Brady Kieffer, Morteza Babaie, Shivam Kalra, H.R.Tizhoosh
mathjax: true
---

* content
{:toc}

##### Abstract
We explore the problem of classification within a medical image data-set based on a feature vector extracted from the deepest layer of pre-trained Convolution Neural Networks. We have used feature vectors from several pre-trained structures, including networks with/without transfer learning to evaluate the performance of pre-trained deep features versus CNNs which have been trained by that specific dataset as well as the impact of transfer learning with a small number of samples. All experiments are done on Kimia Path24 dataset which consists of 27,055 histopathology training patches in 24 tissue texture classes along with 1,325 test patches for evaluation. The result shows that pre-trained networks are quite competitive against training from scratch. As well, fine-tuning does not seem to add any tangible improvement for VGG16 to justify additional training while we observed considerable improvement in retrieval and classification accuracy when we fine-tuned the Inception structure.

##### Abstract (translated by Google)
我们根据从最深层的预先训练的卷积神经网络提取的特征向量来探索医学图像数据集内的分类问题。我们已经使用了来自几个预先训练的结构的特征向量，包括有/无传输学习的网络来评估预先训练的深度特征相对于由该特定数据集训练的CNN的性能以及小的传输学习的影响样本数量。所有的实验都在Kimia Path24数据集上完成，该数据集由24个组织纹理类中的27,055个组织病理学训练补丁以及1,325个评估补丁组成。结果表明，预先训练的网络对于从零开始的培训是非常有竞争力的。同样，微调似乎并没有为VGG16增加任何实质性的改进来证明额外的训练，而当我们在初始结构上进行微调时，我们观察到检索和分类准确性的显着提高。

##### URL
[https://arxiv.org/abs/1710.05726](https://arxiv.org/abs/1710.05726)

##### PDF
[https://arxiv.org/pdf/1710.05726](https://arxiv.org/pdf/1710.05726)

