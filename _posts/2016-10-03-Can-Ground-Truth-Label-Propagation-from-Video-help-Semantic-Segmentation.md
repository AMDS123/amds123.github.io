---
layout: post
title: "Can Ground Truth Label Propagation from Video help Semantic Segmentation?"
date: 2016-10-03 20:29:12
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Recommendation
author: Siva Karthik Mustikovela, Michael Ying Yang, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
For state-of-the-art semantic segmentation task, training convolutional neural networks (CNNs) requires dense pixelwise ground truth (GT) labeling, which is expensive and involves extensive human effort. In this work, we study the possibility of using auxiliary ground truth, so-called \textit{pseudo ground truth} (PGT) to improve the performance. The PGT is obtained by propagating the labels of a GT frame to its subsequent frames in the video using a simple CRF-based, cue integration framework. Our main contribution is to demonstrate the use of noisy PGT along with GT to improve the performance of a CNN. We perform a systematic analysis to find the right kind of PGT that needs to be added along with the GT for training a CNN. In this regard, we explore three aspects of PGT which influence the learning of a CNN: i) the PGT labeling has to be of good quality; ii) the PGT images have to be different compared to the GT images; iii) the PGT has to be trusted differently than GT. We conclude that PGT which is diverse from GT images and has good quality of labeling can indeed help improve the performance of a CNN. Also, when PGT is multiple folds larger than GT, weighing down the trust on PGT helps in improving the accuracy. Finally, We show that using PGT along with GT, the performance of Fully Convolutional Network (FCN) on Camvid data is increased by $2.7\%$ on IoU accuracy. We believe such an approach can be used to train CNNs for semantic video segmentation where sequentially labeled image frames are needed. To this end, we provide recommendations for using PGT strategically for semantic segmentation and hence bypass the need for extensive human efforts in labeling.

##### Abstract (translated by Google)
对于最先进的语义分割任务，训练卷积神经网络（CNN）需要密集的像素地面真实（GT）标签，这是昂贵的并涉及大量人力。在这项工作中，我们研究使用辅助的基本事实，即所谓的“伪基础真理”（PGT）来提高性能的可能性。通过使用简单的基于CRF的提示集成框架，通过将GT帧的标签传播到其视频中的后续帧来获得PGT。我们的主要贡献是展示使用嘈杂的PGT和GT来提高CNN的性能。我们进行一个系统的分析，以找到正确的PGT类型，需要与GT一起加入培训CNN。在这方面，我们探讨了影响CNN学习的PGT的三个方面：i）PGT标签必须是高质量的; ii）PGT图像必须与GT图像相比不同; iii）PGT必须被信任而不是GT。我们得出这样的结论：PGT与GT图像是不同的，并且具有良好的标签质量确实可以帮助改善CNN的性能。而且，当PGT比GT大倍数时，减小对PGT的信任有助于提高准确性。最后，我们证明，使用PGT和GT，在Camvid数据上完全卷积网络（FCN）的性能在IoU精度上增加$ 2.7 \％$。我们相信这种方法可以被用来训练CNN进行语义视频分割，其中需要依次标记的图像帧。为此，我们提供了在策略上使用PGT进行语义分割的建议，从而避免了在标签上进行广泛的人工努力。

##### URL
[https://arxiv.org/abs/1610.00731](https://arxiv.org/abs/1610.00731)

##### PDF
[https://arxiv.org/pdf/1610.00731](https://arxiv.org/pdf/1610.00731)

