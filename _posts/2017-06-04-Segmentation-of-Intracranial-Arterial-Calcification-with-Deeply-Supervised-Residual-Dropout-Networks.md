---
layout: post
title: "Segmentation of Intracranial Arterial Calcification with Deeply Supervised Residual Dropout Networks"
date: 2017-06-04 21:13:12
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge Segmentation CNN Optimization Relation
author: Gerda Bortsova, Gijs van Tulder, Florian Dubost, Tingying Peng, Nassir Navab, Aad van der Lugt, Daniel Bos, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
Intracranial carotid artery calcification (ICAC) is a major risk factor for stroke, and might contribute to dementia and cognitive decline. Reliance on time-consuming manual annotation of ICAC hampers much demanded further research into the relationship between ICAC and neurological diseases. Automation of ICAC segmentation is therefore highly desirable, but difficult due to the proximity of the lesions to bony structures with a similar attenuation coefficient. In this paper, we propose a method for automatic segmentation of ICAC; the first to our knowledge. Our method is based on a 3D fully convolutional neural network that we extend with two regularization techniques. Firstly, we use deep supervision (hidden layers supervision) to encourage discriminative features in the hidden layers. Secondly, we augment the network with skip connections, as in the recently developed ResNet, and dropout layers, inserted in a way that skip connections circumvent them. We investigate the effect of skip connections and dropout. In addition, we propose a simple problem-specific modification of the network objective function that restricts the focus to the most important image regions and simplifies the optimization. We train and validate our model using 882 CT scans and test on 1,000. Our regularization techniques and objective improve the average Dice score by 7.1%, yielding an average Dice of 76.2% and 97.7% correlation between predicted ICAC volumes and manual annotations.

##### Abstract (translated by Google)
颅内颈动脉钙化（ICAC）是中风的主要危险因素，并可能导致痴呆和认知能力下降。依赖于耗时费力的ICAC手工标注阻碍了对ICAC与神经系统疾病之间关系的进一步研究。因此，ICAC分割的自动化是非常需要的，但是由于病变靠近具有类似衰减系数的骨结构而难以实现。在本文中，我们提出一种自动分割ICAC的方法;第一个就是我们的知识。我们的方法是基于一个三维完全卷积神经网络，我们扩展了两个正则化技术。首先，我们使用深层监督（隐藏层监督）来鼓励隐藏层中的判别特征。其次，如最近开发的ResNet那样，通过跳过连接来增加网络，并且以跳过连接的方式插入丢失层。我们调查跳过连接和退出的影响。此外，我们提出了一个简单的问题特定的网络目标函数修改，将重点限制在最重要的图像区域，并简化了优化。我们使用882 CT扫描和1000测试来训练和验证我们的模型。我们的正规化技术和目标将骰子的平均得分提高了7.1％，产生预测的ICAC体积和手工注释之间的平均骰子76.2％和97.7％的相关性。

##### URL
[https://arxiv.org/abs/1706.01148](https://arxiv.org/abs/1706.01148)

##### PDF
[https://arxiv.org/pdf/1706.01148](https://arxiv.org/pdf/1706.01148)

