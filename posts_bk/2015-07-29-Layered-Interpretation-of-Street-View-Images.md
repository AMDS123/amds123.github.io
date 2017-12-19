---
layout: post
title: "Layered Interpretation of Street View Images"
date: 2015-07-29 15:38:28
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Ming-Yu Liu, Shuoxin Lin, Srikumar Ramalingam, Oncel Tuzel
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a layered street view model to encode both depth and semantic information on street view images for autonomous driving. Recently, stixels, stix-mantics, and tiered scene labeling methods have been proposed to model street view images. We propose a 4-layer street view model, a compact representation over the recently proposed stix-mantics model. Our layers encode semantic classes like ground, pedestrians, vehicles, buildings, and sky in addition to the depths. The only input to our algorithm is a pair of stereo images. We use a deep neural network to extract the appearance features for semantic classes. We use a simple and an efficient inference algorithm to jointly estimate both semantic classes and layered depth values. Our method outperforms other competing approaches in Daimler urban scene segmentation dataset. Our algorithm is massively parallelizable, allowing a GPU implementation with a processing speed about 9 fps.

##### Abstract (translated by Google)
我们提出了一种分层的街景模型来对街景图像的深度和语义信息进行编码以进行自主驾驶。最近，已经提出了用于模拟街景图像的stixels，stix-mantics和分层场景标记方法。我们提出了一个4层街景模型，在最近提出的stix-mantics模型上的一个紧凑的表示。除了深度之外，我们的图层还编码语义类，如地面，行人，车辆，建筑物和天空。我们算法的唯一输入是一对立体图像。我们使用深度神经网络来提取语义类的外观特征。我们使用一个简单而有效的推理算法来联合估计语义类和分层深度值。我们的方法胜过戴姆勒城市场景分割数据集中的其他竞争方法。我们的算法是大规模并行化的，允许GPU处理速度大约为9 fps。

##### URL
[https://arxiv.org/abs/1506.04723](https://arxiv.org/abs/1506.04723)

##### PDF
[https://arxiv.org/pdf/1506.04723](https://arxiv.org/pdf/1506.04723)

