---
layout: post
title: "DeepHuman: 3D Human Reconstruction from a Single Image"
date: 2019-03-15 11:38:15
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation Deep_Learning
author: Zerong Zheng, Tao Yu, Yixuan Wei, Qionghai Dai, Yebin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose DeepHuman, a deep learning based framework for 3D human reconstruction from a single RGB image. Since this problem is highly intractable, we adopt a stage-wise, coarse-to-fine method consisting of three steps, namely body shape/pose estimation, surface reconstruction and frontal surface detail refinement. Once a body is estimated from the given image, our method generates a dense semantic representation from it. The representations not only encodes body shape and pose but also bridges the 2D image plane and 3D space. An image-guided volume-to-volume translation CNN is introduced to reconstruct the surface given the input image and the dense semantic representation. One key feature of our network is that it fuses different scales of image features into the 3D space through volumetric feature transformation, which helps to recover details of the subject's surface geometry. The details on the frontal areas of the surface are further refined through a normal map refinement network. The normal refinement network can be concatenated with the volume generation network using our proposed volumetric normal projection layer. We also contribute THuman, a 3D real-world human model dataset containing approximately 7000 models. The whole network is trained using training data generated from the dataset. Overall, due to the specific design of our network and the diversity in our dataset, our method enables 3D human reconstruction given only a single image and outperforms state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06473](http://arxiv.org/abs/1903.06473)

##### PDF
[http://arxiv.org/pdf/1903.06473](http://arxiv.org/pdf/1903.06473)

