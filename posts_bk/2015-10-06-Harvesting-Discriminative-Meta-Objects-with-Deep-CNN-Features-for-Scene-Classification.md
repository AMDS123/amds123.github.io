---
layout: post
title: "Harvesting Discriminative Meta Objects with Deep CNN Features for Scene Classification"
date: 2015-10-06 05:59:11
categories: arXiv_CV
tags: arXiv_CV Image_Caption Weakly_Supervised Classification
author: Ruobing Wu, Baoyuan Wang, Wenping Wang, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work on scene classification still makes use of generic CNN features in a rudimentary manner. In this ICCV 2015 paper, we present a novel pipeline built upon deep CNN features to harvest discriminative visual objects and parts for scene classification. We first use a region proposal technique to generate a set of high-quality patches potentially containing objects, and apply a pre-trained CNN to extract generic deep features from these patches. Then we perform both unsupervised and weakly supervised learning to screen these patches and discover discriminative ones representing category-specific objects and parts. We further apply discriminative clustering enhanced with local CNN fine-tuning to aggregate similar objects and parts into groups, called meta objects. A scene image representation is constructed by pooling the feature response maps of all the learned meta objects at multiple spatial scales. We have confirmed that the scene image representation obtained using this new pipeline is capable of delivering state-of-the-art performance on two popular scene benchmark datasets, MIT Indoor 67~\cite{MITIndoor67} and Sun397~\cite{Sun397}

##### Abstract (translated by Google)
最近的场景分类工作仍然以基本的方式使用通用的CNN特征。在这个ICCV 2015年的论文中，我们提出了一个基于CNN深度特征的新型管道，用于收集区分视觉对象和场景分类的部分。我们首先使用区域提议技术来生成一组可能包含对象的高质量补丁，并应用预先训练的CNN从这些补丁中提取通用深度特征。然后，我们进行无监督和弱监督学习，以筛选这些补丁，发现代表特定类别的对象和部分的区别性的。我们进一步应用通过本地CNN微调增强的区分聚类来将相似的对象和部分聚合成组，称为元对象。场景图像表示是通过将多个空间尺度上的所有学习元对象的特征响应图汇集起来而构建的。我们已经证实，使用这个新的管道获得的场景图像表示能够在两个流行的场景基准数据集MIT室内67〜

##### URL
[https://arxiv.org/abs/1510.01440](https://arxiv.org/abs/1510.01440)

##### PDF
[https://arxiv.org/pdf/1510.01440](https://arxiv.org/pdf/1510.01440)

