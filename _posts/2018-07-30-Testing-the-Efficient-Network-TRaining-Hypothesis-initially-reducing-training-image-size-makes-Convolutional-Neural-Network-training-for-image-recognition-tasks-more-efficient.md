---
layout: post
title: "Testing the Efficient Network TRaining Hypothesis: initially reducing training image size makes Convolutional Neural Network training for image recognition tasks more efficient"
date: 2018-07-30 21:10:25
categories: arXiv_AI
tags: arXiv_AI Regularization CNN Inference Recognition
author: Thomas Cherico Wanger, Peter Frohn
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNN) for image recognition tasks are seeing rapid advances in the available architectures and how networks are trained based on large computational infrastructure and standard datasets with millions of images. In contrast, performance and time constraints for example, of small devices and free cloud GPUs necessitate efficient network training (i.e., highest accuracy in the shortest inference time possible), often on small datasets. Here, we hypothesize that initially decreasing image size during training makes the training process more efficient, because pre-shaping weights with small images and later utilizing these weights with larger images reduces initial network parameters and total inference time. We test this Efficient Network TRaining (ENTR) Hypothesis by training pre-trained Residual Network (ResNet) models (ResNet18, 34, &amp; 50) on three small datasets (steel microstructures, bee images, and geographic aerial images) with a free cloud GPU. Based on three training regimes of i) not, ii) gradually or iii) in one step increasing image size over the training process, we show that initially reducing image size increases training efficiency consistently across datasets and networks. We interpret these results mechanistically in the framework of regularization theory. Support for the ENTR hypothesis is an important contribution, because network efficiency improvements for image recognition tasks are needed for practical applications. In the future, it will be exciting to see how the ENTR hypothesis holds for large standard datasets like ImageNet or CIFAR, to better understand the underlying mechanisms, and how these results compare to other fields such as structural learning.

##### Abstract (translated by Google)
用于图像识别任务的卷积神经网络（CNN）正在看到可用架构的快速发展以及如何基于大型计算基础设施和具有数百万图像的标准数据集来训练网络。相反，例如小型设备和免费云GPU的性能和时间限制需要有效的网络训练（即，在最短的推断时间内的最高精度），通常在小型数据集上。在这里，我们假设最初在训练期间减小图像尺寸使得训练过程更有效，因为利用小图像预先整形权重并且稍后利用具有较大图像的这些权重减少了初始网络参数和总推理时间。我们通过使用自由云在三个小数据集（钢微结构，蜂图像和地理航拍图像）上训练预训练的残差网络（ResNet）模型（ResNet18,34和50）来测试这种高效网络训练（ENTR）假设GPU。基于以下三种训练方案：i）不是，ii）逐步或iii）一步增加训练过程中的图像大小，我们表明最初减小图像大小可以在数据集和网络中一致地提高训练效率。我们在正则化理论的框架中机械地解释这些结果。对ENTR假设的支持是一项重要贡献，因为实际应用需要提高图像识别任务的网络效率。将来，看看ENTR假设如何适用于像ImageNet或CIFAR这样的大型标准数据集，以更好地理解基础机制，以及这些结果与结构学习等其他领域的比较，将会令人兴奋。

##### URL
[http://arxiv.org/abs/1807.11583](http://arxiv.org/abs/1807.11583)

##### PDF
[http://arxiv.org/pdf/1807.11583](http://arxiv.org/pdf/1807.11583)

