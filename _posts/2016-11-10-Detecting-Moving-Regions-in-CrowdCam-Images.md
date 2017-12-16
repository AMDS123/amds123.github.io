---
layout: post
title: "Detecting Moving Regions in CrowdCam Images"
date: 2016-11-10 11:58:52
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Adi Dafni, Yael Moses, Shai Avidan
mathjax: true
---

* content
{:toc}

##### Abstract
We address the novel problem of detecting dynamic regions in CrowdCam images, a set of still images captured by a group of people. These regions capture the most interesting parts of the scene, and detecting them plays an important role in the analysis of visual data. Our method is based on the observation that matching static points must satisfy the epipolar geometry constraints, but computing exact matches is challenging. Instead, we compute the probability that a pixel has a match, not necessarily the correct one, along the corresponding epipolar line. The complement of this probability is not necessarily the probability of a dynamic point because of occlusions, noise, and matching errors. Therefore, information from all pairs of images is aggregated to obtain a high quality dynamic probability map, per image. Experiments on challenging datasets demonstrate the effectiveness of the algorithm on a broad range of settings; no prior knowledge about the scene, the camera characteristics or the camera locations is required.

##### Abstract (translated by Google)
我们解决了在CrowdCam图像中检测动态区域的新问题，这是一群人拍摄的一组静止图像。这些区域捕捉场景中最有趣的部分，检测它们在视觉数据分析中起着重要的作用。我们的方法是基于观察匹配静态点必须满足极线几何约束，但计算精确匹配是具有挑战性的。相反，我们计算一个像素沿相应的核线有一个匹配的概率，不一定是正确的。由于遮挡，噪声和匹配错误，这个概率的补码不一定是动态点的概率。因此，来自所有图像对的信息被聚合以获得每张图像的高质量动态概率图。在具有挑战性的数据集上的实验证明了该算法在广泛的设置上的有效性;没有关于场景的先验知识，相机特性或相机位置是必需的。

##### URL
[https://arxiv.org/abs/1611.03270](https://arxiv.org/abs/1611.03270)

##### PDF
[https://arxiv.org/pdf/1611.03270](https://arxiv.org/pdf/1611.03270)

