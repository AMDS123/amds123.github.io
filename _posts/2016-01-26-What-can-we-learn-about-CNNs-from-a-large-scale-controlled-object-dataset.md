---
layout: post
title: "What can we learn about CNNs from a large scale controlled object dataset?"
date: 2016-01-26 16:56:11
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Deep_Learning Recognition
author: Ali Borji, Saeed Izadi, Laurent Itti
mathjax: true
---

* content
{:toc}

##### Abstract
Tolerance to image variations (e.g. translation, scale, pose, illumination) is an important desired property of any object recognition system, be it human or machine. Moving towards increasingly bigger datasets has been trending in computer vision specially with the emergence of highly popular deep learning models. While being very useful for learning invariance to object inter- and intra-class shape variability, these large-scale wild datasets are not very useful for learning invariance to other parameters forcing researchers to resort to other tricks for training a model. In this work, we introduce a large-scale synthetic dataset, which is freely and publicly available, and use it to answer several fundamental questions regarding invariance and selectivity properties of convolutional neural networks. Our dataset contains two parts: a) objects shot on a turntable: 16 categories, 8 rotation angles, 11 cameras on a semicircular arch, 5 lighting conditions, 3 focus levels, variety of backgrounds (23.4 per instance) generating 1320 images per instance (over 20 million images in total), and b) scenes: in which a robot arm takes pictures of objects on a 1:160 scale scene. We study: 1) invariance and selectivity of different CNN layers, 2) knowledge transfer from one object category to another, 3) systematic or random sampling of images to build a train set, 4) domain adaptation from synthetic to natural scenes, and 5) order of knowledge delivery to CNNs. We also explore how our analyses can lead the field to develop more efficient CNNs.

##### Abstract (translated by Google)
图像变化的容差（例如平移，缩放，姿态，照明）是任何物体识别系统（无论是人还是机器）的重要期望属性。随着高度流行的深度学习模式的出现，走向日益庞大的数据集趋向于计算机视觉。这些大规模的野生数据集对于学习不变性来反对类内和类间的形状变化是非常有用的，但是这些大规模的野生数据集对于学习其他参数的不变性是非常有用的，迫使研究者采用其他技巧来训练模型。在这项工作中，我们引入一个大规模的合成数据集，这是自由公开的，并用它来回答关于卷积神经网络的不变性和选择性性质的几个基本问​​题。我们的数据集包含两部分：a）在转盘上拍摄的物体：16个类别，8个旋转角度，半圆弧上的11个摄像机，5个光照条件，3个焦点级别，各种背景（每个实例23.4个），每个实例产生1320个图像总共超过2000万张图像）; b）场景：机器人手臂在1：160的比例场景下拍摄物体。我们研究：1）不同CNN层的不变性和选择性; 2）从一个对象类别到另一个对象类别的知识转移; 3）图像的系统或随机抽样以建立一个训练集; 4）从合成到自然场景的领域适应; ）知识传递给CNN的顺序。我们还探索了我们的分析如何引导该领域开发更有效的CNN。

##### URL
[https://arxiv.org/abs/1512.01320](https://arxiv.org/abs/1512.01320)

##### PDF
[https://arxiv.org/pdf/1512.01320](https://arxiv.org/pdf/1512.01320)

