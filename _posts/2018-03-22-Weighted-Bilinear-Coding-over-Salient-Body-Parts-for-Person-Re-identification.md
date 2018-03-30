---
layout: post
title: "Weighted Bilinear Coding over Salient Body Parts for Person Re-identification"
date: 2018-03-22 20:51:26
categories: arXiv_CV
tags: arXiv_CV Salient Re-identification Person_Re-identification CNN Relation Recognition
author: Qin Zhou, Heng Fan, Hang Su, Hua Yang, Shibao Zheng, Haibin Ling
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) have demonstrated dominant performance in person re-identification (Re-ID). Existing CNN based methods utilize global average pooling (GAP) to aggregate intermediate convolutional features for Re-ID. However, this strategy only considers the first-order statistics of local features and treats local features at different locations equally important, leading to sub-optimal feature representation. To deal with these issues, we propose a novel \emph{weighted bilinear coding} (WBC) model for local feature aggregation in CNN networks to pursue more representative and discriminative feature representations. In specific, bilinear coding is used to encode the channel-wise feature correlations to capture richer feature interactions. Meanwhile, a weighting scheme is applied on the bilinear coding to adaptively adjust the weights of local features at different locations based on their importance in recognition, further improving the discriminability of feature aggregation. To handle the spatial misalignment issue, we use a salient part net to derive salient body parts, and apply the WBC model on each part. The final representation, formed by concatenating the WBC eoncoded features of each part, is both discriminative and resistant to spatial misalignment. Experiments on three benchmarks including Market-1501, DukeMTMC-reID and CUHK03 evidence the favorable performance of our method against other state-of-the-art methods.

##### Abstract (translated by Google)
深卷积神经网络（CNN）已经证明了在人重新识别（Re-ID）方面的主要性能。现有的基于CNN的方法利用全局平均池（GAP）来聚合Re-ID的中间卷积特征。但是，该策略仅考虑局部特征的一阶统计量，并将同一重要位置处的局部特征视为同等重要，导致次优特征表示。为了解决这些问题，我们提出了一种新颖的用于CNN网络中局部特征聚合的加权双线性编码（WBC）模型，以追求更具代表性和区分性的特征表示。具体而言，双线性编码被用于编码信道方面的特征相关性以捕获更丰富的特征交互。同时，对双线性编码应用加权方案，根据识别的重要性自适应调整不同位置的局部特征权值，进一步提高特征聚合的可辨性。为了处理空间偏差问题，我们使用显着的部分网络来导出显着的身体部位，并将WBC模型应用于每个部分。通过连接每个部分的WBC编码特征形成的最终表示既具有区分性又能抵抗空间不对齐。包括Market-1501，DukeMMC-reID和CUHK03三个基准的实验证明了我们的方法与其他最先进的方法的良好表现。

##### URL
[https://arxiv.org/abs/1803.08580](https://arxiv.org/abs/1803.08580)

##### PDF
[https://arxiv.org/pdf/1803.08580](https://arxiv.org/pdf/1803.08580)

