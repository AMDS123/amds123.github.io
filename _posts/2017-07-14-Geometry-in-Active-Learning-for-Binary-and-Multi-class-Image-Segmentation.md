---
layout: post
title: "Geometry in Active Learning for Binary and Multi-class Image Segmentation"
date: 2017-07-14 10:23:26
categories: arXiv_CV
tags: arXiv_CV Segmentation Face
author: Ksenia Konyushkova, Raphael Sznitman, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an Active Learning approach to image segmentation that exploits geometric priors to streamline the annotation process. We demonstrate this for both background-foreground and multi-class segmentation tasks in 2D images and 3D image volumes. Our approach combines geometric smoothness priors in the image space with more traditional uncertainty measures to estimate which pixels or voxels are most in need of annotation. For multi-class settings, we additionally introduce two novel criteria for uncertainty. In the 3D case, we use the resulting uncertainty measure to show the annotator voxels lying on the same planar patch, which makes batch annotation much easier than if they were randomly distributed in the volume. The planar patch is found using a branch-and-bound algorithm that finds a patch with the most informative instances. We evaluate our approach on Electron Microscopy and Magnetic Resonance image volumes, as well as on regular images of horses and faces. We demonstrate a substantial performance increase over state-of-the-art approaches.

##### Abstract (translated by Google)
我们提出了一种主动学习的图像分割方法，利用几何先验来简化注释过程。我们在二维图像和三维图像体中对背景前景和多类别的分割任务展示了这一点。我们的方法将图像空间中的几何光滑先验与更传统的不确定性测量相结合，以估计哪些像素或体素是最需要注释的。对于多级设置，我们另外引入了两个新的不确定性标准。在3D情况下，我们使用由此产生的不确定性度量来显示位于同一个平面片上的注释体素，这使得批量注释比随机分布在体中更容易。使用分支定界算法找到平面补丁，找到具有最多信息的实例的补丁。我们评估我们的方法在电子显微镜和磁共振图像卷，以及马和面部的常规图像。我们展示了比最先进的方法显着的性能提升。

##### URL
[https://arxiv.org/abs/1606.09029](https://arxiv.org/abs/1606.09029)

##### PDF
[https://arxiv.org/pdf/1606.09029](https://arxiv.org/pdf/1606.09029)

