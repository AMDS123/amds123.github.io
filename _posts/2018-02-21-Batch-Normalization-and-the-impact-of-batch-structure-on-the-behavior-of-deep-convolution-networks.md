---
layout: post
title: "Batch Normalization and the impact of batch structure on the behavior of deep convolution networks"
date: 2018-02-21 14:47:18
categories: arXiv_CV
tags: arXiv_CV Inference
author: Mohamed Hajaj, Duncan Gillies
mathjax: true
---

* content
{:toc}

##### Abstract
Batch normalization was introduced in 2015 to speed up training of deep convolution networks by normalizing the activations across the current batch to have zero mean and unity variance. The results presented here show an interesting aspect of batch normalization, where controlling the shape of the training batches can influence what the network will learn. If training batches are structured as balanced batches (one image per class), and inference is also carried out on balanced test batches, using the batch's own means and variances, then the conditional results will improve considerably. The network uses the strong information about easy images in a balanced batch, and propagates it through the shared means and variances to help decide the identity of harder images on the same batch. Balancing the test batches requires the labels of the test images, which are not available in practice, however further investigation can be done using batch structures that are less strict and might not require the test image labels. The conditional results show the error rate almost reduced to zero for nontrivial datasets with small number of classes such as the CIFAR10.

##### Abstract (translated by Google)
批量归一化是在2015年引入的，通过将当前批次的激活标准化为零均值和统一方差来加速深度卷积网络的训练。这里展示的结果显示了批量标准化的一个有趣方面，其中控制培训批次的形状可以影响网络将学习的内容。如果培训批次的结构为平衡批次（每班一个图像），并且对平衡测试批次也进行推理，使用批次自己的方法和差异，则条件结果将大大提高。网络在平衡的批次中使用关于简单图像的强大信息，并通过共享手段和差异传播该信息，以帮助确定同一批次中较硬图像的身份。平衡测试批次需要测试图像的标签，实际上这些标签是不可用的，但是可以使用不太严格并且可能不需要测试图像标签的批量结构进行进一步调查。条件结果显示，对于CIFAR10等少数类别的非平凡数据集，错误率几乎降为零。

##### URL
[http://arxiv.org/abs/1802.07590](http://arxiv.org/abs/1802.07590)

##### PDF
[http://arxiv.org/pdf/1802.07590](http://arxiv.org/pdf/1802.07590)

