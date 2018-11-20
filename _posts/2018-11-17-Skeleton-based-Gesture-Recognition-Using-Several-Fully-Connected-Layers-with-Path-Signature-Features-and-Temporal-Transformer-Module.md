---
layout: post
title: "Skeleton-based Gesture Recognition Using Several Fully Connected Layers with Path Signature Features and Temporal Transformer Module"
date: 2018-11-17 02:41:38
categories: arXiv_CV
tags: arXiv_CV Attention Face Classification Recognition
author: Chenyang Li, Xin Zhang, Lufan Liao, Lianwen Jin, Weixin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
The skeleton based gesture recognition is gaining more popularity due to its wide possible applications. The key issues are how to extract discriminative features and how to design the classification model. In this paper, we first leverage a robust feature descriptor, path signature (PS), and propose three PS features to explicitly represent the spatial and temporal motion characteristics, i.e., spatial PS (S_PS), temporal PS (T_PS) and temporal spatial PS (T_S_PS). Considering the significance of fine hand movements in the gesture, we propose an "attention on hand" (AOH) principle to define joint pairs for the S_PS and select single joint for the T_PS. In addition, the dyadic method is employed to extract the T_PS and T_S_PS features that encode global and local temporal dynamics in the motion. Secondly, without the recurrent strategy, the classification model still faces challenges on temporal variation among different sequences. We propose a new temporal transformer module (TTM) that can match the sequence key frames by learning the temporal shifting parameter for each input. This is a learning-based module that can be included into standard neural network architecture. Finally, we design a multi-stream fully connected layer based network to treat spatial and temporal features separately and fused them together for the final result. We have tested our method on three benchmark gesture datasets, i.e., ChaLearn 2016, ChaLearn 2013 and MSRC-12. Experimental results demonstrate that we achieve the state-of-the-art performance on skeleton-based gesture recognition with high computational efficiency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07081](http://arxiv.org/abs/1811.07081)

##### PDF
[http://arxiv.org/pdf/1811.07081](http://arxiv.org/pdf/1811.07081)

