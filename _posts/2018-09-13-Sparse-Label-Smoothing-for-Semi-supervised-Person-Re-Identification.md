---
layout: post
title: "Sparse Label Smoothing for Semi-supervised Person Re-Identification"
date: 2018-09-13 14:04:58
categories: arXiv_CV
tags: arXiv_CV Regularization Re-identification Sparse GAN Person_Re-identification Represenation_Learning
author: Jean-Paul Ainam, Ke Qin, Guisong Liu, Guangchun Luo
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a semi-supervised framework to address the over-smoothness problem found in current regularization methods. We carefully propose to derive a regularization method by constructing clusters of similar images. We propose Sparse Label Smoothing Regularization (SLSR) which consist of three steps. First, we train a CNN to learn discriminative patterns from labeled data. For each image, we extract the feature map from the last convolution layer and directly apply \textit{k-means} clustering algorithm on the feature. Secondly, we train a GAN model for feature representation learning and generate sample images for each cluster. Each generated sample is assigned a label using our regularization method. Thirdly, we define a new objective function and fine-tuned two baseline models ResNet and DenseNet. Extensive experiments on four large-scale datasets Market-1501, CUHK03, DukeMTMC-ReID, and VIPeR show that our regularization method significantly improves the Re-ID accuracy compared to existing semi-supervised methods. On Market-1501 dataset, for instance, rank-1 accuracy is improved from 87.29% to 89.16% for ResNet, and from 90.05% to 92.43% for DenseNet. The code is available at https://github.com/jpainam/SLS_ReID

##### Abstract (translated by Google)
在本文中，我们提出了一个半监督框架来解决当前正则化方法中出现的过平滑问题。我们小心地建议通过构建相似图像的聚类来推导正则化方法。我们提出稀疏标签平滑正则化（SLSR），它包括三个步骤。首先，我们训练CNN学习标记数据的判别模式。对于每个图像，我们从最后一个卷积层中提取特征图，并直接在特征上应用\ textit {k-means}聚类算法。其次，我们训练GAN模型进行特征表示学习，并为每个聚类生成样本图像。使用我们的正则化方法为每个生成的样本分配标签。第三，我们定义了一个新的目标函数和微调的两个基线模型ResNet和DenseNet。对四个大型数据集Market-1501，CUHK03，DukeMTMC-ReID和VIPeR进行的大量实验表明，与现有的半监督方法相比，我们的正则化方法显着提高了Re-ID精度。例如，在Market-1501数据集上，ResNet的秩-1准确度从87.29％提高到89.16％，DenseNet从90.05％提高到92.43％。该代码可在https://github.com/jpainam/SLS_ReID获得

##### URL
[http://arxiv.org/abs/1809.04976](http://arxiv.org/abs/1809.04976)

##### PDF
[http://arxiv.org/pdf/1809.04976](http://arxiv.org/pdf/1809.04976)

