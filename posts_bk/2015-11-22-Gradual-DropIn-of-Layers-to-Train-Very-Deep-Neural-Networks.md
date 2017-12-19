---
layout: post
title: "Gradual DropIn of Layers to Train Very Deep Neural Networks"
date: 2015-11-22 02:33:08
categories: arXiv_CV
tags: arXiv_CV Regularization GAN
author: Leslie N. Smith, Emily M. Hand, Timothy Doster
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the concept of dynamically growing a neural network during training. In particular, an untrainable deep network starts as a trainable shallow network and newly added layers are slowly, organically added during training, thereby increasing the network's depth. This is accomplished by a new layer, which we call DropIn. The DropIn layer starts by passing the output from a previous layer (effectively skipping over the newly added layers), then increasingly including units from the new layers for both feedforward and backpropagation. We show that deep networks, which are untrainable with conventional methods, will converge with DropIn layers interspersed in the architecture. In addition, we demonstrate that DropIn provides regularization during training in an analogous way as dropout. Experiments are described with the MNIST dataset and various expanded LeNet architectures, CIFAR-10 dataset with its architecture expanded from 3 to 11 layers, and on the ImageNet dataset with the AlexNet architecture expanded to 13 layers and the VGG 16-layer architecture.

##### Abstract (translated by Google)
我们介绍在训练过程中动态生长一个神经网络的概念。尤其是，一个不可排除的深层网络开始作为一个可训练的浅层网络，新增加的层在培训期间被缓慢有机地添加，从而增加了网络的深度。这是通过一个我们称之为DropIn的新图层完成的。 DropIn层通过传递前一层的输出（有效地跳过新添加的层）开始，然后逐渐包括来自新层的单位，用于前馈和后向传播。我们展示了用传统方法无法消除的深层网络将与散布在体系结构中的DropIn层相汇合。另外，我们证明DropIn在训练期间以类似的方式提供正常化作为辍学。使用MNIST数据集和各种扩展的LeNet体系结构，CIFAR-10数据集的体系结构从3层扩展到11层，以及将ImageNet数据集的AlexNet体系结构扩展到13层以及VGG 16层体系结构来描述实验。

##### URL
[https://arxiv.org/abs/1511.06951](https://arxiv.org/abs/1511.06951)

##### PDF
[https://arxiv.org/pdf/1511.06951](https://arxiv.org/pdf/1511.06951)

