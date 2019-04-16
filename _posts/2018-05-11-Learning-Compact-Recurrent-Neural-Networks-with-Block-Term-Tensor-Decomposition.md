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


##### URL
[https://arxiv.org/abs/1712.05134](https://arxiv.org/abs/1712.05134)

##### PDF
[https://arxiv.org/pdf/1712.05134](https://arxiv.org/pdf/1712.05134)

