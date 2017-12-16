---
layout: post
title: "Improved Stereo Matching with Constant Highway Networks and Reflective Confidence Learning"
date: 2016-12-31 20:24:16
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Amit Shaked, Lior Wolf
mathjax: true
---

* content
{:toc}

##### Abstract
We present an improved three-step pipeline for the stereo matching problem and introduce multiple novelties at each stage. We propose a new highway network architecture for computing the matching cost at each possible disparity, based on multilevel weighted residual shortcuts, trained with a hybrid loss that supports multilevel comparison of image patches. A novel post-processing step is then introduced, which employs a second deep convolutional neural network for pooling global information from multiple disparities. This network outputs both the image disparity map, which replaces the conventional "winner takes all" strategy, and a confidence in the prediction. The confidence score is achieved by training the network with a new technique that we call the reflective loss. Lastly, the learned confidence is employed in order to better detect outliers in the refinement step. The proposed pipeline achieves state of the art accuracy on the largest and most competitive stereo benchmarks, and the learned confidence is shown to outperform all existing alternatives.

##### Abstract (translated by Google)
我们提出了一个改进的三步管道立体匹配问题，并在每个阶段引入多个新奇事物。我们提出了一种新的高速公路网络架构，用于根据多级加权剩余快捷方式计算每种可能差异的匹配成本，并通过混合损失进行训练，支持图像块的多级比较。然后引入一个新的后处理步骤，该步骤使用第二个深度卷积神经网络汇集来自多个差异的全局信息。这个网络输出的图像视差图，取代了传统的“赢家全部”策略，并在预测的信心。信心评分是通过用一种我们称之为反射损失的新技术来训练网络来实现的。最后，为了更好地检测细化步骤中的异常值，使用所学习的置信度。所提出的管线在最大和最具竞争力的立体基准上达到了最新的精确度，并且所学习的信心被证明优于所有现有的替代方案。

##### URL
[https://arxiv.org/abs/1701.00165](https://arxiv.org/abs/1701.00165)

##### PDF
[https://arxiv.org/pdf/1701.00165](https://arxiv.org/pdf/1701.00165)

