---
layout: post
title: "Hierarchical Cross-Modal Talking Face Generationwith Dynamic Pixel-Wise Loss"
date: 2019-05-09 19:14:26
categories: arXiv_CV
tags: arXiv_CV Attention GAN Face Quantitative Relation
author: Lele Chen, Ross K. Maddox, Zhiyao Duan, Chenliang Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We devise a cascade GAN approach to generate talking face video, which is robust to different face shapes, view angles, facial characteristics, and noisy audio conditions. Instead of learning a direct mapping from audio to video frames, we propose first to transfer audio to high-level structure, i.e., the facial landmarks, and then to generate video frames conditioned on the landmarks. Compared to a direct audio-to-image approach, our cascade approach avoids fitting spurious correlations between audiovisual signals that are irrelevant to the speech content. We, humans, are sensitive to temporal discontinuities and subtle artifacts in video. To avoid those pixel jittering problems and to enforce the network to focus on audiovisual-correlated regions, we propose a novel dynamically adjustable pixel-wise loss with an attention mechanism. Furthermore, to generate a sharper image with well-synchronized facial movements, we propose a novel regression-based discriminator structure, which considers sequence-level information along with frame-level information. Thoughtful experiments on several datasets and real-world samples demonstrate significantly better results obtained by our method than the state-of-the-art methods in both quantitative and qualitative comparisons.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03820](http://arxiv.org/abs/1905.03820)

##### PDF
[http://arxiv.org/pdf/1905.03820](http://arxiv.org/pdf/1905.03820)

