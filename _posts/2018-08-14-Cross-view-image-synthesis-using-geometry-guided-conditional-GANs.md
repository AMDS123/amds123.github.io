---
layout: post
title: "Cross-view image synthesis using geometry-guided conditional GANs"
date: 2018-08-14 21:24:26
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Image_Generation
author: Krishna Regmi, Ali Borji
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of generating images across two drastically different views, namely ground (street) and aerial (overhead) views. Image synthesis by itself is a very challenging computer vision task and is even more so when generation is conditioned on an image in another view. Due the difference in viewpoints, there is small overlapping field of view and little common content between these two views. Here, we try to preserve the pixel information between the views so that the generated image is a realistic representation of cross view input image. For this, we propose to use homography as a guide to map the images between the views based on the common field of view to preserve the details in the input image. We then use generative adversarial networks to inpaint the missing regions in the transformed image and add realism to it. Our exhaustive evaluation and model comparison demonstrate that utilizing geometry constraints adds fine details to the generated images and can be a better approach for cross view image synthesis than purely pixel based synthesis methods.

##### Abstract (translated by Google)
我们解决了在两个截然不同的视图中生成图像的问题，即地面（街道）和空中（俯视）视图。图像合成本身是一项非常具有挑战性的计算机视觉任务，当生成以另一种视图中的图像为条件时更是如此。由于视点的不同，在这两个视图之间存在小的重叠视野和很少的共同内容。在这里，我们尝试保留视图之间的像素信息，以便生成的图像是交叉视图输入图像的真实表示。为此，我们建议使用单应性作为指导，基于公共视野在视图之间映射图像，以保留输入图像中的细节。然后，我们使用生成对抗网络来修改变换图像中的缺失区域并为其添加真实感。我们详尽的评估和模型比较表明，利用几何约束为生成的图像添加了精细的细节，并且与纯粹的基于像素的合成方法相比，可以是更好的交叉视图图像合成方法。

##### URL
[http://arxiv.org/abs/1808.05469](http://arxiv.org/abs/1808.05469)

##### PDF
[http://arxiv.org/pdf/1808.05469](http://arxiv.org/pdf/1808.05469)

