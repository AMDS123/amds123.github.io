---
layout: post
title: "Color and Gradient Features for Text Segmentation from Video Frames"
date: 2017-08-22 11:10:57
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Recognition
author: P. Shivakumara, D. S. Guru, H.T. Basavaraju
mathjax: true
---

* content
{:toc}

##### Abstract
Text segmentation in a video is drawing attention of researchers in the field of image processing, pattern recognition and document image analysis because it helps in annotating and labeling video events accurately. We propose a novel idea of generating an enhanced frame from the R, G, and B channels of an input frame by grouping high and low values using Min-Max clustering criteria. We also perform sliding window on enhanced frame to group high and low values from the neighboring pixel values to further enhance the frame. Subsequently, we use k-means with k=2 clustering algorithm to separate text and non-text regions. The fully connected components will be identified in the skeleton of the frame obtained by k-means clustering. Concept of connected component analysis based on gradient feature has been adapted for the purpose of symmetry verification. The components which satisfy symmetric verification are selected to be the representatives of text regions and they are permitted to grow to cover their respective region fully containing text. The method is tested on variety of video frames to evaluate the performance of the method in terms of recall, precision and f-measure. The results show that method is promising and encouraging.

##### Abstract (translated by Google)
视频中的文本分割引起了图像处理，模式识别和文档图像分析领域的研究人员的注意，因为它有助于准确地标注和标记视频事件。我们提出了一种新颖的思想，即通过使用Min-Max聚类标准对高，低值进行分组，从输入帧的R，G和B通道生成增强帧。我们还在增强帧上执行滑动窗口，以将来自相邻像素值的高值和低值分组以进一步增强帧。随后，我们使用k-means和k = 2的聚类算法分离文本和非文本区域。完全连接的组件将在通过k均值聚类获得的帧的骨架中被识别。基于梯度特征的连通分量分析的概念已被用于对称验证的目的。满足对称验证的组件被选择为文本区域的代表，并且允许它们扩展以覆盖其各自包含文本的区域。该方法在各种视频帧上进行测试，以评估方法在召回率，精度和f-measure方面的性能。结果表明，该方法是有前途的和令人鼓舞的。

##### URL
[https://arxiv.org/abs/1708.06561](https://arxiv.org/abs/1708.06561)

##### PDF
[https://arxiv.org/pdf/1708.06561](https://arxiv.org/pdf/1708.06561)

