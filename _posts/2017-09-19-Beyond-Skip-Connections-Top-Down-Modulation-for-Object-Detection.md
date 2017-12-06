---
layout: post
title: "Beyond Skip Connections: Top-Down Modulation for Object Detection"
date: 2017-09-19 22:37:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Abhinav Shrivastava, Rahul Sukthankar, Jitendra Malik, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, we have seen tremendous progress in the field of object detection. Most of the recent improvements have been achieved by targeting deeper feedforward networks. However, many hard object categories such as bottle, remote, etc. require representation of fine details and not just coarse, semantic representations. But most of these fine details are lost in the early convolutional layers. What we need is a way to incorporate finer details from lower layers into the detection architecture. Skip connections have been proposed to combine high-level and low-level features, but we argue that selecting the right features from low-level requires top-down contextual information. Inspired by the human visual pathway, in this paper we propose top-down modulations as a way to incorporate fine details into the detection framework. Our approach supplements the standard bottom-up, feedforward ConvNet with a top-down modulation (TDM) network, connected using lateral connections. These connections are responsible for the modulation of lower layer filters, and the top-down network handles the selection and integration of contextual information and low-level features. The proposed TDM architecture provides a significant boost on the COCO testdev benchmark, achieving 28.6 AP for VGG16, 35.2 AP for ResNet101, and 37.3 for InceptionResNetv2 network, without any bells and whistles (e.g., multi-scale, iterative box refinement, etc.).

##### Abstract (translated by Google)
近年来，我们在物体检测领域取得了巨大的进展。大部分最近的改进都是通过瞄准更深的前馈网络来实现的。然而，瓶子，遥控器等许多硬件对象要求表示细节，而不仅仅是粗略的语义表示。但是这些细节大部分都在早期的卷积层中丢失了。我们需要的是将较低层的更精细的细节结合到检测体系结构中的一种方式。已经提出跳过连接来结合高级和低级特征，但是我们认为从低级选择正确的特征需要自顶向下的上下文信息。受到人类视觉通路的启发，本文中我们提出自上而下的调制方式，将细节融入检测框架。我们的方法补充了自顶向下调制（TDM）网络的标准自底向上，前馈ConvNet，使用横向连接进行连接。这些连接负责调制较低层过滤器，自上而下的网络负责处理上下文信息和低级特征的选择和集成。所提出的TDM架构为COCO testdev基准测试提供了显着的提升，VGG16达到了28.6 AP，ResNet101达到了35.2 AP，InceptionResNetv2网络达到了37.3，没有任何花招（比如多尺度，迭代盒精细化等） 。

##### URL
[https://arxiv.org/abs/1612.06851](https://arxiv.org/abs/1612.06851)

