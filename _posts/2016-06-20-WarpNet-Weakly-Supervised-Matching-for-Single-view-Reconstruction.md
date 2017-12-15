---
layout: post
title: "WarpNet: Weakly Supervised Matching for Single-view Reconstruction"
date: 2016-06-20 09:40:46
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised Deep_Learning
author: Angjoo Kanazawa, David W. Jacobs, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach to matching images of objects in fine-grained datasets without using part annotations, with an application to the challenging problem of weakly supervised single-view reconstruction. This is in contrast to prior works that require part annotations, since matching objects across class and pose variations is challenging with appearance features alone. We overcome this challenge through a novel deep learning architecture, WarpNet, that aligns an object in one image with a different object in another. We exploit the structure of the fine-grained dataset to create artificial data for training this network in an unsupervised-discriminative learning approach. The output of the network acts as a spatial prior that allows generalization at test time to match real images across variations in appearance, viewpoint and articulation. On the CUB-200-2011 dataset of bird categories, we improve the AP over an appearance-only network by 13.6%. We further demonstrate that our WarpNet matches, together with the structure of fine-grained datasets, allow single-view reconstructions with quality comparable to using annotated point correspondences.

##### Abstract (translated by Google)
我们提出一种方法来匹配细粒度数据集中的对象的图像，而不使用部分注释，以及应用于弱监督单视图重建的具有挑战性的问题。这与之前的需要部分注释的作品形成对比，因为跨类别和姿势变化的匹配对象仅凭外观特征是具有挑战性的。我们通过一种新颖的深度学习体系结构WarpNet克服了这个挑战，将一个图像中的对象与另一个对象中的对象对齐。我们利用细粒度数据集的结构来创建人工数据，以无监督区分的学习方法来训练这个网络。网络的输出作为一个空间先验，允许在测试时间进行泛化，以匹配外观，观点和清晰度变化的实际图像。在鸟类的CUB-200-2011数据集中，我们通过仅有外观的网络将AP改善了13.6％。我们进一步证明，我们的WarpNet匹配，与细粒度数据集的结构一起，允许单视图重建质量与使用注释点对应关系相媲美。

##### URL
[https://arxiv.org/abs/1604.05592](https://arxiv.org/abs/1604.05592)

##### PDF
[https://arxiv.org/pdf/1604.05592](https://arxiv.org/pdf/1604.05592)

