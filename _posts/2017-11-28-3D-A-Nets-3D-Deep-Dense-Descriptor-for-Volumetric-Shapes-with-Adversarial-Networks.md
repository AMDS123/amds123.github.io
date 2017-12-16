---
layout: post
title: "3D-A-Nets: 3D Deep Dense Descriptor for Volumetric Shapes with Adversarial Networks"
date: 2017-11-28 04:01:20
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN RNN Classification
author: Mengwei Ren, Liang Niu, Yi Fang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently researchers have been shifting their focus towards learned 3D shape descriptors from hand-craft ones to better address challenging issues of the deformation and structural variation inherently present in 3D objects. 3D geometric data are often transformed to 3D Voxel grids with regular format in order to be better fed to a deep neural net architecture. However, the computational intractability of direct application of 3D convolutional nets to 3D volumetric data severely limits the efficiency (i.e. slow processing) and effectiveness (i.e. unsatisfied accuracy) in processing 3D geometric data. In this paper, powered with a novel design of adversarial networks (3D-A-Nets), we have developed a novel 3D deep dense shape descriptor (3D-DDSD) to address the challenging issues of efficient and effective 3D volumetric data processing. We developed new definition of 2D multilayer dense representation (MDR) of 3D volumetric data to extract concise but geometrically informative shape description and a novel design of adversarial networks that jointly train a set of convolution neural network (CNN), recurrent neural network (RNN) and an adversarial discriminator. More specifically, the generator network produces 3D shape features that encourages the clustering of samples from the same category with correct class label, whereas the discriminator network discourages the clustering by assigning them misleading adversarial class labels. By addressing the challenges posed by the computational inefficiency of direct application of CNN to 3D volumetric data, 3D-A-Nets can learn high-quality 3D-DSDD which demonstrates superior performance on 3D shape classification and retrieval over other state-of-the-art techniques by a great margin.

##### Abstract (translated by Google)
最近，研究人员已经将注意力转移到手工工艺的3D形状描述符上，以更好地解决3D物体本身存在的变形和结构变化这些具有挑战性的问题。 3D几何数据通常被转换为3D Voxel网格，以便更好地馈送到深度神经网络体系结构。然而，将3D卷积网直接应用于3D体数据的计算困难性严重地限制了在处理3D几何数据中的效率（即，慢处理）和有效性（即，不满意的精度）。本文以一种新颖的对抗网络设计（3D-A-Nets）为基础，开发了一种新颖的3D深度形状描述子（3D-DDSD），以解决高效和有效的三维体积数据处理的挑战性问题。我们开发了三维体积数据的二维多层密集表示（MDR）的新定义，以提取简洁但几何信息丰富的形状描述和新的联合训练一组卷积神经网络（CNN），递归神经网络（RNN）和一个敌对的鉴别者。更具体地说，发生器网络产生三维形状特征，鼓励用相同类别的样本对正确的类别标签进行聚类，而鉴别器网络通过给它们分配具有误导性的对抗类别标签来阻止聚类。通过解决CNN直接应用于三维体数据的计算效率低下所带来的挑战，3D-A-Nets可以学习高质量的3D-DSDD，该3D-DSDD在三维形状分类和检索上优于其他先进的3D-艺术技巧大幅度提高。

##### URL
[https://arxiv.org/abs/1711.10108](https://arxiv.org/abs/1711.10108)

##### PDF
[https://arxiv.org/pdf/1711.10108](https://arxiv.org/pdf/1711.10108)

