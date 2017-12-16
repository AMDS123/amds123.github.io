---
layout: post
title: "Depth Assisted Full Resolution Network for Single Image-based View Synthesis"
date: 2017-11-17 16:50:13
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Xiaodong Cun, Feng Xu, Chi-Man Pun, Hao Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Researches in novel viewpoint synthesis majorly focus on interpolation from multi-view input images. In this paper, we focus on a more challenging and ill-posed problem that is to synthesize novel viewpoints from one single input image. To achieve this goal, we propose a novel deep learning-based technique. We design a full resolution network that extracts local image features with the same resolution of the input, which contributes to derive high resolution and prevent blurry artifacts in the final synthesized images. We also involve a pre-trained depth estimation network into our system, and thus 3D information is able to be utilized to infer the flow field between the input and the target image. Since the depth network is trained by depth order information between arbitrary pairs of points in the scene, global image features are also involved into our system. Finally, a synthesis layer is used to not only warp the observed pixels to the desired positions but also hallucinate the missing pixels with recorded pixels. Experiments show that our technique performs well on images of various scenes, and outperforms the state-of-the-art techniques.

##### Abstract (translated by Google)
新视点合成研究主要集中于多视点输入图像的插值。在本文中，我们关注一个更具挑战性和不适合的问题，即从一个单一的输入图像合成新颖的观点。为了实现这个目标，我们提出了一种新颖的基于深度学习的技术。我们设计了一个全分辨率的网络，以相同的输入分辨率提取局部图像特征，有助于获得高分辨率，并防止最终合成图像中的模糊伪像。我们还将预先训练的深度估计网络引入到我们的系统中，从而能够利用3D信息来推断输入与目标图像之间的流场。由于深度网络是通过场景中任意点之间的深度顺序信息进行训练的，所以全局图像特征也涉及到我们的系统中。最后，合成层不仅用于将观察到的像素扭曲到期望的位置，而且还用记录的像素幻化缺失的像素。实验表明，我们的技术在各种场景的图像上表现良好，并且胜过最先进的技术。

##### URL
[https://arxiv.org/abs/1711.06620](https://arxiv.org/abs/1711.06620)

##### PDF
[https://arxiv.org/pdf/1711.06620](https://arxiv.org/pdf/1711.06620)

