---
layout: post
title: "VUNet: Dynamic Scene View Synthesis for Traversability Estimation using an RGB Camera"
date: 2019-01-10 20:05:27
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Noriaki Hirose, Amir Sadeghian, Fei Xia, Roberto Martin-Martin, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
We present VUNet, a novel view(VU) synthesis method for mobile robots in dynamic environments, and its application to the estimation of future traversability. Our method predicts future images for given virtual robot velocity commands using only RGB images at previous and current time steps. The future images result from applying two types of image changes to the previous and current images: 1) changes caused by different camera pose, and 2) changes due to the motion of the dynamic obstacles. We learn to predict these two types of changes disjointly using two novel network architectures, SNet and DNet. We combine SNet and DNet to synthesize future images that we pass to our previously presented method GONet to estimate the traversable areas around the robot. Our quantitative and qualitative evaluation indicate that our approach for view synthesis predicts accurate future images in both static and dynamic environments. We also show that these virtual images can be used to estimate future traversability correctly. We apply our view synthesis-based traversability estimation method to two applications for assisted teleoperation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.08864](http://arxiv.org/abs/1806.08864)

##### PDF
[http://arxiv.org/pdf/1806.08864](http://arxiv.org/pdf/1806.08864)

