---
layout: post
title: "Learning to Segment Breast Biopsy Whole Slide Images"
date: 2017-10-10 22:22:06
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Semantic_Segmentation
author: Sachin Mehta, Ezgi Mercan, Jamen Bartlett, Donald Weaver, Joann Elmore, Linda Shapiro
mathjax: true
---

* content
{:toc}

##### Abstract
We trained and applied an encoder-decoder model to semantically segment breast biopsy images into biologically meaningful tissue labels. Since conventional encoder-decoder networks cannot be applied directly on large biopsy images and the different sized structures in biopsies present novel challenges, we propose four modifications: (1) an input-aware encoding block to compensate for information loss, (2) a new dense connection pattern between encoder and decoder, (3) dense and sparse decoders to combine multi-level features, (4) a multi-resolution network that fuses the results of encoder-decoders run on different resolutions. Our model outperforms a feature-based approach and conventional encoder-decoders from the literature. We use semantic segmentations produced with our model in an automated diagnosis task and obtain higher accuracies than a baseline approach that employs an SVM for feature-based segmentation, both using the same segmentation-based diagnostic features.

##### Abstract (translated by Google)
我们训练并应用编码器 - 解码器模型，将乳房活检图像语义分割成具有生物学意义的组织标签。由于传统的编码器 - 解码器网络不能直接应用于大的活组织图像，而活组织检查中的不同大小的结构提出了新的挑战，我们提出了四种修改：（1）输入感知编码块以补偿信息损失;（2）编码器和解码器之间的密集连接模式，（3）稠密和稀疏的解码器以组合多级特征，（4）多分辨率网络，其融合在不同分辨率下运行的编码器 - 解码器的结果。我们的模型比文献中的基于特征的方法和传统的编码器 - 解码器优越得多。我们将使用我们的模型生成的语义分割用于自动诊断任务，并获得比采用基于特征的分割的SVM的基线方法更高的精度，两者都使用相同的基于分割的诊断特征。

##### URL
[https://arxiv.org/abs/1709.02554](https://arxiv.org/abs/1709.02554)

##### PDF
[https://arxiv.org/pdf/1709.02554](https://arxiv.org/pdf/1709.02554)

