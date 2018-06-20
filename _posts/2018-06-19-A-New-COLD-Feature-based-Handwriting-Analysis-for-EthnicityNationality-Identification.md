---
layout: post
title: "A New COLD Feature based Handwriting Analysis for Ethnicity/Nationality Identification"
date: 2018-06-19 07:14:54
categories: arXiv_AI
tags: arXiv_AI
author: Sauradip Nag, Palaiahnakote Shivakumara, Wu Yirui, Umapada Pal, Tong Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Identifying crime for forensic investigating teams when crimes involve people of different nationals is challenging. This paper proposes a new method for ethnicity (nationality) identification based on Cloud of Line Distribution (COLD) features of handwriting components. The proposed method, at first, explores tangent angle for the contour pixels in each row and the mean of intensity values of each row in an image for segmenting text lines. For segmented text lines, we use tangent angle and direction of base lines to remove rule lines in the image. We use polygonal approximation for finding dominant points for contours of edge components. Then the proposed method connects the nearest dominant points of every dominant point, which results in line segments of dominant point pairs. For each line segment, the proposed method estimates angle and length, which gives a point in polar domain. For all the line segments, the proposed method generates dense points in polar domain, which results in COLD distribution. As character component shapes change, according to nationals, the shape of the distribution changes. This observation is extracted based on distance from pixels of distribution to Principal Axis of the distribution. Then the features are subjected to an SVM classifier for identifying nationals. Experiments are conducted on a complex dataset, which show the proposed method is effective and outperforms the existing method

##### Abstract (translated by Google)
当犯罪涉及不同国籍的人时，为法医调查小组确定犯罪行为具有挑战性。本文提出了一种基于手写组件的线性分布云（COLD）特征的种族（国籍）识别新方法。所提出的方法首先探索每行中的轮廓像素的切线角以及图像中每行的强度值的平均值以用于分割文本行。对于分段文本行，我们使用基线的切线角度和方向来删除图像中的规则行。我们使用多边形近似来寻找边缘分量轮廓的主要点。然后，所提出的方法连接每个主导点的最接近的主导点，这导致主导点对的线段。对于每个线段，所提出的方法估计角度和长度，这在极性域中给出一个点。对于所有线段，所提出的方法在极性域中产生稠密点，这导致COLD分布。随着角色成分形状的变化，根据国民的不同，分布的形状也会发生变化。根据分布像素到分布的主轴的距离提取此观察值。然后这些特征受到用于识别国民的SVM分类器的支配。实验是在一个复杂的数据集上进行的，这表明所提出的方法是有效的，并且胜过了现有的方法

##### URL
[http://arxiv.org/abs/1806.07072](http://arxiv.org/abs/1806.07072)

##### PDF
[http://arxiv.org/pdf/1806.07072](http://arxiv.org/pdf/1806.07072)

