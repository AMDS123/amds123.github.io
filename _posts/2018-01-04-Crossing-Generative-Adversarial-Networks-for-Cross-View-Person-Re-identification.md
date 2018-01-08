---
layout: post
title: "Crossing Generative Adversarial Networks for Cross-View Person Re-identification"
date: 2018-01-04 03:52:15
categories: arXiv_CV
tags: arXiv_CV Image_Caption Re-identification Adversarial GAN Person_Re-identification
author: Chengyuan Zhang, Lin Wu, Yang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (\textit{re-id}) refers to matching pedestrians across disjoint yet non-overlapping camera views. The most effective way to match these pedestrians undertaking significant visual variations is to seek reliably invariant features that can describe the person of interest faithfully. Most of existing methods are presented in a supervised manner to produce discriminative features by relying on labeled paired images in correspondence. However, annotating pair-wise images is prohibitively expensive in labors, and thus not practical in large-scale networked cameras. Moreover, seeking comparable representations across camera views demands a flexible model to address the complex distributions of images. In this work, we study the co-occurrence statistic patterns between pairs of images, and propose to crossing Generative Adversarial Network (Cross-GAN) for learning a joint distribution for cross-image representations in a unsupervised manner. Given a pair of person images, the proposed model consists of the variational auto-encoder to encode the pair into respective latent variables, a proposed cross-view alignment to reduce the view disparity, and an adversarial layer to seek the joint distribution of latent representations. The learned latent representations are well-aligned to reflect the co-occurrence patterns of paired images. We empirically evaluate the proposed model against challenging datasets, and our results show the importance of joint invariant features in improving matching rates of person re-id with comparison to semi/unsupervised state-of-the-arts.

##### Abstract (translated by Google)
人员重新识别（\ textit {re-id}）是指跨不相交但不重叠的摄像机视图匹配行人。匹配这些行人进行显着的视觉变化的最有效的方法是寻找可靠地描述感兴趣的人的可靠的不变特征。现有的大多数方法都是以监督的方式呈现，通过对应的标记配对图像来产生判别特征。然而，注释成对图像在劳动中昂贵，因此在大型网络摄像机中不实用。而且，在相机视图中寻找可比较的表示需要灵活的模型来解决图像的复杂分布。在这项工作中，我们研究了图像对之间的共现统计模式，并提出跨越生成对抗网络（Cross-GAN）来以无监督的方式学习交叉图像表示的联合分布。给定一对人的图像，所提出的模型由变量自编码器将该对编码成相应的潜在变量，提出的交叉视图对齐以减少视图差异，以及寻求潜在表示的联合分布的对抗层。学习到的潜在表示很好地反映了配对图像的共现模式。我们根据具有挑战性的数据集对所提出的模型进行了实证评估，并且我们的结果显示了联合不变特征在提高人员重复率匹配率方面的重要性，与半/无监督技术状态比较。

##### URL
[http://arxiv.org/abs/1801.01760](http://arxiv.org/abs/1801.01760)

##### PDF
[http://arxiv.org/pdf/1801.01760](http://arxiv.org/pdf/1801.01760)

