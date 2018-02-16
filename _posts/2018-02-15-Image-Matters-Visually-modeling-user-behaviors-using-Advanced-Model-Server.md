---
layout: post
title: "Image Matters: Visually modeling user behaviors using Advanced Model Server"
date: 2018-02-15 12:08:39
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Tiezheng Ge, Liqin Zhao, Guorui Zhou, Keyu Chen, Shuying Liu, Huiming Yi, Zelin Hu, Bochao Liu, Peng Sun, Haoyu Liu, Pengtao Yi, Sui Huang, Zhiqiang Zhang, Xiaoqiang Zhu, Yu Zhang, Kun Gai
mathjax: true
---

* content
{:toc}

##### Abstract
In Taobao, the largest e-commerce platform in China, billions of items are provided and typically displayed with their images. For better user experience and business effectiveness, Click Through Rate (CTR) prediction in online advertising system exploits abundant user historical behaviors to identify whether a user is interested in a candidate ad. Enhancing behavior representations with user behavior images will bring user's visual preference and can greatly help CTR prediction. So we propose to model user preference jointly with user behavior ID features and behavior images. However, comparing with utilizing candidate ad image in CTR prediction which only introduces one image in one sample, training with user behavior images brings tens to hundreds of images in one sample, giving rise to a great challenge in both communication and computation. With the well-known Parameter Server (PS) framework, implementing such model needs to communicate the raw image features, leading to unacceptable communication load. It indicates PS is not suitable for this scenario. In this paper, we propose a novel and efficient distributed machine learning paradigm called Advanced Model Server (AMS). In AMS, the forward/backward process can also happen in the server side, and only high level semantic features with much smaller size need to be sent to workers. AMS thus dramatically reduces the communication load, which enables the arduous joint training process. Based on AMS, the methods of effectively combining the images and ID features are carefully studied, and then we propose a Deep Image CTR Model. Our approach is shown to achieve significant improvements in both online and offline evaluations, and has been deployed in Taobao display advertising system serving the main traffic.

##### Abstract (translated by Google)
在中国最大的电子商务平台淘宝网上，提供了数十亿件商品，并且通常会显示其图片。为了获得更好的用户体验和业务效果，在线广告系统中的点击率（CTR）预测利用丰富的用户历史行为来识别用户是否对候选广告感兴趣。使用用户行为图像增强行为表示会带来用户的视觉偏好，并且可以极大地帮助点击率预测。因此，我们建议与用户行为ID特征和行为图像一起建模用户偏好。然而，与仅在一个样本中引入一个图像的CTR预测中利用候选广告图像相比，用户行为图像的训练在一个样本中带来数十到数百个图像，这给通信和计算带来了巨大的挑战。使用众所周知的参数服务器（PS）框架，实现这种模型需要传送原始图像特征，导致不可接受的通信负载。这表明PS不适合这种情况。在本文中，我们提出了一种称为高级模型服务器（AMS）的新型高效分布式机器学习范例。在AMS中，前进/后退过程也可以发生在服务器端，只有小得多的高级语义特征需要发送给工作人员。因此，AMS显着降低了通信负载，从而实现了艰苦的联合培训过程。基于AMS，对图像和ID特征有效结合的方法进行了仔细的研究，然后我们提出了深度图像CTR模型。我们的方法被证明可以显着改善在线和离线评估，并且已经部署在服务于主要流量的淘宝显示广告系统中。

##### URL
[http://arxiv.org/abs/1711.06505](http://arxiv.org/abs/1711.06505)

##### PDF
[http://arxiv.org/pdf/1711.06505](http://arxiv.org/pdf/1711.06505)

