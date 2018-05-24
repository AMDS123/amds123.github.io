---
layout: post
title: "Deformable Part Networks"
date: 2018-05-22 18:35:28
categories: arXiv_CV
tags: arXiv_CV Detection Relation Recognition
author: Ziming Zhang, Rongmei Lin, Alan Sullivan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose novel Deformable Part Networks (DPNs) to learn {\em pose-invariant} representations for 2D object recognition. In contrast to the state-of-the-art pose-aware networks such as CapsNet \cite{sabour2017dynamic} and STN \cite{jaderberg2015spatial}, DPNs can be naturally {\em interpreted} as an efficient solver for a challenging detection problem, namely Localized Deformable Part Models (LDPMs) where localization is introduced to DPMs as another latent variable for searching for the best poses of objects over all pixels and (predefined) scales. In particular we construct DPNs as sequences of such LDPM units to model the semantic and spatial relations among the deformable parts as hierarchical composition and spatial parsing trees. Empirically our 17-layer DPN can outperform both CapsNets and STNs significantly on affNIST \cite{sabour2017dynamic}, for instance, by 19.19\% and 12.75\%, respectively, with better generalization and better tolerance to affine transformations.

##### Abstract (translated by Google)
在本文中，我们提出了新颖的可变形部件网络（DPNs）来学习二维物体识别的{\ em姿态不变}表示。与诸如CapsNet \ cite {sabour2017dynamic}和STN \ cite {jaderberg2015spatial}等最先进的姿态感知网络相比，DPN可以自然而然地被解释为解决具有挑战性的检测问题的高效解决方案，即局部化可变形部件模型（LDPM），其中定位被引入DPM作为另一个潜在变量，用于在所有像素和（预定义）尺度上搜索物体的最佳姿态。具体而言，我们构造DPN作为这种LDPM单元的序列，以将可变形部分之间的语义和空间关系建模为分层组成和空间解析树。根据经验，我们的17层DPN可以在affNIST \ cite {sabour2017dynamic}上显着优于CapsNets和STN，例如，分别达到19.19％和12.75％，具有更好的泛化能力和更好的仿射变换容限。

##### URL
[http://arxiv.org/abs/1805.08808](http://arxiv.org/abs/1805.08808)

##### PDF
[http://arxiv.org/pdf/1805.08808](http://arxiv.org/pdf/1805.08808)

