---
layout: post
title: "A dynamic graph-cuts method with integrated multiple feature maps for segmenting kidneys in ultrasound images"
date: 2017-06-11 16:17:51
categories: arXiv_CV
tags: arXiv_CV Segmentation Quantitative
author: Qiang Zheng, Steven Warner, Gregory Tasian, Yong Fan
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: To improve kidney segmentation in clinical ultrasound (US) images, we develop a new graph cuts based method to segment kidney US images by integrating original image intensity information and texture feature maps extracted using Gabor filters. Methods: To handle large appearance variation within kidney images and improve computational efficiency, we build a graph of image pixels close to kidney boundary instead of building a graph of the whole image. To make the kidney segmentation robust to weak boundaries, we adopt localized regional information to measure similarity between image pixels for computing edge weights to build the graph of image pixels. The localized graph is dynamically updated and the GC based segmentation iteratively progresses until convergence. The proposed method has been evaluated and compared with state of the art image segmentation methods based on clinical kidney US images of 85 subjects. We randomly selected US images of 20 subjects as training data for tuning the parameters, and validated the methods based on US images of the remaining 65 subjects. The segmentation results have been quantitatively analyzed using 3 metrics, including Dice Index, Jaccard Index, and Mean Distance. Results: Experiment results demonstrated that the proposed method obtained segmentation results for bilateral kidneys of 65 subjects with average Dice index of 0.9581, Jaccard index of 0.9204, and Mean Distance of 1.7166, better than other methods under comparison (p<10-19, paired Wilcoxon rank sum tests). Conclusions: The proposed method achieved promising performance for segmenting kidneys in US images, better than segmentation methods that built on any single channel of image information. This method will facilitate extraction of kidney characteristics that may predict important clinical outcomes such progression chronic kidney disease.

##### Abstract (translated by Google)
目的：为了改善临床超声（US）图像中的肾脏分割，我们开发了一种新的基于图形切割的方法，通过整合原始图像强度信息和使用Gabor滤波器提取的纹理特征图来分割肾脏US图像。方法：为了处理肾脏图像中的大的外观变化并提高计算效率，我们建立一个靠近肾脏边界的图像像素的图形，而不是建立整个图像的图形。为了使肾脏分割对弱边界具有鲁棒性，我们采用局部区域信息来测量图像像素之间的相似性，以计算边缘权值以建立图像像素图。局部图被动态地更新，并且基于GC的分割迭代地进行直到收敛。所提出的方法已经被评估并且与基于85名受试者的临床肾脏US图像的现有技术的图像分割方法进行比较。我们随机选取20个主题的美国图像作为调整参数的训练数据，并根据其余65个主题的美国图像验证方法。分割结果已经使用3个度量进行了定量分析，包括骰子指数，Jaccard指数和平均距离。结果：实验结果表明，所提出的方法获得了65名受试者双侧肾脏的分割结果，平均骰子指数为0.9581，Jaccard指数为0.9204，平均距离为1.7166，优于其他比较方法（p <10-19，成对Wilcoxon秩和检验）。结论：所提出的方法在美国图像中分割肾脏方面取得了有希望的性能，优于在任何单一图像信息通道上构建的分割方法。这种方法将有助于提取肾脏特征，可以预测重要的临床结果，如进展慢性肾脏疾病。

##### URL
[https://arxiv.org/abs/1706.03372](https://arxiv.org/abs/1706.03372)

##### PDF
[https://arxiv.org/pdf/1706.03372](https://arxiv.org/pdf/1706.03372)

