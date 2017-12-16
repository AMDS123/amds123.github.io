---
layout: post
title: "Co-localization with Category-Consistent CNN Features and Geodesic Distance Propagation"
date: 2017-04-03 17:09:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Detection
author: Hieu Le, Chen-Ping Yu, Gregory Zelinsky, Dimitris Samaras
mathjax: true
---

* content
{:toc}

##### Abstract
Co-localization is the problem of localizing objects of the same class using only the set of images that contain them. This is a challenging task because the object detector must be built without negative examples that can lead to more informative supervision signals. The main idea of our method is to cluster the feature space of a generically pre-trained CNN, to find a set of CNN features that are consistently and highly activated for an object category, which we call category-consistent CNN features. Then, we propagate their combined activation map using superpixel geodesic distances for co-localization. In our first set of experiments, we show that the proposed method achieves state-of-the-art performance on three related benchmarks: PASCAL 2007, PASCAL-2012, and the Object Discovery dataset. We also show that our method is able to detect and localize truly unseen categories, on six held-out ImageNet categories with accuracy that is significantly higher than previous state-of-the-art. Our intuitive approach achieves this success without any region proposals or object detectors, and can be based on a CNN that was pre-trained purely on image classification tasks without further fine-tuning.

##### Abstract (translated by Google)
共同定位是仅使用包含它们的一组图像来定位同一类的对象的问题。这是一个具有挑战性的任务，因为物体检测器必须建立在没有负面的例子，可以导致更多的信息监督信号。我们的方法的主要思想是对一般预先训练的CNN的特征空间进行聚类，以找到一组CNN特征，这些特征对于一个对象类别来说是一致的和高度激活的，我们称之为类别一致的CNN特征。然后，我们传播他们的联合激活地图使用超像素测地距离协同定位。在我们的第一组实验中，我们证明了所提出的方法在三个相关的基准测试中达到了最先进的性能：PASCAL 2007，PASCAL-2012和Object Discovery数据集。我们还表明，我们的方法能够检测和本地化真正看不见的类别，在六个坚持的ImageNet类别上，其准确度明显高于以前的最新水平。我们直观的方法在没有任何区域建议或物体检测器的情况下取得了这一成功，并且可以基于纯粹基于图像分类任务的预先训练的CNN而无需进一步微调。

##### URL
[https://arxiv.org/abs/1612.03236](https://arxiv.org/abs/1612.03236)

##### PDF
[https://arxiv.org/pdf/1612.03236](https://arxiv.org/pdf/1612.03236)

