---
layout: post
title: "Interactive Binary Image Segmentation with Edge Preservation"
date: 2018-09-10 14:14:21
categories: arXiv_CV
tags: arXiv_CV Segmentation Gradient_Descent
author: Jianfeng Zhang, Liezhuo Zhang, Yuankai Teng, Xiaoping Zhang, Song Wang, Lili Ju
mathjax: true
---

* content
{:toc}

##### Abstract
Binary image segmentation plays an important role in computer vision and has been widely used in many applications such as image and video editing, object extraction, and photo composition. In this paper, we propose a novel interactive binary image segmentation method based on the Markov Random Field (MRF) framework and the fast bilateral solver (FBS) technique. Specifically, we employ the geodesic distance component to build the unary term. To ensure both computation efficiency and effective responsiveness for interactive segmentation, superpixels are used in computing geodesic distances instead of pixels. Furthermore, we take a bilateral affinity approach for the pairwise term in order to preserve edge information and denoise. Through the alternating direction strategy, the MRF energy minimization problem is divided into two subproblems, which then can be easily solved by steepest gradient descent (SGD) and FBS respectively. Experimental results on the VGG interactive image segmentation dataset show that the proposed algorithm outperforms several state-of-the-art ones, and in particular, it can achieve satisfactory edge-smooth segmentation results even when the foreground and background color appearances are quite indistinctive.

##### Abstract (translated by Google)
二值图像分割在计算机视觉中起着重要作用，并且已广泛用于许多应用中，例如图像和视频编辑，对象提取和照片合成。在本文中，我们提出了一种基于马尔可夫随机场（MRF）框架和快速双边求解器（FBS）技术的交互式二值图像分割方法。具体来说，我们使用测地距离组件来构建一元术语。为了确保交互式分割的计算效率和有效响应，超像素用于计算测地距离而不是像素。此外，我们对成对项采用双边亲和方法，以保留边缘信息和去噪。通过交替方向策略，将MRF能量最小化问题分为两个子问题，然后分别通过最陡梯度下降（SGD）和FBS轻松解决。 VGG交互式图像分割数据集的实验结果表明，该算法优于几种最先进的算法，特别是即使前景色和背景色非常不明显，也可以获得令人满意的边缘平滑分割效果。

##### URL
[http://arxiv.org/abs/1809.03334](http://arxiv.org/abs/1809.03334)

##### PDF
[http://arxiv.org/pdf/1809.03334](http://arxiv.org/pdf/1809.03334)

