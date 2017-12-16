---
layout: post
title: "Error Corrective Boosting for Learning Fully Convolutional Networks with Limited Data"
date: 2017-07-02 07:58:41
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Abhijit Guha Roy, Sailesh Conjeti, Debdoot Sheet, Amin Katouzian, Nassir Navab, Christian Wachinger
mathjax: true
---

* content
{:toc}

##### Abstract
Training deep fully convolutional neural networks (F-CNNs) for semantic image segmentation requires access to abundant labeled data. While large datasets of unlabeled image data are available in medical applications, access to manually labeled data is very limited. We propose to automatically create auxiliary labels on initially unlabeled data with existing tools and to use them for pre-training. For the subsequent fine-tuning of the network with manually labeled data, we introduce error corrective boosting (ECB), which emphasizes parameter updates on classes with lower accuracy. Furthermore, we introduce SkipDeconv-Net (SD-Net), a new F-CNN architecture for brain segmentation that combines skip connections with the unpooling strategy for upsampling. The SD-Net addresses challenges of severe class imbalance and errors along boundaries. With application to whole-brain MRI T1 scan segmentation, we generate auxiliary labels on a large dataset with FreeSurfer and fine-tune on two datasets with manual annotations. Our results show that the inclusion of auxiliary labels and ECB yields significant improvements. SD-Net segments a 3D scan in 7 secs in comparison to 30 hours for the closest multi-atlas segmentation method, while reaching similar performance. It also outperforms the latest state-of-the-art F-CNN models.

##### Abstract (translated by Google)
训练深度完全卷积神经网络（F-CNN）进行语义图像分割需要获得丰富的标记数据。尽管未标记图像数据的大数据集在医疗应用中可用，但手动标记数据的访问却非常有限。我们建议使用现有工具自动在最初未标记的数据上创建辅助标签，并将其用于预培训。为了随后用人工标记的数据对网络进行微调，我们引入了纠错提升（ECB），它强调了对精度较低的类进行参数更新。此外，我们还介绍了SkipDeconv-Net（SD-Net），一种新的F-CNN架构，用于脑区域分割，将跳跃连接与上采样的解耦策略相结合。 SD-Net解决严重的类别不平衡和边界错误的挑战。通过应用全脑MRI T1扫描分割，我们使用FreeSurfer在大型数据集上生成辅助标签，并使用手动注释对两个数据集进行微调。我们的研究结果表明，包括辅助标签和ECB产生显着的改善。 SD-Net在7秒内对3D扫描进行分割，而对于最接近的多图分割方法，SD-Net分割30个小时，同时达到类似的性能。它也胜过最新的F-CNN型号。

##### URL
[https://arxiv.org/abs/1705.00938](https://arxiv.org/abs/1705.00938)

##### PDF
[https://arxiv.org/pdf/1705.00938](https://arxiv.org/pdf/1705.00938)

