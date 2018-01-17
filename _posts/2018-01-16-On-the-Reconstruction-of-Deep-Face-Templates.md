---
layout: post
title: "On the Reconstruction of Deep Face Templates"
date: 2018-01-16 03:15:54
categories: arXiv_CV
tags: arXiv_CV Knowledge Face CNN Recognition Face_Recognition
author: Guangcan Mai, Kai Cao, Pong C. Yuen, Anil K. Jain
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art face recognition systems are based on deep (convolutional) neural networks. Therefore, it is imperative to determine to what extent face templates derived from deep networks can be inverted to obtain the original face image. In this paper, we study the vulnerabilities of a state-of-the-art face recognition system based on template reconstruction attack. We propose a neighborly de-convolutional neural network (\textit{NbNet}) to reconstruct face images from their deep templates. In our experiments, we assumed that no knowledge about the target subject and the deep network are available. To train the \textit{NbNet} reconstruction models, we augmented two benchmark face datasets (VGG-Face and Multi-PIE) with a large collection of images synthesized using a face generator. The proposed reconstruction was evaluated using type-I (comparing the reconstructed images against the original face images used to generate the deep template) and type-II (comparing the reconstructed images against a different face image of the same subject) attacks. Given the images reconstructed from \textit{NbNets}, we show that for verification, we achieve TAR of 95.20\% (58.05\%) on LFW under type-I (type-II) attacks @ FAR of 0.1\%. Besides, 96.58\% (92.84\%) of the images reconstruction from templates of partition \textit{fa} (\textit{fb}) can be identified from partition \textit{fa} in color FERET. Our study demonstrates the need to secure deep templates in face recognition systems.

##### Abstract (translated by Google)
最先进的人脸识别系统基于深度（卷积）神经网络。因此，必须确定从深度网络导出的面部模板在多大程度上可以被倒置以获得原始的面部图像。在本文中，我们研究了基于模板重构攻击的最先进的人脸识别系统的脆弱性。我们提出了一个邻域去卷积神经网络（\ textit {NbNet}）来从他们的深层模板重建人脸图像。在我们的实验中，我们假设没有关于目标主题和深度网络的知识。为了训练\ textit {NbNet}重建模型，我们增加了两个基准面部数据集（VGG-Face和Multi-PIE），其中使用面部生成器合成的大量图像集合。使用类型I（比较重建图像与用于生成深度模板的原始人脸图像）和类型II（针对相同主题的不同人脸图像比较重建图像）来评估所提出的重建。给定从\ textit {NbNets}重建的图像，我们证明为了验证，在类型I（type-II）攻击@ FAR为0.1 \％的情况下，我们在LFW上达到95.20％（58.05％）的TAR。此外，从分区\ textit {fa}（\ textit {fb}）的模板重建的图像的96.58％（92.84％）可以从FERET的分区\ textit {fa}中识别出来。我们的研究表明需要保证人脸识别系统中的深层模板。

##### URL
[http://arxiv.org/abs/1703.00832](http://arxiv.org/abs/1703.00832)

##### PDF
[http://arxiv.org/pdf/1703.00832](http://arxiv.org/pdf/1703.00832)

