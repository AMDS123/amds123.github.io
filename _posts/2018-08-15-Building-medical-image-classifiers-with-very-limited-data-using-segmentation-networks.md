---
layout: post
title: "Building medical image classifiers with very limited data using segmentation networks"
date: 2018-08-15 17:52:09
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Transfer_Learning Classification Deep_Learning
author: Ken C. L. Wong, Tanveer Syeda-Mahmood, Mehdi Moradi
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has shown promising results in medical image analysis, however, the lack of very large annotated datasets confines its full potential. Although transfer learning with ImageNet pre-trained classification models can alleviate the problem, constrained image sizes and model complexities can lead to unnecessary increase in computational cost and decrease in performance. As many common morphological features are usually shared by different classification tasks of an organ, it is greatly beneficial if we can extract such features to improve classification with limited samples. Therefore, inspired by the idea of curriculum learning, we propose a strategy for building medical image classifiers using features from segmentation networks. By using a segmentation network pre-trained on similar data as the classification task, the machine can first learn the simpler shape and structural concepts before tackling the actual classification problem which usually involves more complicated concepts. Using our proposed framework on a 3D three-class brain tumor type classification problem, we achieved 82% accuracy on 191 testing samples with 91 training samples. When applying to a 2D nine-class cardiac semantic level classification problem, we achieved 86% accuracy on 263 testing samples with 108 training samples. Comparisons with ImageNet pre-trained classifiers and classifiers trained from scratch are presented.

##### Abstract (translated by Google)
深度学习在医学图像分析中显示出有希望的结果，然而，缺乏非常大的注释数据集限制了其全部潜力。尽管使用ImageNet预训练分类模型的转移学习可以缓解该问题，但是约束的图像大小和模型复杂性可能导致计算成本的不必要的增加和性能的降低。由于许多常见的形态特征通常由器官的不同分类任务共享，因此如果我们能够提取这些特征以改进有限样本的分类，则是非常有益的。因此，受课程学习理念的启发，我们提出了一种使用细分网络特征构建医学图像分类器的策略。通过使用在类似数据上预先训练的分割网络作为分类任务，机器可以在解决通常涉及更复杂概念的实际分类问题之前首先学习更简单的形状和结构概念。使用我们提出的关于3D三级脑肿瘤类型分类问题的框架，我们在191个测试样本上获得了82％的准确性，其中91个训练样本。当应用于二维九级心脏语义水平分类问题时，我们在263个测试样本上获得了86％的准确度，其中包含108个训练样本。提供了与从头开始训练的ImageNet预训练分类器和分类器的比较。

##### URL
[http://arxiv.org/abs/1808.05205](http://arxiv.org/abs/1808.05205)

##### PDF
[http://arxiv.org/pdf/1808.05205](http://arxiv.org/pdf/1808.05205)

