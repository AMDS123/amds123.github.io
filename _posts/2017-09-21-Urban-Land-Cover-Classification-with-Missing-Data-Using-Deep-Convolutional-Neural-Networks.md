---
layout: post
title: "Urban Land Cover Classification with Missing Data Using Deep Convolutional Neural Networks"
date: 2017-09-21 15:46:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Classification Deep_Learning
author: Michael Kampffmeyer, Arnt-Børre Salberg, Robert Jenssen
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic urban land cover classification is a classical problem in remote sensing and good urban land cover maps build the foundation for many tasks, such as e.g. environmental monitoring. It is a particularly challenging problem, as classes generally have high inter-class and low intra-class variance. A common technique to improve urban land cover classification performance in remote sensing is the fusing of data from different sensors with different data modalities. However, all modalities are rarely available for all test data, and this missing data problem poses severe challenges for multi-modal learning. Inspired by recent successes in deep learning, we propose as a remedy a convolutional neural network (CNN) architecture for urban remote sensing image segmentation trained on data modalities which are not all available at test time. We train our architecture with a cost function particularly suited for imbalanced classes, as this is a frequent problem in remote sensing, especially in urban areas. We demonstrate the method using two benchmark datasets, both consisting of optical and digital surface model (DSM) images. We simulate missing data, by assuming that the DSM images are missing during testing and show that our method outperforms both CNNs trained on optical images as well as an ensemble of two CNNs trained only on optical images. We further evaluate the potential of our method to handle situations where only some DSM images are missing during training and show that we can clearly exploit training time information of the missing modality during testing.

##### Abstract (translated by Google)
城市土地覆盖自动分类是遥感中的一个经典问题，良好的城市土地覆盖地图为许多任务奠定了基础，环境监测。这是一个特别具有挑战性的问题，因为班级一般具有较高的班级间和较低的班内差异。提高城市土地覆盖遥感分类性能的一项常用技术是将来自不同传感器的数据融合到不同的数据模式中。然而，所有的测试数据都很少有可用的模式，这种缺失的数据问题给多模式学习带来了严峻的挑战。受近期在深度学习方面取得的成功的启发，我们提出了一种用于城市遥感图像分割的卷积神经网络（CNN）体系结构，该体系结构在数据模式上进行了训练，而这些数据模式在测试时并非全部可用。我们使用特别适合不平衡班级的成本函数来训练我们的架构，因为这是遥感领域的一个常见问题，特别是在城市地区。我们演示了使用两个基准数据集的方法，包括光学和数字表面模型（DSM）图像。我们通过假设测试期间DSM图像丢失来模拟丢失的数据，并且证明我们的方法优于在光学图像上训练的CNN以及仅在光学图像上训练的两个CNN的合奏。我们进一步评估了我们的方法处理在训练期间只有一些DSM图像缺失的情况的潜力，并且显示我们可以在测试期间清楚地利用缺失模态的训练时间信息。

##### URL
[https://arxiv.org/abs/1709.07383](https://arxiv.org/abs/1709.07383)

##### PDF
[https://arxiv.org/pdf/1709.07383](https://arxiv.org/pdf/1709.07383)

