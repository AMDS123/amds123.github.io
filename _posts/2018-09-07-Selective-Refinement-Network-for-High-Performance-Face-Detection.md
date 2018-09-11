---
layout: post
title: "Selective Refinement Network for High Performance Face Detection"
date: 2018-09-07 22:00:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Classification Detection Face_Detection
author: Cheng Chi, Shifeng Zhang, Junliang Xing, Zhen Lei, Stan Z. Li, Xudong Zou
mathjax: true
---

* content
{:toc}

##### Abstract
High performance face detection remains a very challenging problem, especially when there exists many tiny faces. This paper presents a novel single-shot face detector, named Selective Refinement Network (SRN), which introduces novel two-step classification and regression operations selectively into an anchor-based face detector to reduce false positives and improve location accuracy simultaneously. In particular, the SRN consists of two modules: the Selective Two-step Classification (STC) module and the Selective Two-step Regression (STR) module. The STC aims to filter out most simple negative anchors from low level detection layers to reduce the search space for the subsequent classifier, while the STR is designed to coarsely adjust the locations and sizes of anchors from high level detection layers to provide better initialization for the subsequent regressor. Moreover, we design a Receptive Field Enhancement (RFE) block to provide more diverse receptive field, which helps to better capture faces in some extreme poses. As a consequence, the proposed SRN detector achieves state-of-the-art performance on all the widely used face detection benchmarks, including AFW, PASCAL face, FDDB, and WIDER FACE datasets. Codes will be released to facilitate further studies on the face detection problem.

##### Abstract (translated by Google)
高性能人脸检测仍然是一个非常具有挑战性的问题，尤其是当存在许多小脸时。本文提出了一种新型的单镜头人脸检测器，命名为选择性细化网络（SRN），它将选择性地引入新的两步分类和回归操作到基于锚的人脸检测器中，以减少误报并同时提高定位精度。特别是，SRN由两个模块组成：选择性两步分类（STC）模块和选择性两步回归（STR）模块。 STC旨在从低级检测层中过滤掉大多数简单的负锚，以减少后续分类器的搜索空间，而STR旨在从高级检测层粗略调整锚的位置和大小，以便为随后的回归量。此外，我们设计了一个感受野增强（RFE）模块，以提供更多样化的感受野，这有助于更好地捕捉某些极端姿势的面部。因此，所提出的SRN检测器在所有广泛使用的面部检测基准上实现了最先进的性能，包括AFW，PASCAL面，FDDB和WIDER FACE数据集。将发布代码以促进对面部检测问题的进一步研究。

##### URL
[http://arxiv.org/abs/1809.02693](http://arxiv.org/abs/1809.02693)

##### PDF
[http://arxiv.org/pdf/1809.02693](http://arxiv.org/pdf/1809.02693)

