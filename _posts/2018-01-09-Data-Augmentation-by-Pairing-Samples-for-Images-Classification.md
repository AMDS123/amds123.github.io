---
layout: post
title: "Data Augmentation by Pairing Samples for Images Classification"
date: 2018-01-09 13:37:11
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Hiroshi Inoue
mathjax: true
---

* content
{:toc}

##### Abstract
Data augmentation is a widely used technique in many machine learning tasks, such as image classification, to virtually enlarge the training dataset size and avoid overfitting. Traditional data augmentation techniques for image classification tasks create new samples from the original training data by, for example, flipping, distorting, adding a small amount of noise to, or cropping a patch from an original image. In this paper, we introduce a simple but surprisingly effective data augmentation technique for image classification tasks. With our technique, named SamplePairing, we synthesize a new sample from one image by overlaying another image randomly chosen from the training data (i.e., taking an average of two images for each pixel). By using two images randomly selected from the training set, we can generate $N^2$ new samples from $N$ training samples. This simple data augmentation technique significantly improved classification accuracy for all the tested datasets; for example, the top-1 error rate was reduced from 33.5% to 29.0% for the ILSVRC 2012 dataset with GoogLeNet and from 8.22% to 6.93% in the CIFAR-10 dataset. We also show that our SamplePairing technique largely improved accuracy when the number of samples in the training set was very small. Therefore, our technique is more valuable for tasks with a limited amount of training data, such as medical imaging tasks.

##### Abstract (translated by Google)
数据增强是许多机器学习任务中广泛使用的技术，例如图像分类，以虚拟放大训练数据集大小并避免过度拟合。用于图像分类任务的传统数据增强技术通过例如翻转，扭曲，向原始图像中添加少量噪声或从中裁剪补丁，从原始训练数据中创建新的样本。在本文中，我们介绍一种简单但令人惊讶的数据增强技术，用于图像分类任务。使用我们的名为SamplePairing的技术，我们通过叠加从训练数据中随机选择的另一个图像（即，为每个像素取平均两个图像）来从一个图像合成新的样本。通过使用从训练集中随机选择的两幅图像，我们可以从$ N $个训练样本中生成$ N ^ 2 $个新样本。这种简单的数据增强技术显着改善了所有测试数据集的分类准确性;例如，使用GoogLeNet的ILSVRC 2012数据集的前1个错误率从33.5％降低到29.0％，并且在CIFAR-10数据集中从8.22％降低到6.93％。我们还展示了当训练集中的样本数量非常小时，我们的SamplePairing技术大大提高了准确性。因此，我们的技术对于训练数据量有限的任务（如医学成像任务）更有价值。

##### URL
[http://arxiv.org/abs/1801.02929](http://arxiv.org/abs/1801.02929)

##### PDF
[http://arxiv.org/pdf/1801.02929](http://arxiv.org/pdf/1801.02929)

