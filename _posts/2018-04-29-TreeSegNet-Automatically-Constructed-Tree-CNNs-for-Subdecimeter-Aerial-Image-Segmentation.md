---
layout: post
title: "TreeSegNet: Automatically Constructed Tree CNNs for Subdecimeter Aerial Image Segmentation"
date: 2018-04-29 06:17:00
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding CNN Semantic_Segmentation
author: Kai Yue, Lei Yang, Ruirui Li, Wei Hu, Fan Zhang, Wei Li
mathjax: true
---

* content
{:toc}

##### Abstract
For the task of subdecimeter aerial imagery segmentation, the fine-grained semantic segmentation results are usually difficult to obtain because of complex remote sensing contents and optical conditions. In addition, remote sensing imagery has inherent limitations of imbalanced class distribution. Recently, convolutional neural networks (CNNs) have shown outstanding performance on this task. In this paper, we propose the TreeSegNet to solve the class imbalance problem and further improve the accuracy in the metrics' point of view. Based on the infrastructure of DeepUNet, a Tree-CNN model in which each node represents a ResNeXt unit is constructed automatically according to confusion matrix and minimum graph cut algorithm. By transporting feature maps by concatenating connections, the Tree-CNN block fuses the multiscale features and learning the best weights for the model. In the experiments on ISPRS 2D semantic labeling Potsdam dataset, the results gotten by TreeSegNet are better than the opened state-of-the-art methods. The F1 measure scores of classes are improved especially for those classes that are easily confused. Completely and detailed comparison and analysis are performed to show that the improvement is brought by the construction and the embedding of the Tree-CNN module.

##### Abstract (translated by Google)
由于复杂的遥感内容和光学条件，对于亚高空航片图像分割任务来说，细粒度的语义分割结果通常很难获得。另外，遥感影像具有不平衡类分布的固有局限性。最近，卷积神经网络（CNN）在这项任务中表现出色。在本文中，我们提出了TreeSegNet来解决类不平衡问题，并进一步提高度量角度的准确性。基于DeepUNet的基础设施，根据混淆矩阵和最小图切割算法，自动构建每个节点代表ResNeXt单元的Tree-CNN模型。通过连接连接传输特征地图，Tree-CNN块将多尺度特征融合并学习模型的最佳权重。在ISPRS 2D语义标注波茨坦数据集的实验中，TreeSegNet获得的结果优于开放的最先进的方法。对于容易混淆的类别，F1类别的测量分数得到了提高。进行全面和详细的比较和分析，以表明改进是由Tree-CNN模块的构建和嵌入带来的。

##### URL
[https://arxiv.org/abs/1804.10879](https://arxiv.org/abs/1804.10879)

##### PDF
[https://arxiv.org/pdf/1804.10879](https://arxiv.org/pdf/1804.10879)

