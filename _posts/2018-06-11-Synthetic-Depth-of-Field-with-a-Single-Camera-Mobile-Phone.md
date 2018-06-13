---
layout: post
title: "Synthetic Depth-of-Field with a Single-Camera Mobile Phone"
date: 2018-06-11 18:29:12
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Neal Wadhwa, Rahul Garg, David E. Jacobs, Bryan E. Feldman, Nori Kanazawa, Robert Carroll, Yair Movshovitz-Attias, Jonathan T. Barron, Yael Pritch, Marc Levoy
mathjax: true
---

* content
{:toc}

##### Abstract
Shallow depth-of-field is commonly used by photographers to isolate a subject from a distracting background. However, standard cell phone cameras cannot produce such images optically, as their short focal lengths and small apertures capture nearly all-in-focus images. We present a system to computationally synthesize shallow depth-of-field images with a single mobile camera and a single button press. If the image is of a person, we use a person segmentation network to separate the person and their accessories from the background. If available, we also use dense dual-pixel auto-focus hardware, effectively a 2-sample light field with an approximately 1 millimeter baseline, to compute a dense depth map. These two signals are combined and used to render a defocused image. Our system can process a 5.4 megapixel image in 4 seconds on a mobile phone, is fully automatic, and is robust enough to be used by non-experts. The modular nature of our system allows it to degrade naturally in the absence of a dual-pixel sensor or a human subject.

##### Abstract (translated by Google)
摄影师通常使用浅景深将主体与分散注意力的背景隔离开来。然而，标准的手机相机不能以光学方式产生这样的图像，因为它们的短焦距和小光圈捕捉几乎全焦点图像。我们提出了一个系统，用一台移动摄像机和一个按钮按下计算合成浅景深图像。如果图像属于某人，我们使用人员分割网络将人员及其配件与背景分开。如果可用，我们还使用密集的双像素自动对焦硬件，实际上是具有大约1毫米基线的双样本光场，以计算密集的深度图。这两个信号被组合并用于渲染散焦的图像。我们的系统可以在手机上4秒内处理一张5.4万像素的图像，完全自动化，足够强大，可供非专家使用。我们的系统的模块化特性使其在没有双像素传感器或人体时自然降解。

##### URL
[http://arxiv.org/abs/1806.04171](http://arxiv.org/abs/1806.04171)

##### PDF
[http://arxiv.org/pdf/1806.04171](http://arxiv.org/pdf/1806.04171)

