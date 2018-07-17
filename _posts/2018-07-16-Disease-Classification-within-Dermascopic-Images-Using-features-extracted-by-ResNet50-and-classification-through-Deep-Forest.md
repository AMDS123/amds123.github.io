---
layout: post
title: "Disease Classification within Dermascopic Images Using features extracted by ResNet50 and classification through Deep Forest"
date: 2018-07-16 07:57:31
categories: arXiv_CV
tags: arXiv_CV Face CNN Represenation_Learning Classification Detection
author: Sounak Ray
mathjax: true
---

* content
{:toc}

##### Abstract
In this report we propose a classification technique for skin lesion images as a part of our submission for ISIC 2018 Challenge in Skin Lesion Analysis Towards Melanoma Detection. Our data was extracted from the ISIC 2018: Skin Lesion Analysis Towards Melanoma Detection grand challenge datasets. The features are extracted through a Convolutional Neural Network, in our case ResNet50 and then using these features we train a DeepForest, having cascading layers, to classify our skin lesion images. We know that Convolutional Neural Networks are a state-of-the-art technique in representation learning for images, with the convolutional filters learning to detect features from images through backpropagation. These features are then usually fed to a classifier like a softmax layer or other such classifiers for classification tasks. In our case we do not use the traditional backpropagation method and train a softmax layer for classification. Instead, we use Deep Forest, a novel decision tree ensemble approach with performance highly competitive to deep neural networks in a broad range of tasks. Thus we use a ResNet50 to extract the features from skin lesion images and then use the Deep Forest to classify these images. This method has been used because Deep Forest has been found to be hugely efficient in areas where there are only small-scale training data available. Also as the Deep Forest network decides its complexity by itself, it also caters to the problem of dataset imbalance we faced in this problem.

##### Abstract (translated by Google)
在本报告中，我们提出了皮肤病变图像的分类技术，作为我们提交的ISIC 2018皮肤病变分析中针对黑色素瘤检测的挑战的一部分。我们的数据来自ISIC 2018：皮肤病变分析，针对黑色素瘤检测大挑战数据集。这些特征是通过卷积神经网络提取的，在我们的案例中是ResNet50，然后使用这些特征我们训练一个具有级联层的DeepForest来对我们的皮肤病变图像进行分类。我们知道卷积神经网络是图像表示学习中最先进的技术，卷积滤波器学习通过反向传播从图像中检测特征。然后，这些特征通常被馈送到分类器，例如softmax层或用于分类任务的其他这样的分类器。在我们的例子中，我们不使用传统的反向传播方法并训练softmax层进行分类。相反，我们使用Deep Forest，一种新颖的决策树集合方法，其性能与广泛的任务中的深度神经网络具有高度竞争性。因此，我们使用ResNet50从皮肤病变图像中提取特征，然后使用深森林对这些图像进行分类。使用这种方法是因为深森林在只有小规模培训数据的地区被发现非常有效。此外，由于深林网络自身决定其复杂性，它也迎合了我们在这个问题中遇到的数据集不平衡问题。

##### URL
[http://arxiv.org/abs/1807.05711](http://arxiv.org/abs/1807.05711)

##### PDF
[http://arxiv.org/pdf/1807.05711](http://arxiv.org/pdf/1807.05711)

