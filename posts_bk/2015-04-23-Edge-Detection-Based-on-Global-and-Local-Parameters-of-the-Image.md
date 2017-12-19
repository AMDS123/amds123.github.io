---
layout: post
title: "Edge Detection Based on Global and Local Parameters of the Image"
date: 2015-04-23 04:11:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Andrew F. C. Brustolin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an edge detection method based on global and local parameters of the image, which produces satisfactory results on the edge detection of complex images and has a simple structure for execution. The local and global parameters of the image are arithmetic means and standard deviations, the former acquired from a three sized window representing five pixels, the latter acquired from the entire row or column. We obtain the differences of grayscale intensities between two adjacent pixels and the sum of the modulus of these differences from the horizontal and vertical scans of the image. Using these obtained values, we calculate the local and global parameters. After the gathering of the local and global parameters, we compare each sum of the modulus of differences with its own local and global parameter. In the case of the comparison is true, the consecutive pixel to the modulus sum of differences index is marked as an edge. We present the results of the tests with grayscale images using different parameters and discuss the advantages and disadvantages of each parameter value and algorithm structure chosen on the edge processing. There is a comparison of results between this papers detector and Canny, where we evaluate the quality of the presented detector.

##### Abstract (translated by Google)
本文提出了一种基于图像全局和局部参数的边缘检测方法，在复杂图像边缘检测方面取得了令人满意的结果，并且具有简单的执行结构。图像的局部和全局参数是算术平均值和标准偏差，前者是从代表五个像素的三个窗口获得的，后者是从整个行或列中获取的。我们获得了两个相邻像素之间灰度强度的差异以及这些差异与图像水平和垂直扫描的模数之和。使用这些获得的值，我们计算本地和全局参数。在收集了局部参数和全局参数之后，我们将差值模数的每个和与它自己的局部参数和全局参数进行比较。在比较为真的情况下，连续像素与模糊和的差异指数被标记为边缘。我们用不同参数的灰度图像给出了测试结果，讨论了在边缘处理中选择的每个参数值和算法结构的优缺点。这篇论文的探测器和Canny的结果有一个比较，在那里我们评估了探测器的质量。

##### URL
[https://arxiv.org/abs/1504.06036](https://arxiv.org/abs/1504.06036)

##### PDF
[https://arxiv.org/pdf/1504.06036](https://arxiv.org/pdf/1504.06036)

