---
layout: post
title: "Deep Learning Improves Template Matching by Normalized Cross Correlation"
date: 2017-05-24 03:24:25
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Relation
author: Davit Buniatyan, Thomas Macrina, Dodam Ih, Jonathan Zung, H. Sebastian Seung
mathjax: true
---

* content
{:toc}

##### Abstract
Template matching by normalized cross correlation (NCC) is widely used for finding image correspondences. We improve the robustness of this algorithm by preprocessing images with "siamese" convolutional networks trained to maximize the contrast between NCC values of true and false matches. The improvement is quantified using patches of brain images from serial section electron microscopy. Relative to a parameter-tuned bandpass filter, siamese convolutional networks significantly reduce false matches. Furthermore, all false matches can be eliminated by removing a tiny fraction of all matches based on NCC values. The improved accuracy of our method could be essential for connectomics, because emerging petascale datasets may require billions of template matches to assemble 2D images of serial sections into a 3D image stack. Our method is also expected to generalize to many other computer vision applications that use NCC template matching to find image correspondences.

##### Abstract (translated by Google)
通过归一化互相关（NCC）的模板匹配被广泛用于寻找图像对应。我们通过用“连体”卷积网络对图像进行预处理来提高该算法的鲁棒性，所述卷积网络被训练为最大化真假匹配的NCC值之间的对比度。使用来自连续切片电子显微镜的大脑图像斑块来量化改善。相对于参数调谐的带通滤波器，连体卷积网络大大减少了错误的匹配。而且，所有的错误匹配可以通过基于NCC值去除所有匹配的一小部分来消除。我们的方法的精度提高对于连接组学来说可能是必不可少的，因为新出现的千万亿次数据集可能需要数十亿的模板匹配才能将连续部分的二维图像组装成三维图像堆栈。我们的方法也有望推广到许多其他使用NCC模板匹配查找图像对应的计算机视觉应用。

##### URL
[https://arxiv.org/abs/1705.08593](https://arxiv.org/abs/1705.08593)

##### PDF
[https://arxiv.org/pdf/1705.08593](https://arxiv.org/pdf/1705.08593)

