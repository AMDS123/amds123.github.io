---
layout: post
title: "'Zero-Shot' Super-Resolution using Deep Internal Learning"
date: 2017-12-17 11:00:30
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Knowledge Deep_Learning
author: Assaf Shocher, Nadav Cohen, Michal Irani
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Learning has led to a dramatic leap in Super-Resolution (SR) performance in the past few years. However, being supervised, these SR methods are restricted to specific training data, where the acquisition of the low-resolution (LR) images from their high-resolution (HR) counterparts is predetermined (e.g., bicubic downscaling), without any distracting artifacts (e.g., sensor noise, image compression, non-ideal PSF, etc). Real LR images, however, rarely obey these restrictions, resulting in poor SR results by SotA (State of the Art) methods. In this paper we introduce "Zero-Shot" SR, which exploits the power of Deep Learning, but does not rely on prior training. We exploit the internal recurrence of information inside a single image, and train a small image-specific CNN at test time, on examples extracted solely from the input image itself. As such, it can adapt itself to different settings per image. This allows to perform SR of real old photos, noisy images, biological data, and other images where the acquisition process is unknown or non-ideal. On such images, our method outperforms SotA CNN-based SR methods, as well as previous unsupervised SR methods. To the best of our knowledge, this is the first unsupervised CNN-based SR method.

##### Abstract (translated by Google)
深度学习在过去几年里已经在超分辨率（SR）性能方面取得了巨大的飞跃。然而，受监督，这些SR方法仅限于特定的训练数据，其中从其高分辨率（HR）对应物获取低分辨率（LR）图像是预定的（例如，双三次降尺度），没有任何分散的伪影例如传感器噪声，图像压缩，非理想的PSF等）。然而，真正的LR图像很少遵守这些限制，从而导致SotA（现有技术）方法的较差的SR结果。在本文中，我们将介绍“Zero-Shot”SR，它利用了深度学习的力量，但不依赖于以前的训练。我们利用单个图像内部信息的内部重现，并且在测试时间训练一个小图像特定的CNN，这个例子是从输入图像本身提取的。因此，它可以适应每个图像的不同设置。这允许在采集过程未知或不理想的情况下执行真实的老照片，噪声图像，生物数据和其他图像的SR。在这样的图像上，我们的方法胜过SotA基于CNN的SR方法，以及以前的无监督SR方法。据我们所知，这是第一个无监督的基于CNN的SR方法。

##### URL
[http://arxiv.org/abs/1712.06087](http://arxiv.org/abs/1712.06087)

##### PDF
[http://arxiv.org/pdf/1712.06087](http://arxiv.org/pdf/1712.06087)

