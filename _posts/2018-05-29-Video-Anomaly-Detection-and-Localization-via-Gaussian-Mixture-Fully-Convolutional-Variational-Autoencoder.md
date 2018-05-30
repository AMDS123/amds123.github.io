---
layout: post
title: "Video Anomaly Detection and Localization via Gaussian Mixture Fully Convolutional Variational Autoencoder"
date: 2018-05-29 02:37:19
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Detection
author: Yaxiang Fan, Gongjian Wen, Deren Li, Shaohua Qiu, Martin D. Levine
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel end-to-end partially supervised deep learning approach for video anomaly detection and localization using only normal samples. The insight that motivates this study is that the normal samples can be associated with at least one Gaussian component of a Gaussian Mixture Model (GMM), while anomalies either do not belong to any Gaussian component. The method is based on Gaussian Mixture Variational Autoencoder, which can learn feature representations of the normal samples as a Gaussian Mixture Model trained using deep learning. A Fully Convolutional Network (FCN) that does not contain a fully-connected layer is employed for the encoder-decoder structure to preserve relative spatial coordinates between the input image and the output feature map. Based on the joint probabilities of each of the Gaussian mixture components, we introduce a sample energy based method to score the anomaly of image test patches. A two-stream network framework is employed to combine the appearance and motion anomalies, using RGB frames for the former and dynamic flow images, for the latter. We test our approach on two popular benchmarks (UCSD Dataset and Avenue Dataset). The experimental results verify the superiority of our method compared to the state of the arts.

##### Abstract (translated by Google)
我们提出了一种新颖的端到端部分监督深度学习方法，用于仅使用正常样本的视频异常检测和定位。激发这项研究的见解是，正常样本可以与高斯混合模型（GMM）的至少一个高斯分量相关联，而异常或者不属于任何高斯分量。该方法基于高斯混合变分自动编码器，可以将正常样本的特征表示学习为使用深度学习训练的高斯混合模型。编码器 - 解码器结构采用不包含完全连接层的完全卷积网络（FCN）来保持输入图像和输出特征图之间的相对空间坐标。基于每个高斯混合分量的联合概率，我们引入基于样本能量的方法来评分图像测试片的异常。采用双流网络框架结合外观和运动异常，前者使用RGB帧，后者使用动态流动图像。我们在两个流行的基准测试（UCSD数据集和Avenue数据集）上测试我们的方法。实验结果验证了我们的方法与艺术状态相比的优越性。

##### URL
[http://arxiv.org/abs/1805.11223](http://arxiv.org/abs/1805.11223)

##### PDF
[http://arxiv.org/pdf/1805.11223](http://arxiv.org/pdf/1805.11223)

