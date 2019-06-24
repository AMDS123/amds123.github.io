---
layout: post
title: "SGANVO: Unsupervised Deep Visual Odometry and Depth Estimation with Stacked Generative Adversarial Networks"
date: 2019-06-20 22:51:10
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Deep_Learning
author: Tuo Feng, Dongbing Gu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently end-to-end unsupervised deep learning methods have achieved an effect beyond geometric methods for visual depth and ego-motion estimation tasks. These data-based learning methods perform more robustly and accurately in some of the challenging scenes. The encoder-decoder network has been widely used in the depth estimation and the RCNN has brought significant improvements in the ego-motion estimation. Furthermore, the latest use of Generative Adversarial Nets(GANs) in depth and ego-motion estimation has demonstrated that the estimation could be further improved by generating pictures in the game learning process. This paper proposes a novel unsupervised network system for visual depth and ego-motion estimation: Stacked Generative Adversarial Network(SGANVO). It consists of a stack of GAN layers, of which the lowest layer estimates the depth and ego-motion while the higher layers estimate the spatial features. It can also capture the temporal dynamic due to the use of a recurrent representation across the layers. See Fig.1 for details. We select the most commonly used KITTI [1] data set for evaluation. The evaluation results show that our proposed method can produce better or comparable results in depth and ego-motion estimation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08889](http://arxiv.org/abs/1906.08889)

##### PDF
[http://arxiv.org/pdf/1906.08889](http://arxiv.org/pdf/1906.08889)

