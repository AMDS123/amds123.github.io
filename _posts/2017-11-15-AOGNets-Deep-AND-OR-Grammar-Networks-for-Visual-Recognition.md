---
layout: post
title: "AOGNets: Deep AND-OR Grammar Networks for Visual Recognition"
date: 2017-11-15 23:42:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Represenation_Learning Classification Detection Recognition
author: Xilai Li, Tianfu Wu, Xi Song, Hamid Krim
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method of learning deep AND-OR Grammar (AOG) networks for visual recognition, which we term AOGNets. An AOGNet consists of a number of stages each of which is composed of a number of AOG building blocks. An AOG building block is designed based on a principled AND-OR grammar and represented by a hierarchical and compositional AND-OR graph. Each node applies some basic operation (e.g., Conv-BatchNorm-ReLU) to its input. There are three types of nodes: an AND-node explores composition, whose input is computed by concatenating features of its child nodes; an OR-node represents alternative ways of composition in the spirit of exploitation, whose input is the element-wise sum of features of its child nodes; and a Terminal-node takes as input a channel-wise slice of the input feature map of the AOG building block. AOGNets aim to harness the best of two worlds (grammar models and deep neural networks) in representation learning with end-to-end training. In experiments, AOGNets are tested on three highly competitive image classification benchmarks: CIFAR-10, CIFAR-100 and ImageNet-1K. AOGNets obtain better performance than the widely used Residual Net and its variants, and are tightly comparable to the Dense Net. AOGNets are also tested in object detection on the PASCAL VOC 2007 and 2012 using the vanilla Faster RCNN system and obtain better performance than the Residual Net.

##### Abstract (translated by Google)
本文提出了一种学习视觉识别的深度“或”语法（AOG）网络的方法，我们称之为AOG网络。 AOGNet由多个阶段组成，每个阶段由多个AOG构建块组成。 AOG构建块是基于一个有原理的AND-OR语法设计的，由一个分层和组合的AND-OR图表示。每个节点对其输入应用一些基本操作（例如，Conv-BatchNorm-ReLU）。有三种类型的节点：AND节点探索组合，其输入通过连接其子节点的特征来计算; OR节点代表开发精神中的组合选择方式，其输入是其子节点的元素元素总和;并且终端节点将AOG构建块的输入特征映射的通道切片作为输入。 AOGNets旨在通过端到端的培训，在表征学习中利用两个世界中最好的（语法模型和深度神经网络）。在实验中，AOGNets在三个高度竞争的图像分类基准测试中进行测试：CIFAR-10，CIFAR-100和ImageNet-1K。 AOGNets获得比广泛使用的残余网络及其变体更好的性能，并与密集网络紧密相媲美。 AOGNets也在PASCAL VOC 2007和2012的对象检测中使用vanilla Faster RCNN系统进行测试，并获得比残余网络更好的性能。

##### URL
[https://arxiv.org/abs/1711.05847](https://arxiv.org/abs/1711.05847)

##### PDF
[https://arxiv.org/pdf/1711.05847](https://arxiv.org/pdf/1711.05847)

