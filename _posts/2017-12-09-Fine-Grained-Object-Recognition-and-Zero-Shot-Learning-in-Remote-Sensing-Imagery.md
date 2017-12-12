---
layout: post
title: "Fine-Grained Object Recognition and Zero-Shot Learning in Remote Sensing Imagery"
date: 2017-12-09 00:44:39
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Inference Language_Model Relation Recognition
author: Gencer Sumbul, Ramazan Gokberk Cinbis, Selim Aksoy
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained object recognition that aims to identify the type of an object among a large number of subcategories is an emerging application with the increasing resolution that exposes new details in image data. Traditional fully supervised algorithms fail to handle this problem where there is low between-class variance and high within-class variance for the classes of interest with small sample sizes. We study an even more extreme scenario named zero-shot learning (ZSL) in which no training example exists for some of the classes. ZSL aims to build a recognition model for new unseen categories by relating them to seen classes that were previously learned. We establish this relation by learning a compatibility function between image features extracted via a convolutional neural network and auxiliary information that describes the semantics of the classes of interest by using training samples from the seen classes. Then, we show how knowledge transfer can be performed for the unseen classes by maximizing this function during inference. We introduce a new data set that contains 40 different types of street trees in 1-ft spatial resolution aerial data, and evaluate the performance of this model with manually annotated attributes, a natural language model, and a scientific taxonomy as auxiliary information. The experiments show that the proposed model achieves 14.3% recognition accuracy for the classes with no training examples, which is significantly better than a random guess accuracy of 6.3% for 16 test classes, and three other ZSL algorithms.

##### Abstract (translated by Google)
旨在识别大量子类别中的对象的类型的细粒度对象识别是新兴的应用，其分辨率越来越高，这揭示了图像数据中的新细节。传统的完全监督算法无法处理这个问题，即对于样本量较小的感兴趣类，类间方差较小，类内方差较高。我们研究一个更为极端的情景，即零点学习（ZSL），其中一些类没有训练样例。 ZSL的目标是建立一个新的看不见的类别的识别模型，将它们与以前学过的可见类相关联。我们通过学习通过卷积神经网络提取的图像特征之间的兼容性函数和通过使用来自所看到的类别的训练样本来描述感兴趣类别的语义的辅助信息来建立这种关系。然后，我们将展示如何通过在推理过程中最大化这个功能来对不可见的类进行知识转移。我们引入一个新的数据集，其中包含40种不同类型的空间分辨率航拍数据，通过手动注释属性，自然语言模型和科学分类作为辅助信息来评估该模型的性能。实验结果表明，该模型对无训练样本类的识别准确率达到14.3％，明显优于16个测试类和其他三种ZSL算法的随机猜测准确率6.3％。

##### URL
[http://arxiv.org/abs/1712.03323](http://arxiv.org/abs/1712.03323)

##### PDF
[http://arxiv.org/pdf/1712.03323](http://arxiv.org/pdf/1712.03323)

