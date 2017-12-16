---
layout: post
title: "Separating Style and Content for Generalized Style Transfer"
date: 2017-11-17 08:26:12
categories: arXiv_CV
tags: arXiv_CV Attention Face Style_Transfer
author: Yexun Zhang, Wenbin Cai, Ya Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Neural style transfer has drawn broad attention in recent years. However, most existing methods aim to explicitly model the transformation between different styles, and the learned model is thus not generalizable to new styles. We here attempt to separate the representations for styles and contents, and propose a generalized style transfer network consisting of style encoder, content encoder, mixer and decoder. The style encoder and content encoder are used to extract the style and content factors from the style reference images and content reference images, respectively. The mixer employs a bilinear model to integrate the above two factors and finally feeds it into a decoder to generate images with target style and content. To separate the style features and content features, we leverage the conditional dependence of styles and contents given an image. During training, the encoder network learns to extract styles and contents from two sets of reference images in limited size, one with shared style and the other with shared content. This learning framework allows simultaneous style transfer among multiple styles and can be deemed as a special `multi-task' learning scenario. The encoders are expected to capture the underlying features for different styles and contents which is generalizable to new styles and contents. For validation, we applied the proposed algorithm to the Chinese Typeface transfer problem. Extensive experiment results on character generation have demonstrated the effectiveness and robustness of our method.

##### Abstract (translated by Google)
神经风格转移近年来引起了广泛的关注。然而，现有的大多数方法都是针对不同风格之间的转换进行明确的建模，因此学习的模型不能推广到新的风格。我们试图将样式和内容的表示分开，并提出一个由样式编码器，内容编码器，混合器和解码器组成的广义样式传输网络。样式编码器和内容编码器分别用于从样式参考图像和内容参考图像中提取样式和内容因子。混音器采用双线性模型对上述两个因素进行整合，最终送入解码器生成具有目标风格和内容的图像。为了分离样式特征和内容特征，我们利用给定图像的样式和内容的条件依赖性。在训练期间，编码器网络学习从两组有限尺寸的参考图像中提取样式和内容，一个具有共享样式而另一个具有共享内容。这种学习框架允许在多种风格之间同时进行风格转换，并且可以被认为是一种特殊的“多任务”学习场景。预计编码器捕捉不同风格和内容的基本特征，这些特征可以推广到新的风格和内容。为了验证，我们将所提出的算法应用于中文字体转换问题。角色生成的大量实验结果证明了我们方法的有效性和鲁棒性。

##### URL
[https://arxiv.org/abs/1711.06454](https://arxiv.org/abs/1711.06454)

##### PDF
[https://arxiv.org/pdf/1711.06454](https://arxiv.org/pdf/1711.06454)

