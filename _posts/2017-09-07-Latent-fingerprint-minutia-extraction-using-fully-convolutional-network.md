---
layout: post
title: "Latent fingerprint minutia extraction using fully convolutional network"
date: 2017-09-07 12:15:54
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yao Tang, Fei Gao, Jufu Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Minutiae play a major role in fingerprint identification. Extracting reliable minutiae is difficult for latent fingerprints which are usually of poor quality. As the limitation of traditional handcrafted features, a fully convolutional network (FCN) is utilized to learn features directly from data to overcome complex background noises. Raw fingerprints are mapped to a correspondingly-sized minutia-score map with a fixed stride. And thus a large number of minutiae will be extracted through a given threshold. Then small regions centering at these minutia points are entered into a convolutional neural network (CNN) to reclassify these minutiae and calculate their orientations. The CNN shares convolutional layers with the fully convolutional network to speed up. 0.45 second is used on average to detect one fingerprint on a GPU. On the NIST SD27 database, we achieve 53\% recall rate and 53\% precise rate that outperform many other algorithms. Our trained model is also visualized to show that we have successfully extracted features preserving ridge information of a latent fingerprint.

##### Abstract (translated by Google)
细节在指纹识别中起主要作用。提取可靠的细节对于通常质量差的潜在指纹是困难的。由于传统手工功能的局限性，利用完全卷积网络（FCN）直接从数据中学习特征来克服复杂的背景噪声。将原始指纹映射到具有固定步幅的相应尺寸的细节分数图。因此，大量的细节将通过给定的阈值来提取。然后以这些细节点为中心的小区域进入卷积神经网络（CNN）重新分类这些细节并计算它们的方向。 CNN与全卷积网络共享卷积层来加速。平均使用0.45秒来检测GPU上的一个指纹。在NIST SD27数据库上，我们实现了53％的查全率和53％的精确率，超越了其他许多算法。我们的训练模型也可视化表明，我们已经成功地提取了特征，保存了潜指纹的脊线信息。

##### URL
[https://arxiv.org/abs/1609.09850](https://arxiv.org/abs/1609.09850)

##### PDF
[https://arxiv.org/pdf/1609.09850](https://arxiv.org/pdf/1609.09850)

