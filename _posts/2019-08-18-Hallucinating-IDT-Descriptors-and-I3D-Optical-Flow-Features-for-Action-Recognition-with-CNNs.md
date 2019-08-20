---
layout: post
title: "Hallucinating IDT Descriptors and I3D Optical Flow Features for Action Recognition with CNNs"
date: 2019-08-18 15:37:40
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Recognition
author: Lei Wang, Piotr Koniusz, Du Q. Huynh
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we revive the use of old-fashioned handcrafted video representations for action recognition and put new life into these techniques via a CNN-based hallucination step. Despite of the use of RGB and optical flow frames, the I3D model (amongst others) thrives on combining its output with the Improved Dense Trajectory (IDT) and extracted with its low-level video descriptors encoded via Bag-of-Words (BoW) and Fisher Vectors (FV). Such a fusion of CNNs and handcrafted representations is time-consuming due to pre-processing, descriptor extraction, encoding and tuning parameters. Thus, we propose an end-to-end trainable network with streams which learn the IDT-based BoW/FV representations at the training stage and are simple to integrate with the I3D model. Specifically, each stream takes I3D feature maps ahead of the last 1D conv. layer and learns to `translate' these maps to BoW/FV representations. Thus, our model can hallucinate and use such synthesized BoW/FV representations at the testing stage. We show that even features of the entire I3D optical flow stream can be hallucinated thus simplifying the pipeline. Our model saves 20-55h of computations and yields state-of-the-art results on four publicly available datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.05910](http://arxiv.org/abs/1906.05910)

##### PDF
[http://arxiv.org/pdf/1906.05910](http://arxiv.org/pdf/1906.05910)

