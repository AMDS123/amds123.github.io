---
layout: post
title: "A Unified Framework for Generalizable Style Transfer: Style and Content Separation"
date: 2018-06-13 01:39:02
categories: arXiv_CV
tags: arXiv_CV Attention Face Style_Transfer
author: Yexun Zhang, Ya Zhang, Wenbin Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Image style transfer has drawn broad attention in recent years. However, most existing methods aim to explicitly model the transformation between different styles, and the learned model is thus not generalizable to new styles. We here propose a unified style transfer framework for both character typeface transfer and neural style transfer tasks leveraging style and content separation. A key merit of such framework is its generalizability to new styles and contents. The overall framework consists of style encoder, content encoder, mixer and decoder. The style encoder and content encoder are used to extract the style and content representations from the corresponding reference images. The mixer integrates the above two representations and feeds it into the decoder to generate images with the target style and content. During training, the encoder networks learn to extract styles and contents from limited size of style/content reference images. This learning framework allows simultaneous style transfer among multiple styles and can be deemed as a special `multi-task' learning scenario. The encoders are expected to capture the underlying features for different styles and contents which is generalizable to new styles and contents. Under this framework, we design two individual networks for character typeface transfer and neural style transfer, respectively. For character typeface transfer, to separate the style features and content features, we leverage the conditional dependence of styles and contents given an image. For neural style transfer, we leverage the statistical information of feature maps in certain layers to represent style. Extensive experimental results have demonstrated the effectiveness and robustness of the proposed methods.

##### Abstract (translated by Google)
图像风格转移近年来引起广泛关注。然而，大多数现有的方法旨在明确地模拟不同风格之间的转换，并且学习模型因此不能推广到新的风格。我们在这里提出了一个统一的风格转移框架，用于字体字体转移和神经风格转移任务，利用风格和内容分离。这种框架的一个关键优点是其对新风格和内容的普遍性。整体框架由样式编码器，内容编码器，混音器和解码器组成。样式编码器和内容编码器用于从相应的参考图像中提取样式和内容表示。该混合器将上述两种表示形式集成并将其馈送到解码器中以生成具有目标样式和内容的图像。在训练期间，编码器网络学习从有限尺寸的样式/内容参考图像中提取样式和内容。这种学习框架允许在多种风格之间同时传输样式，并且可以被视为一种特殊的“多任务”学习场景。预计编码器将捕捉不同样式和内容的基本特征，这些特征可以归纳为新的样式和内容。在这个框架下，我们分别设计了两个单独的字符字体转移网络和神经风格转移网络。对于字符字体转换，为了分离样式特征和内容特征，我们利用给定图像的样式和内容的条件依赖性。对于神经风格转移，我们利用特定地图的统计信息来表示风格。广泛的实验结果证明了所提出方法的有效性和鲁棒性。

##### URL
[http://arxiv.org/abs/1806.05173](http://arxiv.org/abs/1806.05173)

##### PDF
[http://arxiv.org/pdf/1806.05173](http://arxiv.org/pdf/1806.05173)

