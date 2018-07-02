---
layout: post
title: "Detecting Mammals in UAV Images: Best Practices to address a substantially Imbalanced Dataset with Deep Learning"
date: 2018-06-29 11:59:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge CNN Deep_Learning Detection Recommendation
author: Benjamin Kellenberger, Diego Marcos, Devis Tuia
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge over the number of animals in large wildlife reserves is a vital necessity for park rangers in their efforts to protect endangered species. Manual animal censuses are dangerous and expensive, hence Unmanned Aerial Vehicles (UAVs) with consumer level digital cameras are becoming a popular alternative tool to estimate livestock. Several works have been proposed that semi-automatically process UAV images to detect animals, of which some employ Convolutional Neural Networks (CNNs), a recent family of deep learning algorithms that proved very effective in object detection in large datasets from computer vision. However, the majority of works related to wildlife focuses only on small datasets (typically subsets of UAV campaigns), which might be detrimental when presented with the sheer scale of real study areas for large mammal census. Methods may yield thousands of false alarms in such cases. In this paper, we study how to scale CNNs to large wildlife census tasks and present a number of recommendations to train a CNN on a large UAV dataset. We further introduce novel evaluation protocols that are tailored to censuses and model suitability for subsequent human verification of detections. Using our recommendations, we are able to train a CNN reducing the number of false positives by an order of magnitude compared to previous state-of-the-art. Setting the requirements at 90% recall, our CNN allows to reduce the amount of data required for manual verification by three times, thus making it possible for rangers to screen all the data acquired efficiently and to detect almost all animals in the reserve automatically.

##### Abstract (translated by Google)
关于大型野生动物保护区动物数量的知识对于公园护林员努力保护濒危物种至关重要。手动动物普查是危险和昂贵的，因此配备消费级数码相机的无人驾驶飞行器（UAV）正在成为评估牲畜的一种常用替代工具。已经有人提出了一些半自动处理无人机图像以检测动物的作品，其中一些采用了卷积神经网络（CNN），这是最近的一种深度学习算法，在计算机视觉的大型数据集中被证明对物体检测非常有效。然而，与野生动物有关的大多数作品只关注小型数据集（通常是无人机活动的子集），这在向大型哺乳动物普查提供真正的研究区域时可能是有害的。在这种情况下，方法可能会产生数千次错误警报。在本文中，我们研究如何将CNN扩展到大型野生动植物普查任务，并提出若干建议，以在大型无人机数据集上训练CNN。我们进一步介绍新的评估协议，这些协议是为人口普查量身定制的，并且适用于后续人体检测验证的模型适用性。使用我们的建议，我们能够训练CNN，与以前的最新技术相比，将误报数量减少了一个数量级。通过将需求设置为90％的召回率，我们的CNN允许将手动验证所需的数据量减少三倍，从而使游侠能够有效地屏蔽所有获得的数据并自动检测保留区中的几乎所有动物。

##### URL
[http://arxiv.org/abs/1806.11368](http://arxiv.org/abs/1806.11368)

##### PDF
[http://arxiv.org/pdf/1806.11368](http://arxiv.org/pdf/1806.11368)

