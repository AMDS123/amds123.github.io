---
layout: post
title: "Coupled-Projection Residual Network for MRI Super-Resolution"
date: 2019-07-12 07:30:46
categories: arXiv_CV
tags: arXiv_CV Super_Resolution
author: Chun-Mei Feng, Kai Wang, Shijian Lu, Yong Xu, Heng Kong, Ling Shao
mathjax: true
---

* content
{:toc}

##### Abstract
Magnetic Resonance Imaging(MRI) has been widely used in clinical application and pathology research by helping doctors make more accurate diagnoses. On the other hand, accurate diagnosis by MRI remains a great challenge as images obtained via present MRI techniques usually have low resolutions. Improving MRI image quality and resolution thus becomes a critically important task. This paper presents an innovative Coupled-Projection Residual Network (CPRN) for MRI super-resolution. The CPRN consists of two complementary sub-networks: a shallow network and a deep network that keep the content consistency while learning high frequency differences between low-resolution and high-resolution images. The shallow sub-network employs coupled-projection for better retaining the MRI image details, where a novel feedback mechanism is introduced to guide the reconstruction of high-resolution images. The deep sub-network learns from the residuals of the high-frequency image information, where multiple residual blocks are cascaded to magnify the MRI images at the last network layer. Finally, the features from the shallow and deep sub-networks are fused for the reconstruction of high-resolution MRI images. For effective fusion of features from the deep and shallow sub-networks, a step-wise connection (CPRN S) is designed as inspired by the human cognitive processes (from simple to complex). Experiments over three public MRI datasets show that our proposed CPRN achieves superior MRI super-resolution performance as compared with the state-of-the-art. Our source code will be publicly available at <a href="http://www.yongxu.org/lunwen.html.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05598](http://arxiv.org/abs/1907.05598)

##### PDF
[http://arxiv.org/pdf/1907.05598](http://arxiv.org/pdf/1907.05598)

