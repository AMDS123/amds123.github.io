---
layout: post
title: "Learning Compact Recurrent Neural Networks with Block-Term Tensor Decomposition"
date: 2018-05-11 07:33:47
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Action_Recognition RNN Prediction Recognition
author: Jinmian Ye, Linnan Wang, Guangxi Li, Di Chen, Shandian Zhe, Xinqi Chu, Zenglin Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks (RNNs) are powerful sequence modeling tools. However, when dealing with high dimensional inputs, the training of RNNs becomes computational expensive due to the large number of model parameters. This hinders RNNs from solving many important computer vision tasks, such as Action Recognition in Videos and Image Captioning. To overcome this problem, we propose a compact and flexible structure, namely Block-Term tensor decomposition, which greatly reduces the parameters of RNNs and improves their training efficiency. Compared with alternative low-rank approximations, such as tensor-train RNN (TT-RNN), our method, Block-Term RNN (BT-RNN), is not only more concise (when using the same rank), but also able to attain a better approximation to the original RNNs with much fewer parameters. On three challenging tasks, including Action Recognition in Videos, Image Captioning and Image Generation, BT-RNN outperforms TT-RNN and the standard RNN in terms of both prediction accuracy and convergence rate. Specifically, BT-LSTM utilizes 17,388 times fewer parameters than the standard LSTM to achieve an accuracy improvement over 15.6\% in the Action Recognition task on the UCF11 dataset.

##### Abstract (translated by Google)
递归神经网络（RNN）是强大的序列建模工具。然而，当处理高维输入时，由于大量的模型参数，RNN的训练变得计算成本。这阻碍了RNN解决许多重要的计算机视觉任务，例如视频和图像字幕中的动作识别。为了克服这个问题，我们提出了一种紧凑而灵活的结构，即Block-Term张量分解，它大大减少了RNN的参数，提高了训练效率。与其他低等级近似值相比，例如张量序列RNN（TT-RNN），我们的方法，Block-Term RNN（BT-RNN），不仅更简洁（当使用相同的等级时），而且能够通过更少的参数获得更好的近似原始RNN。在三个具有挑战性的任务中，包括视频中的动作识别，图像捕获和图像生成，BT-RNN在预测准确度和收敛速度方面优于TT-RNN和标准RNN。具体而言，BT-LSTM使用的参数比标准LSTM少17,388倍，以在UCF11数据集的动作识别任务中实现超过15.6％的精度提升。

##### URL
[https://arxiv.org/abs/1712.05134](https://arxiv.org/abs/1712.05134)

##### PDF
[https://arxiv.org/pdf/1712.05134](https://arxiv.org/pdf/1712.05134)

