---
layout: post
title: "A Compact DNN: Approaching GoogLeNet-Level Accuracy of Classification and Domain Adaptation"
date: 2017-04-03 05:17:42
categories: arXiv_CV
tags: arXiv_CV Attention Image_Classification Classification Prediction
author: Chunpeng Wu, Wei Wen, Tariq Afzal, Yongmei Zhang, Yiran Chen, Hai Li
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, DNN model compression based on network architecture design, e.g., SqueezeNet, attracted a lot attention. No accuracy drop on image classification is observed on these extremely compact networks, compared to well-known models. An emerging question, however, is whether these model compression techniques hurt DNN's learning ability other than classifying images on a single dataset. Our preliminary experiment shows that these compression methods could degrade domain adaptation (DA) ability, though the classification performance is preserved. Therefore, we propose a new compact network architecture and unsupervised DA method in this paper. The DNN is built on a new basic module Conv-M which provides more diverse feature extractors without significantly increasing parameters. The unified framework of our DA method will simultaneously learn invariance across domains, reduce divergence of feature representations, and adapt label prediction. Our DNN has 4.1M parameters, which is only 6.7% of AlexNet or 59% of GoogLeNet. Experiments show that our DNN obtains GoogLeNet-level accuracy both on classification and DA, and our DA method slightly outperforms previous competitive ones. Put all together, our DA strategy based on our DNN achieves state-of-the-art on sixteen of total eighteen DA tasks on popular Office-31 and Office-Caltech datasets.

##### Abstract (translated by Google)
最近，基于网络体系结构设计（例如SqueezeNet）的DNN模型压缩引起了很多关注。与众所周知的模型相比，在这些非常紧凑的网络上没有观察到图像分类的精度下降。然而，一个新兴的问题是这些模型压缩技术是否会影响DNN的学习能力，而不是将图像分类到单个数据集上。我们的初步实验表明，尽管保持了分类性能，但这些压缩方法可能降低域适应（DA）能力。因此，本文提出了一种新的紧凑型网络架构和无监督DA方法。 DNN建立在一个新的基本模块Conv-M上，它提供了更多不同的特征提取器，而不会显着增加参数。 DA方法的统一框架将同时学习跨领域的不变性，减少特征表示的发散，并适应标签预测。我们的DNN有4.1M参数，只有AlexNet的6.7％或者GoogLeNet的59％。实验表明，我们的DNN在分类和DA方面获得了GoogLeNet级别的准确性，而且我们的DA方法稍微胜过了以前的竞争。总而言之，基于我们的DNN的DA战略在流行的Office-31和Office-Caltech数据集的十八个DA任务中的十六个达到了最先进的水平。

##### URL
[https://arxiv.org/abs/1703.04071](https://arxiv.org/abs/1703.04071)

##### PDF
[https://arxiv.org/pdf/1703.04071](https://arxiv.org/pdf/1703.04071)

