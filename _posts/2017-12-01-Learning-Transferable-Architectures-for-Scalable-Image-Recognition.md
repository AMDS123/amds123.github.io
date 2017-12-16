---
layout: post
title: "Learning Transferable Architectures for Scalable Image Recognition"
date: 2017-12-01 07:48:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Image_Classification Classification Detection Recognition
author: Barret Zoph, Vijay Vasudevan, Jonathon Shlens, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
Developing neural network image classification models often requires significant architecture engineering. In this paper, we attempt to automate this engineering process by learning the model architectures directly on the dataset of interest. As this approach is expensive when the dataset is large, we propose to search for an architectural building block on a small dataset and then transfer the block to a larger dataset. Our key contribution is the design of a new search space which enables transferability. In our experiments, we search for the best convolutional layer (or "cell") on the CIFAR-10 dataset and then apply this cell to the ImageNet dataset by stacking together more copies of this cell, each with their own parameters. Although the cell is not searched for directly on ImageNet, an architecture constructed from the best cell achieves, among the published works, state-of-the-art accuracy of 82.7% top-1 and 96.2% top-5 on ImageNet. Our model is 1.2% better in top-1 accuracy than the best human-invented architectures while having 9 billion fewer FLOPS -- a reduction of 28% in computational demand from the previous state-of-the-art model. When evaluated at different levels of computational cost, accuracies of our models exceed those of the state-of-the-art human-designed models. For instance, a smaller network constructed from the best cell also achieves 74% top-1 accuracy, which is 3.1% better than equivalently-sized, state-of-the-art models for mobile platforms. On CIFAR-10, an architecture constructed from the best cell achieves 2.4% error rate, which is also state-of-the-art. Finally, the image features learned from image classification can also be transferred to other computer vision problems. On the task of object detection, the learned features used with the Faster-RCNN framework surpass state-of-the-art by 4.0% achieving 43.1% mAP on the COCO dataset.

##### Abstract (translated by Google)
开发神经网络图像分类模型往往需要重要的架构工程。在本文中，我们试图通过直接在感兴趣的数据集上学习模型架构来自动化这个工程过程。由于这种方法在数据集很大时很昂贵，我们建议在一个小的数据集上搜索一个建筑模块，然后将这个模块转移到一个更大的数据集上。我们的主要贡献是设计一个新的搜索空间，使可转移性。在我们的实验中，我们在CIFAR-10数据集上搜索最好的卷积层（或“单元”），然后通过将这个单元的更多副本堆叠在一起，将这个单元应用到ImageNet数据集中，每个副本都有自己的参数。虽然这个单元格不是直接在ImageNet上搜索的，但是从最好的单元格构建的体系结构在已发表的作品中，在ImageNet上排名前八位的最高分别为82.7％和96.2％。我们的模型比最好的人工发现的架构精度高1.2％，同时FLOPS减少90亿次 - 与以前最先进的模型相比计算需求减少了28％。当以不同的计算成本水平进行评估时，我们模型的精确度超过了最先进的人工设计模型的精度。例如，由最好的小区构建的较小的网络也实现了74％的最高精度，比移动平台的同等大小，最先进的模型好3.1％。在CIFAR-10上，由最佳单元构建的架构实现了2.4％的错误率，这也是最先进的。最后，从图像分类学习的图像特征也可以转移到其他计算机视觉问题。在对象检测的任务中，与Faster-RCNN框架一起使用的学习特性超过了最新的4.0％，在COCO数据集上达到了43.1％的mAP。

##### URL
[https://arxiv.org/abs/1707.07012](https://arxiv.org/abs/1707.07012)

##### PDF
[https://arxiv.org/pdf/1707.07012](https://arxiv.org/pdf/1707.07012)

