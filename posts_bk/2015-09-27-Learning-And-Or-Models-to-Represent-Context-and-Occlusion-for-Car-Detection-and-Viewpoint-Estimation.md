---
layout: post
title: "Learning And-Or Models to Represent Context and Occlusion for Car Detection and Viewpoint Estimation"
date: 2015-09-27 08:25:35
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised GAN Detection
author: Tianfu Wu, Bo Li, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method for learning And-Or models to represent context and occlusion for car detection and viewpoint estimation. The learned And-Or model represents car-to-car context and occlusion configurations at three levels: (i) spatially-aligned cars, (ii) single car under different occlusion configurations, and (iii) a small number of parts. The And-Or model embeds a grammar for representing large structural and appearance variations in a reconfigurable hierarchy. The learning process consists of two stages in a weakly supervised way (i.e., only bounding boxes of single cars are annotated). Firstly, the structure of the And-Or model is learned with three components: (a) mining multi-car contextual patterns based on layouts of annotated single car bounding boxes, (b) mining occlusion configurations between single cars, and (c) learning different combinations of part visibility based on car 3D CAD simulation. The And-Or model is organized in a directed and acyclic graph which can be inferred by Dynamic Programming. Secondly, the model parameters (for appearance, deformation and bias) are jointly trained using Weak-Label Structural SVM. In experiments, we test our model on four car detection datasets --- the KITTI dataset \cite{Geiger12}, the PASCAL VOC2007 car dataset~\cite{pascal}, and two self-collected car datasets, namely the Street-Parking car dataset and the Parking-Lot car dataset, and three datasets for car viewpoint estimation --- the PASCAL VOC2006 car dataset~\cite{pascal}, the 3D car dataset~\cite{savarese}, and the PASCAL3D+ car dataset~\cite{xiang_wacv14}. Compared with state-of-the-art variants of deformable part-based models and other methods, our model achieves significant improvement consistently on the four detection datasets, and comparable performance on car viewpoint estimation.

##### Abstract (translated by Google)
本文提出了一种学习And-Or模型来表示车辆检测和视点估计的上下文和遮挡的方法。学习的And-Or模型在三个层次上表示汽车到汽车的环境和遮挡配置：（i）空间对齐的汽车，（ii）单个汽车在不同的遮挡配置下，以及（iii）少量的部件。 And-Or模型在可重构层次结构中嵌入用于表示大的结构和外观变化的语法。学习过程由两个阶段以弱监督的方式组成（即，只有单车的边界框被注释）。首先，学习And-Or模型的结构，包括三个部分：（a）基于带注释的单车边界框布局挖掘多车情景模式;（b）挖掘单车之间的遮挡配置;（c）学习基于汽车3D CAD模拟的零件可见度的不同组合。 And-Or模型被组织成有向无环图，可以通过动态规划来推断。其次，使用弱标签结构SVM联合训练模型参数（外观，变形和偏差）。在实验中，我们在四个汽车检测数据集上测试了我们的模型 -  KITTI数据集\Cite {Geiger12}，PASCAL VOC2007汽车数据集以及两个自我收集的汽车数据集，即Street-Parking汽车数据集和停车场车辆数据集，以及用于汽车视点估计的三个数据集--- PASCAL VOC2006汽车数据集〜\ cite {pascal}，3D汽车数据集〜\ cite {savarese}以及PASCAL3D +汽车数据集〜\ cite {} xiang_wacv14。与可变形的基于零件的模型和其他方法的最新变体相比，我们的模型在四个检测数据集上实现了显着的改进，并且在汽车视点估计上具有可比较的性能。

##### URL
[https://arxiv.org/abs/1501.07359](https://arxiv.org/abs/1501.07359)

##### PDF
[https://arxiv.org/pdf/1501.07359](https://arxiv.org/pdf/1501.07359)

