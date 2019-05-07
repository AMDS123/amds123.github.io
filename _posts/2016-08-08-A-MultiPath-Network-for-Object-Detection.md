---
layout: post
title: "A MultiPath Network for Object Detection"
date: 2016-08-08 13:29:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Sergey Zagoruyko, Adam Lerer, Tsung-Yi Lin, Pedro O. Pinheiro, Sam Gross, Soumith Chintala, Piotr Dollár
mathjax: true
---

* content
{:toc}

##### Abstract
The recent COCO object detection dataset presents several new challenges for object detection. In particular, it contains objects at a broad range of scales, less prototypical images, and requires more precise localization. To address these challenges, we test three modifications to the standard Fast R-CNN object detector: (1) skip connections that give the detector access to features at multiple network layers, (2) a foveal structure to exploit object context at multiple object resolutions, and (3) an integral loss function and corresponding network adjustment that improve localization. The result of these modifications is that information can flow along multiple paths in our network, including through features from multiple network layers and from multiple object views. We refer to our modified classifier as a "MultiPath" network. We couple our MultiPath network with DeepMask object proposals, which are well suited for localization and small objects, and adapt our pipeline to predict segmentation masks in addition to bounding boxes. The combined system improves results over the baseline Fast R-CNN detector with Selective Search by 66% overall and by 4x on small objects. It placed second in both the COCO 2015 detection and segmentation challenges.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1604.02135](https://arxiv.org/abs/1604.02135)

##### PDF
[https://arxiv.org/pdf/1604.02135](https://arxiv.org/pdf/1604.02135)

