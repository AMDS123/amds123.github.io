---
layout: post
title: "Do More Dropouts in Pool5 Feature Maps for Better Object Detection"
date: 2014-11-18 17:34:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Image_Classification Classification Detection
author: Zhiqiang Shen, Xiangyang Xue
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks (CNNs) have gained great success in image classification and object detection. In these fields, the outputs of all layers of CNNs are usually considered as a high dimensional feature vector extracted from an input image and the correspondence between finer level feature vectors and concepts that the input image contains is all-important. However, fewer studies focus on this deserving issue. On considering the correspondence, we propose a novel approach which generates an edited version for each original CNN feature vector by applying the maximum entropy principle to abandon particular vectors. These selected vectors correspond to the unfriendly concepts in each image category. The classifier trained from merged feature sets can significantly improve model generalization of individual categories when training data is limited. The experimental results for classification-based object detection on canonical datasets including VOC 2007 (60.1%), 2010 (56.4%) and 2012 (56.3%) show obvious improvement in mean average precision (mAP) with simple linear support vector machines.

##### Abstract (translated by Google)
深度卷积神经网络（CNNs）在图像分类和目标检测方面取得了巨大的成功。在这些领域中，所有CNN层的输出通常被视为从输入图像中提取的高维特征向量，更精细的特征向量与输入图像所包含的概念之间的对应关系是非常重要的。然而，更少的研究关注这个值得注意的问题。在考虑对应关系时，我们提出了一种新的方法，通过应用最大熵原理来放弃特定的向量，为每个原始CNN特征向量生成编辑版本。这些选定的向量对应于每个图像类别中不友好的概念。在训练数据有限的情况下，从合并特征集合训练的分类器可以显着提高各个类别的模型泛化。包括VOC 2007（60.1％），2010（56.4％）和2012（56.3％）在内的典型数据集上的基于分类的对象检测实验结果表明，使用简单的线性支持向量机，均值平均精度（mAP）明显提高。

##### URL
[https://arxiv.org/abs/1409.6911](https://arxiv.org/abs/1409.6911)

##### PDF
[https://arxiv.org/pdf/1409.6911](https://arxiv.org/pdf/1409.6911)

