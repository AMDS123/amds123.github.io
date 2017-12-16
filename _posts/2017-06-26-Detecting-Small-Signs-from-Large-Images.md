---
layout: post
title: "Detecting Small Signs from Large Images"
date: 2017-06-26 19:42:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Zibo Meng, Xiaochuan Fan, Xin Chen, Min Chen, Yan Tong
mathjax: true
---

* content
{:toc}

##### Abstract
In the past decade, Convolutional Neural Networks (CNNs) have been demonstrated successful for object detections. However, the size of network input is limited by the amount of memory available on GPUs. Moreover, performance degrades when detecting small objects. To alleviate the memory usage and improve the performance of detecting small traffic signs, we proposed an approach for detecting small traffic signs from large images under real world conditions. In particular, large images are broken into small patches as input to a Small-Object-Sensitive-CNN (SOS-CNN) modified from a Single Shot Multibox Detector (SSD) framework with a VGG-16 network as the base network to produce patch-level object detection results. Scale invariance is achieved by applying the SOS-CNN on an image pyramid. Then, image-level object detection is obtained by projecting all the patch-level detection results to the image at the original scale. Experimental results on a real-world conditioned traffic sign dataset have demonstrated the effectiveness of the proposed method in terms of detection accuracy and recall, especially for those with small sizes.

##### Abstract (translated by Google)
在过去的十年中，卷积神经网络（CNN）已经被证明是成功的。但是，网络输入的大小受到GPU上可用内存量的限制。此外，检测小物体时性能下降。为了减轻内存使用量，提高小型交通标志检测的性能，本文提出了一种在实际环境下检测大型图像小型交通标志的方法。特别地，将大图像分割成小块，作为输入到以VGG-16网络为基础网络的单发多盒检测器（SSD）框架修改的小物体敏感CNN（SOS-CNN），以产生补丁级别的对象检测结果。通过在图像金字塔上应用SOS-CNN来实现尺度不变性。然后，通过将所有的小片级检测结果以原始尺度投影到图像上来获得图像级别的目标检测。在真实世界的条件交通标志数据集上的实验结果证明了所提出的方法在检测精度和召回率方面的有效性，特别是对于那些尺寸较小的方法。

##### URL
[https://arxiv.org/abs/1706.08574](https://arxiv.org/abs/1706.08574)

##### PDF
[https://arxiv.org/pdf/1706.08574](https://arxiv.org/pdf/1706.08574)

