---
layout: post
title: "Spatial As Deep: Spatial CNN for Traffic Scene Understanding"
date: 2017-12-17 09:37:52
categories: arXiv_CV
tags: arXiv_CV Face CNN RNN Detection Relation
author: Xingang Pan, Jianping Shi, Ping Luo, Xiaogang Wang, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) are usually built by stacking convolutional operations layer-by-layer. Although CNN has shown strong capability to extract semantics from raw pixels, its capacity to capture spatial relationships of pixels across rows and columns of an image is not fully explored. These relationships are important to learn semantic objects with strong shape priors but weak appearance coherences, such as traffic lanes, which are often occluded or not even painted on the road surface as shown in Fig. 1 (a). In this paper, we propose Spatial CNN (SCNN), which generalizes traditional deep layer-by-layer convolutions to slice-byslice convolutions within feature maps, thus enabling message passings between pixels across rows and columns in a layer. Such SCNN is particular suitable for long continuous shape structure or large objects, with strong spatial relationship but less appearance clues, such as traffic lanes, poles, and wall. We apply SCNN on a newly released very challenging traffic lane detection dataset and Cityscapse dataset. The results show that SCNN could learn the spatial relationship for structure output and significantly improves the performance. We show that SCNN outperforms the recurrent neural network (RNN) based ReNet and MRF+CNN (MRFNet) in the lane detection dataset by 8.7% and 4.6% respectively. Moreover, our SCNN won the 1st place on the TuSimple Benchmark Lane Detection Challenge, with an accuracy of 96.53%.

##### Abstract (translated by Google)
卷积神经网络（CNN）通常是通过层叠卷积运算来构建的。虽然CNN已经显示出从原始像素中提取语义的强大能力，但是它没有充分探索其捕捉图像的行和列上的像素的空间关系的能力。这些关系对于学习语义对象具有很强的形状先验性，但外观连贯性弱，如交通车道，这往往是堵塞甚至没有画在路面上，如图1（a）所示。在本文中，我们提出了空间CNN（SCNN），它将传统的深层逐层卷积概化为特征映射中的逐层卷积，从而使层间的行和列之间的像素之间的消息传递成为可能。这样的SCNN特别适用于长连续的形状结构或大物体，空间关系强，外形线条少，如车道，杆，墙等。我们将SCNN应用于新发布的非常具有挑战性的车道检测数据集和Cityscapse数据集。结果表明，SCNN可以学习结构输出的空间关系，显着提高性能。我们发现SCNN在车道检测数据集中的回归神经网络（ReNNN）和MRF + CNN（MRFNet）分别优于8.7％和4.6％。此外，我们的SCNN在TuSimple Benchmark Lane检测挑战赛中获得第一名，准确率为96.53％。

##### URL
[http://arxiv.org/abs/1712.06080](http://arxiv.org/abs/1712.06080)

##### PDF
[http://arxiv.org/pdf/1712.06080](http://arxiv.org/pdf/1712.06080)

