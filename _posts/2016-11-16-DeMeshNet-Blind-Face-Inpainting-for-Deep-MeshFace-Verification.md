---
layout: post
title: "DeMeshNet: Blind Face Inpainting for Deep MeshFace Verification"
date: 2016-11-16 13:36:45
categories: arXiv_CV
tags: arXiv_CV GAN Face Optimization
author: Shu Zhang, Ran He, Tieniu Tan
mathjax: true
---

* content
{:toc}

##### Abstract
MeshFace photos have been widely used in many Chinese business organizations to protect ID face photos from being misused. The occlusions incurred by random meshes severely degenerate the performance of face verification systems, which raises the MeshFace verification problem between MeshFace and daily photos. Previous methods cast this problem as a typical low-level vision problem, i.e. blind inpainting. They recover perceptually pleasing clear ID photos from MeshFaces by enforcing pixel level similarity between the recovered ID images and the ground-truth clear ID images and then perform face verification on them. Essentially, face verification is conducted on a compact feature space rather than the image pixel space. Therefore, this paper argues that pixel level similarity and feature level similarity jointly offer the key to improve the verification performance. Based on this insight, we offer a novel feature oriented blind face inpainting framework. Specifically, we implement this by establishing a novel DeMeshNet, which consists of three parts. The first part addresses blind inpainting of the MeshFaces by implicitly exploiting extra supervision from the occlusion position to enforce pixel level similarity. The second part explicitly enforces a feature level similarity in the compact feature space, which can explore informative supervision from the feature space to produce better inpainting results for verification. The last part copes with face alignment within the net via a customized spatial transformer module when extracting deep facial features. All the three parts are implemented within an end-to-end network that facilitates efficient optimization. Extensive experiments on two MeshFace datasets demonstrate the effectiveness of the proposed DeMeshNet as well as the insight of this paper.

##### Abstract (translated by Google)
MeshFace照片已被广泛用于许多中国商业机构，以保护身份证照片不被滥用。随机网格产生的遮挡严重影响了人脸验证系统的性能，提高了MeshFace与日常照片之间的MeshFace验证问题。以前的方法把这个问题作为一个典型的低级视觉问题，即盲目的修补。他们通过强化恢复的ID图像和事实清晰的ID图像之间的像素级相似性，从MeshFaces中恢复令人愉悦的清晰的ID照片，然后对它们进行面部验证。本质上，脸部验证是在紧凑的特征空间而不是图像像素空间上进行的。因此，本文认为像素级相似性和特征级相似性共同为提高验证性能提供了关键。基于这种见解，我们提供了一种新颖的面向特征的盲脸修复框架。具体来说，我们通过建立一个新的DeMeshNet来实现这个，它由三部分组成。第一部分通过隐式地利用遮挡位置的额外监督来强化像素级的相似性，从而对MeshFaces进行盲目的修复。第二部分在紧凑的特征空间中明确强调特征级别的相似性，从特征空间探索信息监督，为验证提供更好的修复效果。最后一部分通过一个自定义的空间变换器模块在网络中处理人脸对齐时提取深部的面部特征。所有这三个部分都是在一个端到端的网络中实现的，这有利于高效的优化。对两个MeshFace数据集的大量实验证明了所提出的DeMeshNet的有效性以及本文的见解。

##### URL
[https://arxiv.org/abs/1611.05271](https://arxiv.org/abs/1611.05271)

##### PDF
[https://arxiv.org/pdf/1611.05271](https://arxiv.org/pdf/1611.05271)

