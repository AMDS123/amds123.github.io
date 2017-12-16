---
layout: post
title: "Visual attention models for scene text recognition"
date: 2017-06-05 18:34:37
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention CNN RNN Language_Model Recognition
author: Suman K.Ghosh, Ernest Valveny, Andrew D. Bagdanov
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose an approach to lexicon-free recognition of text in scene images. Our approach relies on a LSTM-based soft visual attention model learned from convolutional features. A set of feature vectors are derived from an intermediate convolutional layer corresponding to different areas of the image. This permits encoding of spatial information into the image representation. In this way, the framework is able to learn how to selectively focus on different parts of the image. At every time step the recognizer emits one character using a weighted combination of the convolutional feature vectors according to the learned attention model. Training can be done end-to-end using only word level annotations. In addition, we show that modifying the beam search algorithm by integrating an explicit language model leads to significantly better recognition results. We validate the performance of our approach on standard SVT and ICDAR'03 scene text datasets, showing state-of-the-art performance in unconstrained text recognition.

##### Abstract (translated by Google)
在本文中，我们提出了一种在场景图像中对文本进行无词汇识别的方法。我们的方法依赖于从卷积特征中学习的基于LSTM的软视觉关注模型。从与图像的不同区域相对应的中间卷积层导出一组特征向量。这允许将空间信息编码成图像表示。这样，框架就能够学习如何选择性地关注图像的不同部分。在每个时间步骤，识别器根据学习的关注模型，使用卷积特征向量的加权组合发出一个字符。只能使用单词级别的注释进行端到端的培训。另外，我们还发现通过整合明确的语言模型来修改波束搜索算法会导致更好的识别结果。我们验证了我们的方法在标准SVT和ICDAR'03场景文本数据集上的性能，显示了无约束文本识别中的最新性能。

##### URL
[https://arxiv.org/abs/1706.01487](https://arxiv.org/abs/1706.01487)

##### PDF
[https://arxiv.org/pdf/1706.01487](https://arxiv.org/pdf/1706.01487)

