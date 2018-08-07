---
layout: post
title: "Deep Interactive Region Segmentation and Captioning"
date: 2017-07-26 10:40:33
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Knowledge Segmentation Caption CNN Deep_Learning Detection
author: Ali Sharifi Boroujerdi, Maryam Khanian, Michael Breuss
mathjax: true
---

* content
{:toc}

##### Abstract
With recent innovations in dense image captioning, it is now possible to describe every object of the scene with a caption while objects are determined by bounding boxes. However, interpretation of such an output is not trivial due to the existence of many overlapping bounding boxes. Furthermore, in current captioning frameworks, the user is not able to involve personal preferences to exclude out of interest areas. In this paper, we propose a novel hybrid deep learning architecture for interactive region segmentation and captioning where the user is able to specify an arbitrary region of the image that should be processed. To this end, a dedicated Fully Convolutional Network (FCN) named Lyncean FCN (LFCN) is trained using our special training data to isolate the User Intention Region (UIR) as the output of an efficient segmentation. In parallel, a dense image captioning model is utilized to provide a wide variety of captions for that region. Then, the UIR will be explained with the caption of the best match bounding box. To the best of our knowledge, this is the first work that provides such a comprehensive output. Our experiments show the superiority of the proposed approach over state-of-the-art interactive segmentation methods on several well-known datasets. In addition, replacement of the bounding boxes with the result of the interactive segmentation leads to a better understanding of the dense image captioning output as well as accuracy enhancement for the object detection in terms of Intersection over Union (IoU).

##### Abstract (translated by Google)
随着最近在密集图像字幕中的创新，现在可以用标题描述场景的每个对象，而对象由边界框确定。然而，由于存在许多重叠的边界框，因此对这种输出的解释并不是微不足道的。此外，在当前字幕框架中，用户不能涉及个人偏好以排除感兴趣区域。在本文中，我们提出了一种用于交互式区域分割和字幕的新型混合深度学习架构，其中用户能够指定应该处理的图像的任意区域。为此，使用我们的特殊训练数据训练名为​​Lyncean FCN（LFCN）的专用全卷积网络（FCN），以将用户意图区域（UIR）隔离为有效分段的输出。同时，利用密集图像字幕模型为该区域提供各种各样的字幕。然后，将使用最佳匹配边界框的标题来解释UIR。据我们所知，这是第一部提供如此全面输出的作品。我们的实验表明，在几个众所周知的数据集上，所提出的方法优于最先进的交互式分割方法。此外，利用交互式分割的结果替换边界框导致更好地理解密集图像字幕输出以及针对联合交叉（IoU）方面的对象检测的准确度增强。

##### URL
[https://arxiv.org/abs/1707.08364](https://arxiv.org/abs/1707.08364)

##### PDF
[https://arxiv.org/pdf/1707.08364](https://arxiv.org/pdf/1707.08364)

