---
layout: post
title: "Hallucinating Bag-of-Words and Fisher Vector IDT terms for CNN-based Action Recognition"
date: 2019-06-13 19:44:17
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Classification Recognition
author: Lei Wang, Piotr Koniusz, Du Q. Huynh
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we revive the use of old-fashioned handcrafted video representations and put new life into these techniques via a CNN-based hallucination step. Specifically, we address the problem of action classification in videos via an I3D network pre-trained on the large scale Kinetics-400 dataset. Despite of the use of RGB and optical flow frames, the I3D model (amongst others) thrives on combining its output with the Improved Dense Trajectory (IDT) and extracted with it low-level video descriptors encoded via Bag-of-Words (BoW) and Fisher Vectors (FV). Such a fusion of CNNs and hand crafted representations is time-consuming due to various pre-processing steps, descriptor extraction, encoding and fine-tuning of the model. In this paper, we propose an end-to-end trainable network with streams which learn the IDT-based BoW/FV representations at the training stage and are simple to integrate with the I3D model. Specifically, each stream takes I3D feature maps ahead of the last 1D conv. layer and learns to `translate' these maps to BoW/FV representations. Thus, our enhanced I3D model can hallucinate and use such synthesized BoW/FV representations at the testing stage. We demonstrate simplicity/usefulness of our model on three publicly available datasets and we show state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05910](https://arxiv.org/abs/1906.05910)

##### PDF
[https://arxiv.org/pdf/1906.05910](https://arxiv.org/pdf/1906.05910)

