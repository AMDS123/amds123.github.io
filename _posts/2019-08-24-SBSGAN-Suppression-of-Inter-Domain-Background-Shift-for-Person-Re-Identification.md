---
layout: post
title: "SBSGAN: Suppression of Inter-Domain Background Shift for Person Re-Identification"
date: 2019-08-24 03:48:28
categories: arXiv_CV
tags: arXiv_CV Re-identification Adversarial Segmentation GAN Person_Re-identification
author: Yan Huang, Qiang Wu, JingSong Xu, Yi Zhong
mathjax: true
---

* content
{:toc}

##### Abstract
Cross-domain person re-identification (re-ID) is challenging due to the bias between training and testing domains. We observe that if backgrounds in the training and testing datasets are very different, it dramatically introduces difficulties to extract robust pedestrian features, and thus compromises the cross-domain person re-ID performance. In this paper, we formulate such problems as a background shift problem. A Suppression of Background Shift Generative Adversarial Network (SBSGAN) is proposed to generate images with suppressed backgrounds. Unlike simply removing backgrounds using binary masks, SBSGAN allows the generator to decide whether pixels should be preserved or suppressed to reduce segmentation errors caused by noisy foreground masks. Additionally, we take ID-related cues, such as vehicles and companions into consideration. With high-quality generated images, a Densely Associated 2-Stream (DA-2S) network is introduced with Inter Stream Densely Connection (ISDC) modules to strengthen the complementarity of the generated data and ID-related cues. The experiments show that the proposed method achieves competitive performance on three re-ID datasets, ie., Market-1501, DukeMTMC-reID, and CUHK03, under the cross-domain person re-ID scenario.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09086](http://arxiv.org/abs/1908.09086)

##### PDF
[http://arxiv.org/pdf/1908.09086](http://arxiv.org/pdf/1908.09086)

