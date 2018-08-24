---
layout: post
title: "Predictive Image Regression for Longitudinal Studies with Missing Data"
date: 2018-08-19 20:31:54
categories: arXiv_CV
tags: arXiv_CV CNN RNN Prediction
author: Sharmin Pathan, Yi Hong
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a predictive regression model for longitudinal images with missing data based on large deformation diffeomorphic metric mapping (LDDMM) and deep neural networks. Instead of directly predicting image scans, our model predicts a vector momentum sequence associated with a baseline image. This momentum sequence parameterizes the original image sequence in the LDDMM framework and lies in the tangent space of the baseline image, which is Euclidean. A recurrent network with long term-short memory (LSTM) units encodes the time-varying changes in the vector-momentum sequence, and a convolutional neural network (CNN) encodes the baseline image of the vector momenta. Features extracted by the LSTM and CNN are fed into a decoder network to reconstruct the vector momentum sequence, which is used for the image sequence prediction by deforming the baseline image with LDDMM shooting. To handle the missing images at some time points, we adopt a binary mask to ignore their reconstructions in the loss calculation. We evaluate our model on synthetically generated images and the brain MRIs from the OASIS dataset. Experimental results demonstrate the promising predictions of the spatiotemporal changes in both datasets, irrespective of large or subtle changes in longitudinal image sequences.

##### Abstract (translated by Google)
在本文中，我们提出了基于大变形微分形态度量映射（LDDMM）和深度神经网络的具有缺失数据的纵向图像的预测回归模型。我们的模型不是直接预测图像扫描，而是预测与基线图像相关的矢量动量序列。该动量序列参数化LDDMM框架中的原始图像序列，并且位于基线图像的切线空间中，即欧几里德。具有长期短存储器（LSTM）单元的循环网络编码矢量动量序列中的时变变化，并且卷积神经网络（CNN）编码矢量动量的基线图像。由LSTM和CNN提取的特征被馈送到解码器网络以重建矢量动量序列，其通过利用LDDMM射击使基线图像变形来用于图像序列预测。为了在某​​些时间点处理丢失的图像，我们采用二元掩模来忽略它们在损失计算中的重建。我们根据合成生成的图像和OASIS数据集中的脑MRI来评估我们的模型。实验结果证明了两个数据集中时空变化的有希望的预测，而不管纵向图像序列的大或微小变化。

##### URL
[http://arxiv.org/abs/1808.07553](http://arxiv.org/abs/1808.07553)

##### PDF
[http://arxiv.org/pdf/1808.07553](http://arxiv.org/pdf/1808.07553)

