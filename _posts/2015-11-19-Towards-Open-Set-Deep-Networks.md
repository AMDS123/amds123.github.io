---
layout: post
title: "Towards Open Set Deep Networks"
date: 2015-11-19 16:13:55
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Abhijit Bendale, Terrance Boult
mathjax: true
---

* content
{:toc}

##### Abstract
Deep networks have produced significant gains for various visual recognition problems, leading to high impact academic and commercial applications. Recent work in deep networks highlighted that it is easy to generate images that humans would never classify as a particular object class, yet networks classify such images high confidence as that given class - deep network are easily fooled with images humans do not consider meaningful. The closed set nature of deep networks forces them to choose from one of the known classes leading to such artifacts. Recognition in the real world is open set, i.e. the recognition system should reject unknown/unseen classes at test time. We present a methodology to adapt deep networks for open set recognition, by introducing a new model layer, OpenMax, which estimates the probability of an input being from an unknown class. A key element of estimating the unknown probability is adapting Meta-Recognition concepts to the activation patterns in the penultimate layer of the network. OpenMax allows rejection of "fooling" and unrelated open set images presented to the system; OpenMax greatly reduces the number of obvious errors made by a deep network. We prove that the OpenMax concept provides bounded open space risk, thereby formally providing an open set recognition solution. We evaluate the resulting open set deep networks using pre-trained networks from the Caffe Model-zoo on ImageNet 2012 validation data, and thousands of fooling and open set images. The proposed OpenMax model significantly outperforms open set recognition accuracy of basic deep networks as well as deep networks with thresholding of SoftMax probabilities.

##### Abstract (translated by Google)
深度网络已经为各种视觉识别问题带来了显着的收益，从而导致高影响力的学术和商业应用。最近在深度网络中的工作突出表明，很容易生成人类永远不会分类为特定对象类别的图像，然而网络将这些图像高度自信地分类，因为给定的类别 - 深度网络很容易被人们认为没有意义的图像所迷惑。深层网络的封闭性质迫使他们从导致这种文物的已知类别中选择一个。在现实世界中的识别是开放的，即识别系统应该在测试时间拒绝未知/不可见的类别。我们通过引入一个新的模型层，OpenMax来估计输入来自未知类别的可能性，提出了一种方法来适应深度网络的开放集合识别。估计未知概率的关键要素是将元识别概念应用于网络倒数第二层的激活模式。 OpenMax允许拒绝提供给系统的“愚弄”和不相关的开放设置图像; OpenMax大大减少了由深层网络造成的明显错误的数量。我们证明了OpenMax概念提供了有限的开放空间风险，从而正式提供了一个开放式的识别解决方案。我们使用来自Caffe Model-zoo的ImageNet 2012验证数据的预先训练好的网络，以及数以千计的傻瓜式和开放式设置图像来评估得到的开放式深度网络。所提出的OpenMax模型明显优于基本深度网络和具有SoftMax概率阈值的深度网络的开集识别准确率。

##### URL
[https://arxiv.org/abs/1511.06233](https://arxiv.org/abs/1511.06233)

##### PDF
[https://arxiv.org/pdf/1511.06233](https://arxiv.org/pdf/1511.06233)

