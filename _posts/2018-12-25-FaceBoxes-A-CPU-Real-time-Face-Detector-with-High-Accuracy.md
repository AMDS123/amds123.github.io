---
layout: post
title: "FaceBoxes: A CPU Real-time Face Detector with High Accuracy"
date: 2018-12-25 05:49:00
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Detection Face_Detection
author: Shifeng Zhang, Xiangyu Zhu, Zhen Lei, Hailin Shi, Xiaobo Wang, Stan Z. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Although tremendous strides have been made in face detection, one of the remaining open challenges is to achieve real-time speed on the CPU as well as maintain high performance, since effective models for face detection tend to be computationally prohibitive. To address this challenge, we propose a novel face detector, named FaceBoxes, with superior performance on both speed and accuracy. Specifically, our method has a lightweight yet powerful network structure that consists of the Rapidly Digested Convolutional Layers (RDCL) and the Multiple Scale Convolutional Layers (MSCL). The RDCL is designed to enable FaceBoxes to achieve real-time speed on the CPU. The MSCL aims at enriching the receptive fields and discretizing anchors over different layers to handle faces of various scales. Besides, we propose a new anchor densification strategy to make different types of anchors have the same density on the image, which significantly improves the recall rate of small faces. As a consequence, the proposed detector runs at 20 FPS on a single CPU core and 125 FPS using a GPU for VGA-resolution images. Moreover, the speed of FaceBoxes is invariant to the number of faces. We comprehensively evaluate this method and present state-of-the-art detection performance on several face detection benchmark datasets, including the AFW, PASCAL face, and FDDB. Code is available at https://github.com/sfzhang15/FaceBoxes

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1708.05234](http://arxiv.org/abs/1708.05234)

##### PDF
[http://arxiv.org/pdf/1708.05234](http://arxiv.org/pdf/1708.05234)

