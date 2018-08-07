---
layout: post
title: "MAT: A Multimodal Attentive Translator for Image Captioning"
date: 2017-08-10 14:29:19
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption CNN RNN
author: Chang Liu, Fuchun Sun, Changhu Wang, Feng Wang, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we formulate the problem of image captioning as a multimodal translation task. Analogous to machine translation, we present a sequence-to-sequence recurrent neural networks (RNN) model for image caption generation. Different from most existing work where the whole image is represented by convolutional neural network (CNN) feature, we propose to represent the input image as a sequence of detected objects which feeds as the source sequence of the RNN model. In this way, the sequential representation of an image can be naturally translated to a sequence of words, as the target sequence of the RNN model. To represent the image in a sequential way, we extract the objects features in the image and arrange them in a order using convolutional neural networks. To further leverage the visual information from the encoded objects, a sequential attention layer is introduced to selectively attend to the objects that are related to generate corresponding words in the sentences. Extensive experiments are conducted to validate the proposed approach on popular benchmark dataset, i.e., MS COCO, and the proposed model surpasses the state-of-the-art methods in all metrics following the dataset splits of previous work. The proposed approach is also evaluated by the evaluation server of MS COCO captioning challenge, and achieves very competitive results, e.g., a CIDEr of 1.029 (c5) and 1.064 (c40).

##### Abstract (translated by Google)
在这项工作中，我们将图像字幕问题表述为多模式翻译任务。类似于机器翻译，我们提出了用于图像标题生成的序列到序列的递归神经网络（RNN）模型。与通过卷积神经网络（CNN）特征表示整个图像的大多数现有工作不同，我们建议将输入图像表示为检测到的对象序列，其作为RNN模型的源序列馈送。以这种方式，图像的顺序表示可以自然地转换为单词序列，作为RNN模型的目标序列。为了以顺序方式表示图像，我们提取图像中的对象特征，并使用卷积神经网络按顺序排列它们。为了进一步利用来自编码对象的视觉信息，引入顺序关注层以选择性地处理与生成句子中的对应单词相关的对象。进行了广泛的实验以验证在流行的基准数据集（即MS COCO）上提出的方法，并且所提出的模型在先前工作的数据集拆分之后的所有度量中超过了最先进的方法。所提出的方法还由评估服务器评估MS COCO字幕挑战，并且实现非常有竞争力的结果，例如，CIDEr为1.029（c5）和1.064（c40）。

##### URL
[https://arxiv.org/abs/1702.05658](https://arxiv.org/abs/1702.05658)

##### PDF
[https://arxiv.org/pdf/1702.05658](https://arxiv.org/pdf/1702.05658)

