---
layout: post
title: "Segmentation of histological images and fibrosis identification with a convolutional neural network"
date: 2018-03-20 08:48:24
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation GAN CNN
author: Xiaohang Fu, Tong Liu, Zhaohan Xiong, Bruce H. Smaill, Martin K. Stiles, Jichao Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation of histological images is one of the most crucial tasks for many biomedical analyses including quantification of certain tissue type. However, challenges are posed by high variability and complexity of structural features in such images, in addition to imaging artifacts. Further, the conventional approach of manual thresholding is labor-intensive, and highly sensitive to inter- and intra-image intensity variations. An accurate and robust automated segmentation method is of high interest. We propose and evaluate an elegant convolutional neural network (CNN) designed for segmentation of histological images, particularly those with Masson's trichrome stain. The network comprises of 11 successive convolutional - rectified linear unit - batch normalization layers, and outperformed state-of-the-art CNNs on a dataset of cardiac histological images (labeling fibrosis, myocytes, and background) with a Dice similarity coefficient of 0.947. With 100 times fewer (only 300 thousand) trainable parameters, our CNN is less susceptible to overfitting, and is efficient. Additionally, it retains image resolution from input to output, captures fine-grained details, and can be trained end-to-end smoothly. To the best of our knowledge, this is the first deep CNN tailored for the problem of concern, and may be extended to solve similar segmentation tasks to facilitate investigations into pathology and clinical treatment.

##### Abstract (translated by Google)
组织学图像的分割是许多生物医学分析中最重要的任务之一，包括对某些组织类型的量化。然而，除了成像伪像之外，这些图像中结构特征的高度可变性和复杂性造成了挑战。此外，手动阈值处理的传统方法是劳动密集型的，并且对图像间和图像内的强度变化高度敏感。一个准确和强大的自动分割方法是高度关注的。我们提出并评估一个优雅的卷积神经网络（CNN），用于分割组织图像，特别是Masson三色染色的图像。该网络包含11个连续的卷积校正线性单位批量标准化层，并且在心脏组织学图像（标记的纤维化，肌细胞和背景）的数据集上具有优于最新的CNN，其中Dice相似系数为0.947。我们的CNN减少100次（仅30万次）可训练参数，不易过度拟合，效率高。此外，它还保留了从输入到输出的图像分辨率，捕捉细节细节，并可以顺利地进行端对端培训。据我们所知，这是第一个为有关问题量身定制的深度CNN，并可能扩展到解决类似的分割任务，以促进对病理和临床治疗的调查。

##### URL
[http://arxiv.org/abs/1803.07301](http://arxiv.org/abs/1803.07301)

##### PDF
[http://arxiv.org/pdf/1803.07301](http://arxiv.org/pdf/1803.07301)

