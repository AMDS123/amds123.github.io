---
layout: post
title: "Image Matters: Visually modeling user behaviors using Advanced Model Server"
date: 2018-09-04 09:11:57
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Tiezheng Ge, Liqin Zhao, Guorui Zhou, Keyu Chen, Shuying Liu, Huimin Yi, Zelin Hu, Bochao Liu, Peng Sun, Haoyu Liu, Pengtao Yi, Sui Huang, Zhiqiang Zhang, Xiaoqiang Zhu, Yu Zhang, Kun Gai
mathjax: true
---

* content
{:toc}

##### Abstract
In Taobao, the largest e-commerce platform in China, billions of items are provided and typically displayed with their images. For better user experience and business effectiveness, Click Through Rate (CTR) prediction in online advertising system exploits abundant user historical behaviors to identify whether a user is interested in a candidate ad. Enhancing behavior representations with user behavior images will help understand user's visual preference and improve the accuracy of CTR prediction greatly. So we propose to model user preference jointly with user behavior ID features and behavior images. However, training with user behavior images brings tens to hundreds of images in one sample, giving rise to a great challenge in both communication and computation. To handle these challenges, we propose a novel and efficient distributed machine learning paradigm called Advanced Model Server (AMS). With the well known Parameter Server (PS) framework, each server node handles a separate part of parameters and updates them independently. AMS goes beyond this and is designed to be capable of learning a unified image descriptor model shared by all server nodes which embeds large images into low dimensional high level features before transmitting images to worker nodes. AMS thus dramatically reduces the communication load and enables the arduous joint training process. Based on AMS, the methods of effectively combining the images and ID features are carefully studied, and then we propose a Deep Image CTR Model. Our approach is shown to achieve significant improvements in both online and offline evaluations, and has been deployed in Taobao display advertising system serving the main traffic.

##### Abstract (translated by Google)
在中国最大的电子商务平台淘宝网中，提供了数十亿件物品，并通常与他们的图像一起显示。为了获得更好的用户体验和业务效率，在线广告系统中的点击率（CTR）预测利用丰富的用户历史行为来识别用户是否对候选广告感兴趣。使用用户行为图像增强行为表示将有助于了解用户的视觉偏好并极大地提高CTR预测的准确性。因此，我们建议将用户偏好与用户行为ID特征和行为图像联合建模。然而，使用用户行为图像的训练在一个样本中带来数十到数百个图像，从而在通信和计算中产生巨大挑战。为了应对这些挑战，我们提出了一种新颖高效的分布式机器学习范例，称为高级模型服务器（AMS）。使用众所周知的参数服务器（PS）框架，每个服务器节点处理单独的参数部分并独立更新它们。 AMS超越了这一点，旨在能够学习由所有服务器节点共享的统一图像描述符模型，该模型在将图像传输到工作节点之前将大图像嵌入到低维高级特征中。因此，AMS显着降低了通信负荷，并实现了艰苦的联合培训过程。基于AMS，仔细研究了有效组合图像和ID特征的方法，然后提出了深度图像CTR模型。我们的方法显示在线上和线下评估方面取得了显着进步，并已部署在为主要流量服务的淘宝显示广告系统中。

##### URL
[http://arxiv.org/abs/1711.06505](http://arxiv.org/abs/1711.06505)

##### PDF
[http://arxiv.org/pdf/1711.06505](http://arxiv.org/pdf/1711.06505)

