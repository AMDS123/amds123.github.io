---
layout: post
title: "Real-Time User-Guided Image Colorization with Learned Deep Priors"
date: 2017-05-08 17:58:11
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Deep_Learning
author: Richard Zhang, Jun-Yan Zhu, Phillip Isola, Xinyang Geng, Angela S. Lin, Tianhe Yu, Alexei A. Efros
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deep learning approach for user-guided image colorization. The system directly maps a grayscale image, along with sparse, local user "hints" to an output colorization with a Convolutional Neural Network (CNN). Rather than using hand-defined rules, the network propagates user edits by fusing low-level cues along with high-level semantic information, learned from large-scale data. We train on a million images, with simulated user inputs. To guide the user towards efficient input selection, the system recommends likely colors based on the input image and current user inputs. The colorization is performed in a single feed-forward pass, enabling real-time use. Even with randomly simulated user inputs, we show that the proposed system helps novice users quickly create realistic colorizations, and offers large improvements in colorization quality with just a minute of use. In addition, we demonstrate that the framework can incorporate other user "hints" to the desired colorization, showing an application to color histogram transfer. Our code and models are available at this https URL

##### Abstract (translated by Google)
我们提出了一种用户引导图像着色的深度学习方法。该系统直接将灰度图像与稀疏的本地用户“提示”一起映射到具有卷积神经网络（CNN）的输出彩色化。网络不是使用手工定义的规则，而是通过融合低级线索和从大规模数据中学习的高级语义信息来传播用户编辑。我们训练了一百万张图片，模拟用户输入。为了引导用户进行有效的输入选择，系统根据输入图像和当前用户输入推荐可能的颜色。着色是在一个前馈过程中执行的，可以实时使用。即使使用随机模拟的用户输入，我们也可以证明所提出的系统可以帮助新手用户快速创建逼真的色彩，并且只需一分钟的使用就可以大大提高色彩质量。另外，我们证明框架可以将其他用户“提示”合并到所需的着色中，从而显示应用程序对颜色直方图的转移。我们的代码和模型可在此https网址获得

##### URL
[https://arxiv.org/abs/1705.02999](https://arxiv.org/abs/1705.02999)

##### PDF
[https://arxiv.org/pdf/1705.02999](https://arxiv.org/pdf/1705.02999)

