---
layout: post
title: "Abnormality Detection in Mammography using Deep Convolutional Neural Networks"
date: 2018-03-05 20:04:56
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Pengcheng Xi, Chang Shu, Rafik Goubran
mathjax: true
---

* content
{:toc}

##### Abstract
Breast cancer is the most common cancer in women worldwide. The most common screening technology is mammography. To reduce the cost and workload of radiologists, we propose a computer aided detection approach for classifying and localizing calcifications and masses in mammogram images. To improve on conventional approaches, we apply deep convolutional neural networks (CNN) for automatic feature learning and classifier building. In computer-aided mammography, deep CNN classifiers cannot be trained directly on full mammogram images because of the loss of image details from resizing at input layers. Instead, our classifiers are trained on labelled image patches and then adapted to work on full mammogram images for localizing the abnormalities. State-of-the-art deep convolutional neural networks are compared on their performance of classifying the abnormalities. Experimental results indicate that VGGNet receives the best overall accuracy at 92.53\% in classifications. For localizing abnormalities, ResNet is selected for computing class activation maps because it is ready to be deployed without structural change or further training. Our approach demonstrates that deep convolutional neural network classifiers have remarkable localization capabilities despite no supervision on the location of abnormalities is provided.

##### Abstract (translated by Google)
乳腺癌是全世界女性最常见的癌症。最常见的筛查技术是乳房摄影。为了降低放射科医生的成本和工作量，我们提出了一种计算机辅助检测方法，用于对乳房X线照片图像中的钙化和肿块进行分类和定位。为了改进传统方法，我们将深度卷积神经网络（CNN）应用于自动特征学习和分类器构建。在计算机辅助乳房X线照相术中，深层CNN分类器不能直接在完整的乳房X线照片图像上进行训练，因为输入层调整图像细节丢失。相反，我们的分类器接受过标记图像补丁的训练，然后适用于完整乳房X线照片图像以定位异常。最先进的深度卷积神经网络比较它们对异常进行分类的性能。实验结果表明，VGGNet在分类中获得了92.53％的最佳整体精度。为了定位异常，ResNet被选择用于计算类别激活地图，因为它已准备好进行部署，无需进行结构改变或进一步培训。我们的方法表明，深卷积神经网络分类器具有显着的定位能力，尽管没有提供异常位置的监督。

##### URL
[http://arxiv.org/abs/1803.01906](http://arxiv.org/abs/1803.01906)

##### PDF
[http://arxiv.org/pdf/1803.01906](http://arxiv.org/pdf/1803.01906)

