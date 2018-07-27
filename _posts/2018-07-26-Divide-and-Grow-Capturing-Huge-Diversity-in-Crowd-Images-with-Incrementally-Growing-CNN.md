---
layout: post
title: "Divide and Grow: Capturing Huge Diversity in Crowd Images with Incrementally Growing CNN"
date: 2018-07-26 07:52:17
categories: arXiv_CV
tags: arXiv_CV
author: Deepak Babu Sam, Neeraj N Sajjan, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
Automated counting of people in crowd images is a challenging task. The major difficulty stems from the large diversity in the way people appear in crowds. In fact, features available for crowd discrimination largely depend on the crowd density to the extent that people are only seen as blobs in a highly dense scene. We tackle this problem with a growing CNN which can progressively increase its capacity to account for the wide variability seen in crowd scenes. Our model starts from a base CNN density regressor, which is trained in equivalence on all types of crowd images. In order to adapt with the huge diversity, we create two child regressors which are exact copies of the base CNN. A differential training procedure divides the dataset into two clusters and fine-tunes the child networks on their respective specialties. Consequently, without any hand-crafted criteria for forming specialties, the child regressors become experts on certain types of crowds. The child networks are again split recursively, creating two experts at every division. This hierarchical training leads to a CNN tree, where the child regressors are more fine experts than any of their parents. The leaf nodes are taken as the final experts and a classifier network is then trained to predict the correct specialty for a given test image patch. The proposed model achieves higher count accuracy on major crowd datasets. Further, we analyse the characteristics of specialties mined automatically by our method.

##### Abstract (translated by Google)
在人群图像中自动计数人是一项具有挑战性的任务。主要困难源于人们在人群中出现的方式的多样性。事实上，可用于人群歧视的功能在很大程度上取决于人群密度，以至于人们在高密度场景中仅被视为斑点。我们通过不断增长的CNN来解决这个问题，CNN可以逐步增加其容量以解决人群场景中的广泛变化。我们的模型从基础CNN密度回归器开始，该回归器在所有类型的人群图像上进行等效训练。为了适应巨大的多样性，我们创建了两个子回归器，它们是基本CNN的精确副本。差异训练程序将数据集划分为两个群集，并根据各自的专业对子网络进行微调。因此，在没有任何手工制作的专业标准的情况下，儿童回归者成为某些类型群体的专家。子网络再次递归分割，在每个部门创建两名专家。这种分级培训导致CNN树，其中儿童回归者比他们的父母更优秀的专家。将叶节点作为最终专家，然后训练分类器网络以预测给定测试图像块的正确特征。所提出的模型在主要人群数据集上实现了更高的计数准确度。此外，我们分析了我们的方法自动开采的特色的特点。

##### URL
[http://arxiv.org/abs/1807.09993](http://arxiv.org/abs/1807.09993)

##### PDF
[http://arxiv.org/pdf/1807.09993](http://arxiv.org/pdf/1807.09993)

