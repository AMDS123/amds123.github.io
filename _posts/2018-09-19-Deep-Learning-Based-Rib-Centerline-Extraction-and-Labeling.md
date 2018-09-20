---
layout: post
title: "Deep Learning Based Rib Centerline Extraction and Labeling"
date: 2018-09-19 09:09:23
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Detection
author: Matthias Lenga, Tobias Klinder, Christian B&#xfc;rger, Jens von Berg, Astrid Franz, Cristian Lorenz
mathjax: true
---

* content
{:toc}

##### Abstract
Automated extraction and labeling of rib centerlines is a typically needed prerequisite for more advanced assisted reading tools that help the radiologist to efficiently inspect all 24 ribs in a CT volume. In this paper, we combine a deep learning-based rib detection with a dedicated centerline extraction algorithm applied to the detection result for the purpose of fast, robust and accurate rib centerline extraction and labeling from CT volumes. More specifically, we first apply a fully convolutional neural network (FCNN) to generate a probability map for detecting the first rib pair, the twelfth rib pair, and the collection of all intermediate ribs. In a second stage, a newly designed centerline extraction algorithm is applied to this multi-label probability map. Finally, the distinct detection of first and twelfth rib separately, allows to derive individual rib labels by simple sorting and counting the detected centerlines. We applied our method to CT volumes from 116 patients which included a variety of different challenges and achieved a centerline accuracy of 0.787 mm with respect to manual centerline annotations.

##### Abstract (translated by Google)
肋骨中心线的自动提取和标记是更先进的辅助阅读工具的通常需要的先决条件，其帮助放射科医师有效地检查CT体积中的所有24个肋骨。在本文中，我们将基于深度学习的肋骨检测与应用于检测结果的专用中心线提取算法相结合，以便快速，稳健和准确地从CT体积中提取和标记肋骨中心线。更具体地，我们首先应用完全卷积神经网络（FCNN）来生成用于检测第一肋骨对，第十二肋骨对以及所有中间肋骨的集合的概率图。在第二阶段，将新设计的中心线提取算法应用于该多标签概率图。最后，分别检测第一和第十二肋骨，允许通过简单的排序和计数检测到的中心线来得出单独的肋骨标签。我们将我们的方法应用于116名患者的CT容量，其中包括各种不同的挑战，并且相对于手动中心线注释，中心线准确度达到0.787 mm。

##### URL
[http://arxiv.org/abs/1809.07082](http://arxiv.org/abs/1809.07082)

##### PDF
[http://arxiv.org/pdf/1809.07082](http://arxiv.org/pdf/1809.07082)

