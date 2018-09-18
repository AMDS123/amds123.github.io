---
layout: post
title: "ManifoldNet: A Deep Network Framework for Manifold-valued Data"
date: 2018-09-11 00:27:48
categories: arXiv_CV
tags: arXiv_CV Drone CNN Classification
author: Rudrasis Chakraborty, Jose Bouza, Jonathan Manton, Baba C. Vemuri
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have become the main work horse for many tasks involving learning from data in a variety of applications in Science and Engineering. Traditionally, the input to these networks lie in a vector space and the operations employed within the network are well defined on vector-spaces. In the recent past, due to technological advances in sensing, it has become possible to acquire manifold-valued data sets either directly or indirectly. Examples include but are not limited to data from omnidirectional cameras on automobiles, drones etc., synthetic aperture radar imaging, diffusion magnetic resonance imaging, elastography and conductance imaging in the Medical Imaging domain and others. Thus, there is need to generalize the deep neural networks to cope with input data that reside on curved manifolds where vector space operations are not naturally admissible. In this paper, we present a novel theoretical framework to generalize the widely popular convolutional neural networks (CNNs) to high dimensional manifold-valued data inputs. We call these networks, ManifoldNets. 
 In ManifoldNets, convolution operation on data residing on Riemannian manifolds is achieved via a provably convergent recursive computation of the weighted Fr\'{e}chet Mean (wFM) of the given data, where the weights makeup the convolution mask, to be learned. Further, we prove that the proposed wFM layer achieves a contraction mapping and hence ManifoldNet does not need the non-linear ReLU unit used in standard CNNs. We present experiments, using the ManifoldNet framework, to achieve dimensionality reduction by computing the principal linear subspaces that naturally reside on a Grassmannian. The experimental results demonstrate the efficacy of ManifoldNets in the context of classification and reconstruction accuracy.

##### Abstract (translated by Google)
深度神经网络已经成为许多任务的主要工作，这些任务涉及从科学和工程的各种应用中学习数据。传统上，这些网络的输入位于向量空间中，并且在网络内使用的操作在向量空间上很好地定义。在最近的过去，由于传感技术的进步，已经可以直接或间接地获取多值数据集。示例包括但不限于来自汽车，无人机等上的全向相机，合成孔径雷达成像，扩散磁共振成像，医学成像领域中的弹性成像和电导成像等的数据。因此，需要概括深度神经网络以处理驻留在弯曲流形上的输入数据，其中向量空间操作不是自然可接受的。在本文中，我们提出了一个新的理论框架，将广泛流行的卷积神经网络（CNN）推广到高维流形值数据输入。我们将这些网络称为ManifoldNets。
 在ManifoldNets中，对驻留在黎曼流形上的数据的卷积运算是通过给定数据的加权Fr \'{e} chet Mean（wFM）的可证实收敛的递归计算来实现的，其中权重构成卷积掩模，以便学习。此外，我们证明了所提出的wFM层实现了收缩映射，因此ManifoldNet不需要标准CNN中使用的非线性ReLU单元。我们使用ManifoldNet框架提出实验，通过计算天然存在于格拉斯曼的主线性子空间来实现降维。实验结果证明了ManifoldNets在分类和重建精度方面的功效。

##### URL
[http://arxiv.org/abs/1809.06211](http://arxiv.org/abs/1809.06211)

##### PDF
[http://arxiv.org/pdf/1809.06211](http://arxiv.org/pdf/1809.06211)

