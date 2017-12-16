---
layout: post
title: "FaceBoxes: A CPU Real-time Face Detector with High Accuracy"
date: 2017-08-19 08:58:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Detection Face_Detection
author: Shifeng Zhang, Xiangyu Zhu, Zhen Lei, Hailin Shi, Xiaobo Wang, Stan Z. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Although tremendous strides have been made in face detection, one of the remaining open challenges is to achieve real-time speed on the CPU as well as maintain high performance, since effective models for face detection tend to be computationally prohibitive. To address this challenge, we propose a novel face detector, named FaceBoxes, with superior performance on both speed and accuracy. Specifically, our method has a lightweight yet powerful network structure that consists of the Rapidly Digested Convolutional Layers (RDCL) and the Multiple Scale Convolutional Layers (MSCL). The RDCL is designed to enable FaceBoxes to achieve real-time speed on the CPU. The MSCL aims at enriching the receptive fields and discretizing anchors over different layers to handle faces of various scales. Besides, we propose a new anchor densification strategy to make different types of anchors have the same density on the image, which significantly improves the recall rate of small faces. As a consequence, the proposed detector runs at 20 FPS on a single CPU core and 125 FPS using a GPU for VGA-resolution images. Moreover, the speed of FaceBoxes is invariant to the number of faces. We comprehensively evaluate this method and present state-of-the-art detection performance on several face detection benchmark datasets, including the AFW, PASCAL face, and FDDB.

##### Abstract (translated by Google)
尽管在人脸检测方面已经取得了巨大的进步，但其余的开放挑战之一是要在CPU上实现实时的速度并保持高性能，因为有效的人脸检测模型往往在计算上受到限制。为了应对这一挑战，我们提出了一种名为FaceBoxes的新型面部检测器，在速度和准确性方面都具有优越的性能。具体来说，我们的方法有一个轻量级但强大的网络结构，由快速消化卷积层（RDCL）和多尺度卷积层（MSCL）组成。 RDCL旨在使FaceBoxes能够在CPU上实现实时速度。 MSCL旨在丰富接受领域和不同层次的锚定，以处理各种尺度的面孔。此外，本文提出了一种新的锚定致密化策略，使得不同类型的锚点在图像上具有相同的密度，显着提高了小面的召回率。结果，所提出的检测器在单CPU核心上以20FPS运行，在VGA分辨率图像上使用GPU以125FPS运行。而且，FaceBox的速度对于人脸数量是不变的。我们综合评估了这种方法，并在几个人脸检测基准数据集（包括AFW，PASCAL face和FDDB）上提供了最先进的检测性能。

##### URL
[https://arxiv.org/abs/1708.05234](https://arxiv.org/abs/1708.05234)

##### PDF
[https://arxiv.org/pdf/1708.05234](https://arxiv.org/pdf/1708.05234)

