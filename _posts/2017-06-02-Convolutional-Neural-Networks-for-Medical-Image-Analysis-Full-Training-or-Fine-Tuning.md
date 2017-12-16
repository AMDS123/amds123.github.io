---
layout: post
title: "Convolutional Neural Networks for Medical Image Analysis: Full Training or Fine Tuning?"
date: 2017-06-02 15:04:43
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Classification Detection
author: Nima Tajbakhsh, Jae Y. Shin, Suryakanth R. Gurudu, R. Todd Hurst, Christopher B. Kendall, Michael B. Gotway, Jianming Liang
mathjax: true
---

* content
{:toc}

##### Abstract
Training a deep convolutional neural network (CNN) from scratch is difficult because it requires a large amount of labeled training data and a great deal of expertise to ensure proper convergence. A promising alternative is to fine-tune a CNN that has been pre-trained using, for instance, a large set of labeled natural images. However, the substantial differences between natural and medical images may advise against such knowledge transfer. In this paper, we seek to answer the following central question in the context of medical image analysis: \emph{Can the use of pre-trained deep CNNs with sufficient fine-tuning eliminate the need for training a deep CNN from scratch?} To address this question, we considered 4 distinct medical imaging applications in 3 specialties (radiology, cardiology, and gastroenterology) involving classification, detection, and segmentation from 3 different imaging modalities, and investigated how the performance of deep CNNs trained from scratch compared with the pre-trained CNNs fine-tuned in a layer-wise manner. Our experiments consistently demonstrated that (1) the use of a pre-trained CNN with adequate fine-tuning outperformed or, in the worst case, performed as well as a CNN trained from scratch; (2) fine-tuned CNNs were more robust to the size of training sets than CNNs trained from scratch; (3) neither shallow tuning nor deep tuning was the optimal choice for a particular application; and (4) our layer-wise fine-tuning scheme could offer a practical way to reach the best performance for the application at hand based on the amount of available data.

##### Abstract (translated by Google)
从零开始训练深度卷积神经网络（CNN）是很困难的，因为它需要大量标记的训练数据和大量的专业知识来确保正确的收敛。一个有希望的替代方法是微调已经预先训练的CNN，例如使用大量标记的自然图像。然而，自然和医学图像之间的实质性差异可能会对这种知识转移提出建议。在本文中，我们试图在医学图像分析的背景下回答以下核心问题：能够使用预先训练的深度CNNs进行充分的微调，从而无需从头开始深入训练CNN？为了解决这个问题，我们考虑了3个专业（放射学，心脏病学和胃肠病学）的4种不同的医学成像应用，涉及3种不同成像方式的分类，检测和分割，并且研究了从零开始训练的深CNN的表现受过训练的CNN以分层方式进行微调。我们的实验始终如一地表明：（1）使用预先训练的CNN进行适当的微调，或者在最坏的情况下，以及从头开始训练的CNN; （2）经过微调的CNN比训练集的规模更强大，而不是从零开始训练的CNN; （3）对于特定的应用来说，浅调和深调都不是最佳选择; （4）我们的分层微调方案可以提供一种实用的方法，以根据可用数据量为手中的应用程序实现最佳性能。

##### URL
[https://arxiv.org/abs/1706.00712](https://arxiv.org/abs/1706.00712)

##### PDF
[https://arxiv.org/pdf/1706.00712](https://arxiv.org/pdf/1706.00712)

