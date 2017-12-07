---
layout: post
title: "Learning 6-DOF Grasping Interaction with Deep Geometry-aware 3D Representations"
date: 2017-12-04 18:57:26
categories: arXiv_CV
tags: arXiv_CV
author: Xinchen Yan, Jasmine Hsu, Mohi Khansari, Yunfei Bai, Arkanath Pathak, Abhinav Gupta, James Davidson, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on the problem of learning 6-DOF grasping with a parallel jaw gripper in simulation. We propose the notion of a geometry-aware representation in grasping based on the assumption that knowledge of 3D geometry is at the heart of interaction. Our key idea is constraining and regularizing grasping interaction learning through 3D geometry prediction. Specifically, we formulate the learning of deep geometry-aware grasping model in two steps: First, we learn to build mental geometry-aware representation by reconstructing the scene (i.e., 3D occupancy grid) from RGBD input via generative 3D shape modeling. Second, we learn to predict grasping outcome with its internal geometry-aware representation. The learned outcome prediction model is used to sequentially propose grasping solutions via analysis-by-synthesis optimization. Our contributions are fourfold: (1) To best of our knowledge, we are presenting for the first time a method to learn a 6-DOF grasping net from RGBD input; (2) We build a grasping dataset from demonstrations in virtual reality with rich sensory and interaction annotations. This dataset includes 101 everyday objects spread across 7 categories, additionally, we propose a data augmentation strategy for effective learning; (3) We demonstrate that the learned geometry-aware representation leads to about 10 percent relative performance improvement over the baseline CNN on grasping objects from our dataset. (4) We further demonstrate that the model generalizes to novel viewpoints and object instances.

##### Abstract (translated by Google)
本文重点研究了用平行爪夹钳模拟学习6自由度的问题。我们基于三维几何知识处于相互作用的核心的假设，提出了基于几何意义的表示的概念。我们的主要思想是通过三维几何预测来约束和规范掌握交互学习。具体来说，我们通过两个步骤来制定深度几何意识的抓取模型的学习：首先，我们学习通过从生成的三维形状建模的RGBD输入重构场景（即3D占用网格）来建立心理几何感知表示。其次，我们学习用内部几何感知表示来预测抓握结果。学习结果预测模型被用于通过综合分析优化顺序地提出抓取解决方案。我们的贡献有四个方面：（1）据我们所知，我们首次提出了一种从RGBD输入学习六自由度抓网的方法; （2）通过丰富的感官和交互注释，从虚拟现实中的示范中建立一个抓取数据集。这个数据集包括101个日常对象，分布在7个类别，另外，我们提出了一个有效学习的数据增强策略; （3）我们证明了学习的几何感知表示可以使我们的数据集中的对象从基线CNN上获得10％的相对性能提升。 （4）我们进一步证明该模型推广到新颖的观点和对象实例。

##### URL
[http://arxiv.org/abs/1708.07303](http://arxiv.org/abs/1708.07303)

##### PDF
[http://arxiv.org/pdf/1708.07303](http://arxiv.org/pdf/1708.07303)

