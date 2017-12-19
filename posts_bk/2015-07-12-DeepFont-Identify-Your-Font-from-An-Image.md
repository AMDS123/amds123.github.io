---
layout: post
title: "DeepFont: Identify Your Font from An Image"
date: 2015-07-12 07:25:14
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Zhangyang Wang, Jianchao Yang, Hailin Jin, Eli Shechtman, Aseem Agarwala, Jonathan Brandt, Thomas S. Huang
mathjax: true
---

* content
{:toc}

##### Abstract
As font is one of the core design concepts, automatic font identification and similar font suggestion from an image or photo has been on the wish list of many designers. We study the Visual Font Recognition (VFR) problem, and advance the state-of-the-art remarkably by developing the DeepFont system. First of all, we build up the first available large-scale VFR dataset, named AdobeVFR, consisting of both labeled synthetic data and partially labeled real-world data. Next, to combat the domain mismatch between available training and testing data, we introduce a Convolutional Neural Network (CNN) decomposition approach, using a domain adaptation technique based on a Stacked Convolutional Auto-Encoder (SCAE) that exploits a large corpus of unlabeled real-world text images combined with synthetic data preprocessed in a specific way. Moreover, we study a novel learning-based model compression approach, in order to reduce the DeepFont model size without sacrificing its performance. The DeepFont system achieves an accuracy of higher than 80% (top-5) on our collected dataset, and also produces a good font similarity measure for font selection and suggestion. We also achieve around 6 times compression of the model without any visible loss of recognition accuracy.

##### Abstract (translated by Google)
由于字体是核心设计概念之一，自动字体识别和图像或照片中的类似字体建议已经被许多设计师的愿望清单列出。我们研究视觉字体识别（VFR）问题，并通过开发DeepFont系统来显着提高现有技术水平。首先，我们建立了第一个可用的大型VFR数据集，命名为AdobeVFR，包含标记的合成数据和部分标记的真实世界数据。接下来，为了打击可用训练和测试数据之间的域不匹配，我们引入卷积神经网络（CNN）分解方法，使用基于堆叠卷积自动编码器（SCAE）的域自适应技术，该技术利用大量未标记实体世界文本图像结合合成数据以特定方式进行预处理。此外，我们研究了一种新的基于学习的模型压缩方法，以减少DeepFont模型的大小而不牺牲其性能。 DeepFont系统在我们收集的数据集上实现了高于80％（前5）的准确性，并且还为字体选择和建议产生了良好的字体相似性度量。我们也实现了约6倍的模型压缩，没有任何明显的识别精度损失。

##### URL
[https://arxiv.org/abs/1507.03196](https://arxiv.org/abs/1507.03196)

##### PDF
[https://arxiv.org/pdf/1507.03196](https://arxiv.org/pdf/1507.03196)

