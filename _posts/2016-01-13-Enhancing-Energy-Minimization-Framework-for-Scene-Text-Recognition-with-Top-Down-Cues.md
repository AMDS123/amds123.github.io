---
layout: post
title: "Enhancing Energy Minimization Framework for Scene Text Recognition with Top-Down Cues"
date: 2016-01-13 04:47:28
categories: arXiv_CV
tags: arXiv_CV Attention CNN Deep_Learning Detection Recognition
author: Anand Mishra, Karteek Alahari, C. V. Jawahar
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing scene text is a challenging problem, even more so than the recognition of scanned documents. This problem has gained significant attention from the computer vision community in recent years, and several methods based on energy minimization frameworks and deep learning approaches have been proposed. In this work, we focus on the energy minimization framework and propose a model that exploits both bottom-up and top-down cues for recognizing cropped words extracted from street images. The bottom-up cues are derived from individual character detections from an image. We build a conditional random field model on these detections to jointly model the strength of the detections and the interactions between them. These interactions are top-down cues obtained from a lexicon-based prior, i.e., language statistics. The optimal word represented by the text image is obtained by minimizing the energy function corresponding to the random field model. We evaluate our proposed algorithm extensively on a number of cropped scene text benchmark datasets, namely Street View Text, ICDAR 2003, 2011 and 2013 datasets, and IIIT 5K-word, and show better performance than comparable methods. We perform a rigorous analysis of all the steps in our approach and analyze the results. We also show that state-of-the-art convolutional neural network features can be integrated in our framework to further improve the recognition performance.

##### Abstract (translated by Google)
识别场景文本是一个具有挑战性的问题，甚至比识别扫描的文档更重要。这个问题近年来受到计算机视觉界的重视，提出了几种基于能量最小化框架和深度学习方法的方法。在这项工作中，我们专注于能量最小化框架，并提出了一个模型，利用自下而上和自上而下的线索来识别从街道图像中提取的裁剪的单词。自下而上的暗示来源于图像中的单个字符检测。我们在这些检测上建立一个条件随机场模型来联合建模检测的强度和它们之间的相互作用。这些相互作用是从基于词典的先前的，即语言统计得到的自上而下的线索。由文本图像表示的最佳词是通过最小化对应于随机场模型的能量函数而获得的。我们在许多裁剪的场景文本基准数据集（即街景文本，ICDAR 2003,2011和2013数据集和IIIT 5K字）上广泛地评估了我们的算法，并且表现出比类似方法更好的性能。我们对我们的方法中的所有步骤进行严格的分析，并分析结果。我们还表明，最先进的卷积神经网络特征可以被集成在我们的框架中，以进一步提高识别性能。

##### URL
[https://arxiv.org/abs/1601.03128](https://arxiv.org/abs/1601.03128)

##### PDF
[https://arxiv.org/pdf/1601.03128](https://arxiv.org/pdf/1601.03128)

