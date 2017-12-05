---
layout: post
title: 'MAT: A Multimodal Attentive Translator for Image Captioning'
date: 2017-12-06 02:46:07
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption
author: Chang Liu, Fuchun Sun, Changhu Wang, Feng Wang, Alan Yuille
---

* content
{:toc}

##### Abstract
In this work we formulate the problem of image captioning as a multimodal translation task. Analogous to machine translation, we present a sequence-to-sequence recurrent neural networks (RNN) model for image caption generation. Different from most existing work where the whole image is represented by convolutional neural network (CNN) feature, we propose to represent the input image as a sequence of detected objects which feeds as the source sequence of the RNN model. In this way, the sequential representation of an image can be naturally translated to a sequence of words, as the target sequence of the RNN model. To represent the image in a sequential way, we extract the objects features in the image and arrange them in a order using convolutional neural networks. To further leverage the visual information from the encoded objects, a sequential attention layer is introduced to selectively attend to the objects that are related to generate corresponding words in the sentences. Extensive experiments are conducted to validate the proposed approach on popular benchmark dataset, i.e., MS COCO, and the proposed model surpasses the state-of-the-art methods in all metrics following the dataset splits of previous work. The proposed approach is also evaluated by the evaluation server of MS COCO captioning challenge, and achieves very competitive results, e.g., a CIDEr of 1.029 (c5) and 1.064 (c40).

##### Abstract (translated by Google)
在这项工作中，我们将图像字幕作为多模式翻译任务来制定。类似于机器翻译，我们提出了用于图像字幕生成的序列 - 序列递归神经网络（RNN）模型。与大多数现有的以卷积神经网络（CNN）特征表示整个图像的工作不同，我们提出将输入图像表示为RNN模型源序列的检测对象序列。通过这种方式，图像的顺序表示可以被自然地翻译成一个单词序列，作为RNN模型的目标序列。为了以连续的方式表示图像，我们提取图像中的对象特征，并使用卷积神经网络按顺序排列它们。为了进一步利用来自编码对象的视觉信息，引入顺序关注层来选择性地关注与在句子中生成对应词相关的对象。进行了大量的实验来验证在流行的基准数据集（即，COCO）上提出的方法，并且所提出的模型超越了先前工作的数据集拆分之后的所有度量中的最先进的方法。所提出的方法也由MS COCO字幕挑战的评估服务器评估，并且获得了非常有竞争力的结果，例如1.029（c5）和1.064（c40）的CIDEr。

##### URL
[https://arxiv.org/abs/1702.05658](https://arxiv.org/abs/1702.05658)

