---
layout: post
title: "Convolutional Neural Networks for Font Classification"
date: 2017-08-11 19:25:44
categories: arXiv_CV
tags: arXiv_CV OCR CNN Classification Prediction Recognition
author: Chris Tensmeyer, Daniel Saunders, Tony Martinez
mathjax: true
---

* content
{:toc}

##### Abstract
Classifying pages or text lines into font categories aids transcription because single font Optical Character Recognition (OCR) is generally more accurate than omni-font OCR. We present a simple framework based on Convolutional Neural Networks (CNNs), where a CNN is trained to classify small patches of text into predefined font classes. To classify page or line images, we average the CNN predictions over densely extracted patches. We show that this method achieves state-of-the-art performance on a challenging dataset of 40 Arabic computer fonts with 98.8\% line level accuracy. This same method also achieves the highest reported accuracy of 86.6% in predicting paleographic scribal script classes at the page level on medieval Latin manuscripts. Finally, we analyze what features are learned by the CNN on Latin manuscripts and find evidence that the CNN is learning both the defining morphological differences between scribal script classes as well as overfitting to class-correlated nuisance factors. We propose a novel form of data augmentation that improves robustness to text darkness, further increasing classification performance.

##### Abstract (translated by Google)
将页面或文本行分类为字体类别有助于转录，因为单字体光学字符识别（OCR）通常比全字体OCR更准确。我们提出了一个基于卷积神经网络（CNN）的简单的框架，在这个框架下，CNN被训练成将小片文本分类成预定义的字体类。为了对页面或线条图像进行分类，我们对密集提取的片上的CNN预测进行平均。我们展示了这种方法在具有98.8％行级精度的40种阿拉伯语计算机字体的具有挑战性的数据集上实现了最先进的性能。同样的方法在中世纪拉丁文手稿的页面级预测古文字书写类也达到了86.6％的最高报告准确率。最后，我们分析了CNN在拉丁文手稿上学到了哪些特征，并发现CNN正在学习文本划分类别之间的定义形态差异，以及过度拟合类别相关的妨碍因素。我们提出了一种新的数据增强形式，可以提高文本黑度的鲁棒性，进一步提高分类性能。

##### URL
[https://arxiv.org/abs/1708.03669](https://arxiv.org/abs/1708.03669)

##### PDF
[https://arxiv.org/pdf/1708.03669](https://arxiv.org/pdf/1708.03669)

