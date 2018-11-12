---
layout: post
title: "Can Deep Learning Outperform Modern Commercial CT Image Reconstruction Methods?"
date: 2018-11-08 22:04:22
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Hongming Shan, Atul Padole, Fatemeh Homayounieh, Uwe Kruger, Ruhani Doda Khera, Chayanin Nitiwarangkul, Mannudeep K. Kalra, Ge Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Commercial iterative reconstruction techniques on modern CT scanners target radiation dose reduction but there are lingering concerns over their impact on image appearance and low contrast detectability. Recently, machine learning, especially deep learning, has been actively investigated for CT. Here we design a novel neural network architecture for low-dose CT (LDCT) and compare it with commercial iterative reconstruction methods used for standard of care CT. While popular neural networks are trained for end-to-end mapping, driven by big data, our novel neural network is intended for end-to-process mapping so that intermediate image targets are obtained with the associated search gradients along which the final image targets are gradually reached. This learned dynamic process allows to include radiologists in the training loop to optimize the LDCT denoising workflow in a task-specific fashion with the denoising depth as a key parameter. Our progressive denoising network was trained with the Mayo LDCT Challenge Dataset, and tested on images of the chest and abdominal regions scanned on the CT scanners made by three leading CT vendors. The best deep learning based reconstructions are systematically compared to the best iterative reconstructions in a double-blinded reader study. It is found that our deep learning approach performs either comparably or favorably in terms of noise suppression and structural fidelity, and runs orders of magnitude faster than the commercial iterative CT reconstruction algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03691](http://arxiv.org/abs/1811.03691)

##### PDF
[http://arxiv.org/pdf/1811.03691](http://arxiv.org/pdf/1811.03691)

