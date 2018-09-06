---
layout: post
title: "Bimodal network architectures for automatic generation of image annotation from text"
date: 2018-09-05 16:30:08
categories: arXiv_CV
tags: arXiv_CV Segmentation RNN Detection
author: Mehdi Moradi, Ali Madani, Yaniv Gur, Yufan Guo, Tanveer Syeda-Mahmood
mathjax: true
---

* content
{:toc}

##### Abstract
Medical image analysis practitioners have embraced big data methodologies. This has created a need for large annotated datasets. The source of big data is typically large image collections and clinical reports recorded for these images. In many cases, however, building algorithms aimed at segmentation and detection of disease requires a training dataset with markings of the areas of interest on the image that match with the described anomalies. This process of annotation is expensive and needs the involvement of clinicians. In this work we propose two separate deep neural network architectures for automatic marking of a region of interest (ROI) on the image best representing a finding location, given a textual report or a set of keywords. One architecture consists of LSTM and CNN components and is trained end to end with images, matching text, and markings of ROIs for those images. The output layer estimates the coordinates of the vertices of a polygonal region. The second architecture uses a network pre-trained on a large dataset of the same image types for learning feature representations of the findings of interest. We show that for a variety of findings from chest X-ray images, both proposed architectures learn to estimate the ROI, as validated by clinical annotations. There is a clear advantage obtained from the architecture with pre-trained imaging network. The centroids of the ROIs marked by this network were on average at a distance equivalent to 5.1% of the image width from the centroids of the ground truth ROIs.

##### Abstract (translated by Google)
医学图像分析从业者已经采用了大数据方法。这产生了对大注释数据集的需求。大数据的来源通常是为这些图像记录的大型图像集和临床报告。然而，在许多情况下，构建旨在分割和检测疾病的算法需要训练数据集，其具有与所描述的异常匹配的图像上感兴趣区域的标记。这种注释过程很昂贵，需要临床医生的参与。在这项工作中，我们提出了两个独立的深度神经网络架构，用于在给定文本报告或一组关键字的最佳表示发现位置的图像上自动标记感兴趣区域（ROI）。一种架构由LSTM和CNN组件组成，并且端到端地训练图像，匹配文本以及这些图像的ROI标记。输出层估计多边形区域的顶点的坐标。第二种体系结构使用在相同图像类型的大数据集上预训练的网络来学习感兴趣的发现的特征表示。我们表明，对于来自胸部X射线图像的各种发现，两种建议的体系结构都学会估计ROI，如临床注释验证的那样。从具有预训练成像网络的架构中获得明显的优势。由该网络标记的ROI的质心平均距离相当于来自地面实况ROI的质心的图像宽度的5.1％。

##### URL
[http://arxiv.org/abs/1809.01610](http://arxiv.org/abs/1809.01610)

##### PDF
[http://arxiv.org/pdf/1809.01610](http://arxiv.org/pdf/1809.01610)

