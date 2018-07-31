---
layout: post
title: "ReenactGAN: Learning to Reenact Faces via Boundary Transfer"
date: 2018-07-29 16:35:15
categories: arXiv_AI
tags: arXiv_AI GAN Face
author: Wayne Wu, Yunxuan Zhang, Cheng Li, Chen Qian, Chen Change Loy
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel learning-based framework for face reenactment. The proposed method, known as ReenactGAN, is capable of transferring facial movements and expressions from monocular video input of an arbitrary person to a target person. Instead of performing a direct transfer in the pixel space, which could result in structural artifacts, we first map the source face onto a boundary latent space. A transformer is subsequently used to adapt the boundary of source face to the boundary of target face. Finally, a target-specific decoder is used to generate the reenacted target face. Thanks to the effective and reliable boundary-based transfer, our method can perform photo-realistic face reenactment. In addition, ReenactGAN is appealing in that the whole reenactment process is purely feed-forward, and thus the reenactment process can run in real-time (30 FPS on one GTX 1080 GPU). Dataset and model will be publicly available at https://wywu.github.io/projects/ReenactGAN/ReenactGAN.html

##### Abstract (translated by Google)
我们提出了一种新的基于学习的面部重演框架。所提出的方法，称为ReenactGAN，能够将面部运动和表情从任意人的单眼视频输入传送到目标人。我们首先将源面映射到边界潜在空间，而不是在像素空间中执行可能导致结构伪影的直接传递。随后使用变压器使源面的边界适应目标面的边界。最后，使用特定于目标的解码器来生成重新生成的目标面。由于有效可靠的基于边界的转移，我们的方法可以执行照片逼真的面部重演。此外，ReenactGAN的吸引力在于整个重演过程纯粹是前馈，因此重演过程可以实时运行（在一个GTX 1080 GPU上运行30 FPS）。数据集和模型将在https://wywu.github.io/projects/ReenactGAN/ReenactGAN.html公开发布

##### URL
[http://arxiv.org/abs/1807.11079](http://arxiv.org/abs/1807.11079)

##### PDF
[http://arxiv.org/pdf/1807.11079](http://arxiv.org/pdf/1807.11079)

