---
layout: post
title: "Joint registration and synthesis using a probabilistic model for alignment of MRI and histological sections"
date: 2018-01-16 15:16:05
categories: arXiv_CV
tags: arXiv_CV Inference
author: Juan Eugenio Iglesias, Marc Modat, Loic Peter, Allison Stevens, Roberto Annunziata, Tom Vercauteren, Ed Lein, Bruce Fischl, Sebastien Ourselin
mathjax: true
---

* content
{:toc}

##### Abstract
Nonlinear registration of 2D histological sections with corresponding slices of MRI data is a critical step of 3D histology reconstruction. This task is difficult due to the large differences in image contrast and resolution, as well as the complex nonrigid distortions produced when sectioning the sample and mounting it on the glass slide. It has been shown in brain MRI registration that better spatial alignment across modalities can be obtained by synthesizing one modality from the other and then using intra-modality registration metrics, rather than by using mutual information (MI) as metric. However, such an approach typically requires a database of aligned images from the two modalities, which is very difficult to obtain for histology/MRI. 
 Here, we overcome this limitation with a probabilistic method that simultaneously solves for registration and synthesis directly on the target images, without any training data. In our model, the MRI slice is assumed to be a contrast-warped, spatially deformed version of the histological section. We use approximate Bayesian inference to iteratively refine the probabilistic estimate of the synthesis and the registration, while accounting for each other's uncertainty. Moreover, manually placed landmarks can be seamlessly integrated in the framework for increased performance. 
 Experiments on a synthetic dataset show that, compared with MI, the proposed method makes it possible to use a much more flexible deformation model in the registration to improve its accuracy, without compromising robustness. Moreover, our framework also exploits information in manually placed landmarks more efficiently than MI, since landmarks inform both synthesis and registration - as opposed to registration alone. Finally, we show qualitative results on the public Allen atlas, in which the proposed method provides a clear improvement over MI based registration.

##### Abstract (translated by Google)
二维组织切片与相应切片的MRI数据的非线性配准是3D组织学重建的关键步骤。这个任务是困难的，因为图像对比度和分辨率的巨大差异，以及在将样品切片并将其安装在载玻片上时产生的复杂的非刚性变形。已经在脑MRI注册中显示，通过合成来自另一模态的一种模态，然后使用模式内注册量度而不是通过使用互信息（MI）作为量度，可以获得跨模态的更好空间对准。然而，这种方法通常需要来自两种模式的对准图像的数据库，这对于组织学/ MRI来说是非常难以获得的。
 在这里，我们用概率方法克服了这个限制，同时直接在目标图像上求解配准和合成，而没有任何训练数据。在我们的模型中，MRI切片假定为组织切片的对比度扭曲，空间变形的版本。我们使用近似贝叶斯推理迭代地完善合成和配准的概率估计，同时考虑到彼此的不确定性。而且，手动放置的地标可以无缝地集成在框架中以提高性能。
 在合成数据集上的实验表明，与MI相比，所提出的方法使得可以在配准中使用更灵活的变形模型来提高其准确性，而不损害鲁棒性。此外，我们的框架也比MI更有效地利用手动放置的地标中的信息，因为地标通知合成和注册 - 而不是单独注册。最后，我们在公众艾伦图谱上显示定性结果，其中所提出的方法提供了基于MI的注册的明显改进。

##### URL
[http://arxiv.org/abs/1801.05284](http://arxiv.org/abs/1801.05284)

##### PDF
[http://arxiv.org/pdf/1801.05284](http://arxiv.org/pdf/1801.05284)

