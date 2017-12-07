---
layout: post
title: "Object Contour Detection with a Fully Convolutional Encoder-Decoder Network"
date: 2016-03-15 02:11:49
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Detection
author: Jimei Yang, Brian Price, Scott Cohen, Honglak Lee, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a deep learning algorithm for contour detection with a fully convolutional encoder-decoder network. Different from previous low-level edge detection, our algorithm focuses on detecting higher-level object contours. Our network is trained end-to-end on PASCAL VOC with refined ground truth from inaccurate polygon annotations, yielding much higher precision in object contour detection than previous methods. We find that the learned model generalizes well to unseen object classes from the same super-categories on MS COCO and can match state-of-the-art edge detection on BSDS500 with fine-tuning. By combining with the multiscale combinatorial grouping algorithm, our method can generate high-quality segmented object proposals, which significantly advance the state-of-the-art on PASCAL VOC (improving average recall from 0.62 to 0.67) with a relatively small amount of candidates ($\sim$1660 per image).

##### Abstract (translated by Google)
我们开发了一个完全卷积编码器 - 解码器网络的轮廓检测深度学习算法。与以前的低级边缘检测算法不同，我们的算法重点是检测更高级别的物体轮廓。我们的网络在PASCAL VOC上进行了端对端的培训，从不准确的多边形注释中获得了精确的地面真实性，在物体轮廓检测中比以前的方法具有更高的精度。我们发现，学习模型很好地概括了MS COCO上相同的超类别中看不见的对象类，并且可以与BSDS500上的最新边缘检测进行微调。通过与多尺度组合分组算法相结合，我们的方法可以生成高质量的分段对象提议，这使得PASCAL VOC（将平均召回率从0.62提高到0.67）的技术水平显着提高，候选人数相对较少（$ \ sim $ 1660每张图片）。

##### URL
[https://arxiv.org/abs/1603.04530](https://arxiv.org/abs/1603.04530)

##### PDF
[https://arxiv.org/pdf/1603.04530](https://arxiv.org/pdf/1603.04530)

