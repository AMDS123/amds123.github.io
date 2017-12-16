---
layout: post
title: "Scene Recognition by Combining Local and Global Image Descriptors"
date: 2017-02-21 06:57:37
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Jobin Wilson, Muhammad Arif
mathjax: true
---

* content
{:toc}

##### Abstract
Object recognition is an important problem in computer vision, having diverse applications. In this work, we construct an end-to-end scene recognition pipeline consisting of feature extraction, encoding, pooling and classification. Our approach simultaneously utilize global feature descriptors as well as local feature descriptors from images, to form a hybrid feature descriptor corresponding to each image. We utilize DAISY features associated with key points within images as our local feature descriptor and histogram of oriented gradients (HOG) corresponding to an entire image as a global descriptor. We make use of a bag-of-visual-words encoding and apply Mini- Batch K-Means algorithm to reduce the complexity of our feature encoding scheme. A 2-level pooling procedure is used to combine DAISY and HOG features corresponding to each image. Finally, we experiment with a multi-class SVM classifier with several kernels, in a cross-validation setting, and tabulate our results on the fifteen scene categories dataset. The average accuracy of our model was 76.4% in the case of a 40%-60% random split of images into training and testing datasets respectively. The primary objective of this work is to clearly outline the practical implementation of a basic screne-recognition pipeline having a reasonable accuracy, in python, using open-source libraries. A full implementation of the proposed model is available in our github repository.

##### Abstract (translated by Google)
物体识别是计算机视觉中的一个重要问题，具有多样化的应用。在这项工作中，我们构建了一个由特征提取，编码，合并和分类组成的端到端场景识别流水线。我们的方法同时利用全局特征描述符以及来自图像的局部特征描述符来形成对应于每个图像的混合特征描述符。我们利用与图像中的关键点相关的DAISY特征作为局部特征描述符和与作为全局描述符的整个图像对应的面向梯度（HOG）的直方图。我们利用一种视觉词编码方法，并应用Mini-Batch K-Means算法来降低我们的特征编码方案的复杂度。使用2级池化过程来结合每个图像对应的DAISY和HOG特征。最后，我们在一个交叉验证设置中试验了一个带有几个内核的多类SVM分类器，并将结果列在十五个场景类别数据集上。在将图像随机分为训练和测试数据集的情况下，我们模型的平均准确率为76.4％。这项工作的主要目标是在python中使用开源库清楚地概述具有合理精度的基本screne识别管道的实际实现。我们的github仓库中提供了所提议模型的完整实现。

##### URL
[https://arxiv.org/abs/1702.06850](https://arxiv.org/abs/1702.06850)

##### PDF
[https://arxiv.org/pdf/1702.06850](https://arxiv.org/pdf/1702.06850)

