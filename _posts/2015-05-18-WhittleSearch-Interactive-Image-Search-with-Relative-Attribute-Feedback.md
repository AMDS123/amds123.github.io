---
layout: post
title: "WhittleSearch: Interactive Image Search with Relative Attribute Feedback"
date: 2015-05-18 13:52:40
categories: arXiv_CV
tags: arXiv_CV
author: Adriana Kovashka, Devi Parikh, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel mode of feedback for image search, where a user describes which properties of exemplar images should be adjusted in order to more closely match his/her mental model of the image sought. For example, perusing image results for a query "black shoes", the user might state, "Show me shoe images like these, but sportier." Offline, our approach first learns a set of ranking functions, each of which predicts the relative strength of a nameable attribute in an image (e.g., sportiness). At query time, the system presents the user with a set of exemplar images, and the user relates them to his/her target image with comparative statements. Using a series of such constraints in the multi-dimensional attribute space, our method iteratively updates its relevance function and re-ranks the database of images. To determine which exemplar images receive feedback from the user, we present two variants of the approach: one where the feedback is user-initiated and another where the feedback is actively system-initiated. In either case, our approach allows a user to efficiently "whittle away" irrelevant portions of the visual feature space, using semantic language to precisely communicate her preferences to the system. We demonstrate our technique for refining image search for people, products, and scenes, and we show that it outperforms traditional binary relevance feedback in terms of search speed and accuracy. In addition, the ordinal nature of relative attributes helps make our active approach efficient -- both computationally for the machine when selecting the reference images, and for the user by requiring less user interaction than conventional passive and active methods.

##### Abstract (translated by Google)
我们为图像搜索提出了一种新颖的反馈模式，其中用户描述样本图像的哪些属性应该被调整以更紧密地匹配他/她所寻找的图像的心理模型。例如，仔细查看“黑色鞋子”查询的图像结果，用户可能会声明“向我展示像这样的鞋子图像，但更具运动性”。离线时，我们的方法首先学习一组排名函数，每个排名函数预测图像中可命名属性（例如运动）的相对强度。在查询时，系统向用户呈现一组示例图像，并且用户将其与他/她的目标图像进行关联，并进行比较。利用多维属性空间中的一系列约束条件，我们的方法迭代更新其相关函数，重新对图像数据库进行排序。为了确定哪些示例图像从用户接收反馈，我们提出了两种方法的变体：一种是反馈是用户发起的，另一种是反馈主动地由系统发起。在任何一种情况下，我们的方法都允许用户有效地“消除”视觉特征空间的无关部分，使用语义语言将其偏好精确地传达给系统。我们展示了我们用于精炼人员，产品和场景的图像搜索的技术，并且我们表明它在搜索速度和准确性方面优于传统的二进制相关性反馈。另外，相对属性的序数性质有助于使我们的主动方法有效 - 既在计算机上选择参考图像时的计算机，也为用户提供比传统的被动和主动方法更少的用户交互。

##### URL
[https://arxiv.org/abs/1505.04141](https://arxiv.org/abs/1505.04141)

##### PDF
[https://arxiv.org/pdf/1505.04141](https://arxiv.org/pdf/1505.04141)

