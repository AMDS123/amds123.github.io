---
layout: post
title: "A Benchmark Dataset and Saliency-guided Stacked Autoencoders for Video-based Salient Object Detection"
date: 2017-05-09 07:38:17
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Knowledge Tracking Deep_Learning Detection
author: Jia Li, Changqun Xia, Xiaowu Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Image-based salient object detection (SOD) has been extensively studied in the past decades. However, video-based SOD is much less explored since there lack large-scale video datasets within which salient objects are unambiguously defined and annotated. Toward this end, this paper proposes a video-based SOD dataset that consists of 200 videos (64 minutes). In constructing the dataset, we manually annotate all objects and regions over 7,650 uniformly sampled keyframes and collect the eye-tracking data of 23 subjects that free-view all videos. From the user data, we find salient objects in video can be defined as objects that consistently pop-out throughout the video, and objects with such attributes can be unambiguously annotated by combining manually annotated object/region masks with eye-tracking data of multiple subjects. To the best of our knowledge, it is currently the largest dataset for video-based salient object detection. Based on this dataset, this paper proposes an unsupervised baseline approach for video-based SOD by using saliency-guided stacked autoencoders. In the proposed approach, multiple spatiotemporal saliency cues are first extracted at pixel, superpixel and object levels. With these saliency cues, stacked autoencoders are unsupervisedly constructed which automatically infer a saliency score for each pixel by progressively encoding the high-dimensional saliency cues gathered from the pixel and its spatiotemporal neighbors. Experimental results show that the proposed unsupervised approach outperforms 30 state-of-the-art models on the proposed dataset, including 19 image-based & classic (unsupervised or non-deep learning), 6 image-based & deep learning, and 5 video-based & unsupervised. Moreover, benchmarking results show that the proposed dataset is very challenging and has the potential to boost the development of video-based SOD.

##### Abstract (translated by Google)
在过去的几十年里，基于图像的显着物体检测（SOD）已被广泛研究。然而，基于视频的SOD的研究要少得多，因为缺乏明确定义和注释显着对象的大规模视频数据集。为此，本文提出了一个由200个视频（64分钟）组成的基于视频的SOD数据集。在构建数据集时，我们手动注释了超过7,650个统一采样关键帧的所有对象和区域，并收集了23个免费观看所有视频的主题的眼动数据。从用户数据中，我们发现视频中的显着对象可以被定义为在整个视频中始终弹出的对象，并且可以通过将手动注释的对象/区域掩码与多个对象的眼睛跟踪数据相结合来明确地注释具有这种属性的对象。据我们所知，它是目前基于视频的显着物体检测的最大数据集。基于这个数据集，本文提出了一种基于视频的SOD的无监督基线方法，通过使用显着引导堆叠自动编码器。在所提出的方法中，多个时空显着性提示首先在像素，超像素和对象级提取。利用这些显着性提示，堆叠式自动编码器被无监督地构造，其通过逐步编码从像素及其时空邻居收集的高维显着性线索来自动推断每个像素的显着性分数。实验结果表明，所提出的无监督方法优于所提出的数据集上的30个最先进的模型，包括19个基于图像和经典（无监督或非深度学习），6个基于图像和深度学习，以及5个视频基于和无人监督。此外，基准测试结果显示，提出的数据集非常具有挑战性，并有可能促进基于视频的SOD的发展。

##### URL
[https://arxiv.org/abs/1611.00135](https://arxiv.org/abs/1611.00135)

##### PDF
[https://arxiv.org/pdf/1611.00135](https://arxiv.org/pdf/1611.00135)

