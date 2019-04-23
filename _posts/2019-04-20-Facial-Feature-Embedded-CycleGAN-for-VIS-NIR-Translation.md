---
layout: post
title: "Facial Feature Embedded CycleGAN for VIS-NIR Translation"
date: 2019-04-20 15:45:29
categories: arXiv_CV
tags: arXiv_CV GAN Face Recognition Face_Recognition
author: Huijiao Wang, Li Wang, Xulei Yang, Lei Yu, Haijian Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
VIS-NIR face recognition remains a challenging task due to the distinction between spectral components of two modalities and insufficient paired training data. Inspired by the CycleGAN, this paper presents a method aiming to translate VIS face images into fake NIR images whose distributions are intended to approximate those of true NIR images, which is achieved by proposing a new facial feature embedded CycleGAN. Firstly, to learn the particular feature of NIR domain while preserving common facial representation between VIS and NIR domains, we employ a general facial feature extractor (FFE) to replace the encoder in the original generator of CycleGAN. For implementing the facial feature extractor, herein the MobileFaceNet is pretrained on a VIS face database, and is able to extract effective features. Secondly, the domain-invariant feature learning is enhanced by considering a new pixel consistency loss. Lastly, we establish a new WHU VIS-NIR database which varies in face rotation and expressions to enrich the training data. Experimental results on the Oulu-CASIA NIR-VIS database and the WHU VIS-NIR database show that the proposed FFE-based CycleGAN (FFE-CycleGAN) outperforms state-of-the-art VIS-NIR face recognition methods and achieves 96.5\% accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09464](http://arxiv.org/abs/1904.09464)

##### PDF
[http://arxiv.org/pdf/1904.09464](http://arxiv.org/pdf/1904.09464)

