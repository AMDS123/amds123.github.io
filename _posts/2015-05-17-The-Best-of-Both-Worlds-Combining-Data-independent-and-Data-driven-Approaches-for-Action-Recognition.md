---
layout: post
title: "The Best of Both Worlds: Combining Data-independent and Data-driven Approaches for Action Recognition"
date: 2015-05-17 17:54:38
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Classification Relation Recognition
author: Zhenzhong Lan, Dezhong Yao, Ming Lin, Shoou-I Yu, Alexander Hauptmann
mathjax: true
---

* content
{:toc}

##### Abstract
Motivated by the success of data-driven convolutional neural networks (CNNs) in object recognition on static images, researchers are working hard towards developing CNN equivalents for learning video features. However, learning video features globally has proven to be quite a challenge due to its high dimensionality, the lack of labelled data and the difficulty in processing large-scale video data. Therefore, we propose to leverage effective techniques from both data-driven and data-independent approaches to improve action recognition system. Our contribution is three-fold. First, we propose a two-stream Stacked Convolutional Independent Subspace Analysis (ConvISA) architecture to show that unsupervised learning methods can significantly boost the performance of traditional local features extracted from data-independent models. Second, we demonstrate that by learning on video volumes detected by Improved Dense Trajectory (IDT), we can seamlessly combine our novel local descriptors with hand-crafted descriptors. Thus we can utilize available feature enhancing techniques developed for hand-crafted descriptors. Finally, similar to multi-class classification framework in CNNs, we propose a training-free re-ranking technique that exploits the relationship among action classes to improve the overall performance. Our experimental results on four benchmark action recognition datasets show significantly improved performance.

##### Abstract (translated by Google)
受数据驱动的卷积神经网络（CNNs）在静态图像上的物体识别的成功推动，研究人员正在努力开发用于学习视频特征的CNN等价物。然而，由于其高维度，缺乏标签数据和处理大规模视频数据的困难，全球学习视频特征已被证明是相当大的挑战。因此，我们建议利用数据驱动和数据无关的有效技术来改进行动识别系统。我们的贡献是三重的。首先，我们提出了一个双流堆积卷积独立子空间分析（ConvISA）体系结构，以表明无监督学习方法可以显着提高从数据无关模型中提取的传统局部特征的性能。其次，我们证明通过学习改进密集轨迹（IDT）检测到的视频量，我们可以将我们新颖的局部描述符与手工描述符无缝地结合起来。因此，我们可以利用为手工描述符开发的可用特征增强技术。最后，与CNN中的多类分类框架类似，我们提出了一种无需训练的重排序技术，利用行为类之间的关系来提高整体性能。我们在四个基准动作识别数据集上的实验结果显示性能显着提高。

##### URL
[https://arxiv.org/abs/1505.04427](https://arxiv.org/abs/1505.04427)

##### PDF
[https://arxiv.org/pdf/1505.04427](https://arxiv.org/pdf/1505.04427)

