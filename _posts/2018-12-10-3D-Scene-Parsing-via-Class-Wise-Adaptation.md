---
layout: post
title: "3D Scene Parsing via Class-Wise Adaptation"
date: 2018-12-10 04:53:14
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation SLAM
author: Daichi Ono, Hiroyuki Yabe, Tsutomu Horikawa
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the method that uses only computer graphics datasets to parse the real world 3D scenes. 3D scene parsing based on semantic segmentation is required to implement the categorical interaction in the virtual world. Convolutional Neural Networks (CNNs) have recently shown state-of-theart performance on computer vision tasks including semantic segmentation. However, collecting and annotating a huge amount of data are needed to train CNNs. Especially in the case of semantic segmentation, annotating pixel by pixel takes a significant amount of time and often makes mistakes. In contrast, computer graphics can generate a lot of accurate annotated data and easily scale up by changing camera positions, textures and lights. Despite these advantages, models trained on computer graphics datasets cannot perform well on real data, which is known as the domain shift. To address this issue, we first present that depth modal and synthetic noise are effective to reduce the domain shift. Then, we develop the class-wise adaptation which obtains domain invariant features of CNNs. To reduce the domain shift, we create computer graphics rooms with a lot of props, and provide photo-realistic rendered images.We also demonstrate the application which is combined semantic segmentation with Simultaneous Localization and Mapping (SLAM). Our application performs accurate 3D scene parsing in real-time on an actual room.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03622](http://arxiv.org/abs/1812.03622)

##### PDF
[http://arxiv.org/pdf/1812.03622](http://arxiv.org/pdf/1812.03622)

