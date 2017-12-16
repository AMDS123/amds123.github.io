---
layout: post
title: "Learning Local Shape Descriptors from Part Correspondences With Multi-view Convolutional Networks"
date: 2017-09-05 03:35:20
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Semantic_Segmentation Prediction
author: Haibin Huang, Evangelos Kalogerakis, Siddhartha Chaudhuri, Duygu Ceylan, Vladimir G. Kim, Ersin Yumer
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new local descriptor for 3D shapes, directly applicable to a wide range of shape analysis problems such as point correspondences, semantic segmentation, affordance prediction, and shape-to-scan matching. The descriptor is produced by a convolutional network that is trained to embed geometrically and semantically similar points close to one another in descriptor space. The network processes surface neighborhoods around points on a shape that are captured at multiple scales by a succession of progressively zoomed out views, taken from carefully selected camera positions. We leverage two extremely large sources of data to train our network. First, since our network processes rendered views in the form of 2D images, we repurpose architectures pre-trained on massive image datasets. Second, we automatically generate a synthetic dense point correspondence dataset by non-rigid alignment of corresponding shape parts in a large collection of segmented 3D models. As a result of these design choices, our network effectively encodes multi-scale local context and fine-grained surface detail. Our network can be trained to produce either category-specific descriptors or more generic descriptors by learning from multiple shape categories. Once trained, at test time, the network extracts local descriptors for shapes without requiring any part segmentation as input. Our method can produce effective local descriptors even for shapes whose category is unknown or different from the ones used while training. We demonstrate through several experiments that our learned local descriptors are more discriminative compared to state of the art alternatives, and are effective in a variety of shape analysis applications.

##### Abstract (translated by Google)
我们提出了一个新的局部三维形状描述符，直接适用于广泛的形状分析问题，如点对应，语义分割，可供性预测和形状到扫描匹配。描述符由卷积网络产生，经过训练可以在描述符空间中几何和语义上相似的点相互嵌入。这个网络处理在一个形状上的点周围的表面邻域，这些点通过从精心挑选的摄像机位置取得的连续逐渐缩小的视图以多个比例捕获。我们利用两个极其庞大的数据来训练我们的网络。首先，由于我们的网络处理以2D图像的形式呈现视图，因此我们重新调整了在大量图像数据集上预先训练的体系结构。其次，我们通过大量的分段三维模型集合中的相应形状部分的非刚性对齐，自动生成合成密集点对应数据集。作为这些设计选择的结果，我们的网络有效地编码多尺度的本地环境和细粒度的表面细节。我们的网络可以通过从多个形状类别学习来训练产生类别描述符或更一般的描述符。一旦训练完成，在测试时间，网络提取形状的局部描述符而不需要任何部分分段作为输入。我们的方法可以生成有效的局部描述符，即使对于类别未知或不同于训练时使用的类型。我们通过几个实验来证明，我们学习的局部描述符与最先进的替代品相比具有更多的区分性，并且在各种形状分析应用中都是有效的。

##### URL
[https://arxiv.org/abs/1706.04496](https://arxiv.org/abs/1706.04496)

##### PDF
[https://arxiv.org/pdf/1706.04496](https://arxiv.org/pdf/1706.04496)

