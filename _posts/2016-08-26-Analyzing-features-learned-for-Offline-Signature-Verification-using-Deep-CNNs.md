---
layout: post
title: "Analyzing features learned for Offline Signature Verification using Deep CNNs"
date: 2016-08-26 14:52:55
categories: arXiv_CV
tags: arXiv_CV CNN
author: Luiz G. Hafemann, Robert Sabourin, Luiz S. Oliveira
mathjax: true
---

* content
{:toc}

##### Abstract
Research on Offline Handwritten Signature Verification explored a large variety of handcrafted feature extractors, ranging from graphology, texture descriptors to interest points. In spite of advancements in the last decades, performance of such systems is still far from optimal when we test the systems against skilled forgeries - signature forgeries that target a particular individual. In previous research, we proposed a formulation of the problem to learn features from data (signature images) in a Writer-Independent format, using Deep Convolutional Neural Networks (CNNs), seeking to improve performance on the task. In this research, we push further the performance of such method, exploring a range of architectures, and obtaining a large improvement in state-of-the-art performance on the GPDS dataset, the largest publicly available dataset on the task. In the GPDS-160 dataset, we obtained an Equal Error Rate of 2.74%, compared to 6.97% in the best result published in literature (that used a combination of multiple classifiers). We also present a visual analysis of the feature space learned by the model, and an analysis of the errors made by the classifier. Our analysis shows that the model is very effective in separating signatures that have a different global appearance, while being particularly vulnerable to forgeries that very closely resemble genuine signatures, even if their line quality is bad, which is the case of slowly-traced forgeries.

##### Abstract (translated by Google)
离线手写签名验证的研究探索了大量的手工特征提取器，从图形学，纹理描述符到兴趣点。尽管在过去的几十年里取得了进步，但是当我们测试这个系统对抗熟练的伪造者时，这样的系统的性能仍然远远不够理想 - 针对特定个体的签名伪造。在以前的研究中，我们提出了使用深度卷积神经网络（CNN）以独立于Writer的格式从数据（签名图像）中学习特征的问题的表达，以寻求改善性能的任务。在这项研究中，我们进一步推进了这种方法的性能，探索了一系列的架构，并在GPDS数据集上获得了最先进的性能的大幅度改进，该数据集是最大的公开数据集。在GPDS-160数据集中，我们获得了2.74％的等差错率，而在文献（使用多个分类器的组合）中发表的最佳结果中，其平均错误率为6.97％。我们还对模型学习到的特征空间进行了可视化分析，并分析了分类器产生的错误。我们的分析表明，该模型在分离具有不同全局外观的签名方面是非常有效的，而且即使线条质量不好，伪造的情况也是如此，特别容易受到非常类似于真实签名的伪造。

##### URL
[https://arxiv.org/abs/1607.04573](https://arxiv.org/abs/1607.04573)

##### PDF
[https://arxiv.org/pdf/1607.04573](https://arxiv.org/pdf/1607.04573)

