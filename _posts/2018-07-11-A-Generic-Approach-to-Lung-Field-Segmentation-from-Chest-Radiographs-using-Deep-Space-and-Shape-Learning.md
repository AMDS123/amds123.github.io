---
layout: post
title: "A Generic Approach to Lung Field Segmentation from Chest Radiographs using Deep Space and Shape Learning"
date: 2018-07-11 20:17:25
categories: arXiv_CV
tags: arXiv_CV Segmentation Represenation_Learning Deep_Learning Detection
author: Awais Mansoor, Juan J. Cerrolaza, Geovanny Perez, Elijah Biggs, Kazunori Okada, Gustavo Nino, Marius George Linguraru
mathjax: true
---

* content
{:toc}

##### Abstract
Computer-aided diagnosis (CAD) techniques for lung field segmentation from chest radiographs (CXR) have been proposed for adult cohorts, but rarely for pediatric subjects. Statistical shape models (SSMs), the workhorse of most state-of-the-art CXR-based lung field segmentation methods, do not efficiently accommodate shape variation of the lung field during the pediatric developmental stages. The main contributions of our work are: (1) a generic lung field segmentation framework from CXR accommodating large shape variation for adult and pediatric cohorts; (2) a deep representation learning detection mechanism, \emph{ensemble space learning}, for robust object localization; and (3) \emph{marginal shape deep learning} for the shape deformation parameter estimation. Unlike the iterative approach of conventional SSMs, the proposed shape learning mechanism transforms the parameter space into marginal subspaces that are solvable efficiently using the recursive representation learning mechanism. Furthermore, our method is the first to include the challenging retro-cardiac region in the CXR-based lung segmentation for accurate lung capacity estimation. The framework is evaluated on 668 CXRs of patients between 3 month to 89 year of age. We obtain a mean Dice similarity coefficient of $0.96\pm0.03$ (including the retro-cardiac region). For a given accuracy, the proposed approach is also found to be faster than conventional SSM-based iterative segmentation methods. The computational simplicity of the proposed generic framework could be similarly applied to the fast segmentation of other deformable objects.

##### Abstract (translated by Google)
已经为成人队列提出了用于胸部X射线照片（CXR）的肺野分割的计算机辅助诊断（CAD）技术，但很少用于儿科受试者。统计形状模型（SSM）是大多数最先进的基于CXR的肺野分割方法的主力，在儿科发育阶段不能有效地适应肺野的形状变化。我们工作的主要贡献是：（1）CXR的通用肺野分割框架，适用于成人和儿科队列的大形状变异; （2）深度表示学习检测机制，\ emph {集合空间学习}，用于鲁棒的对象定位; （3）\ emph {边缘形状深度学习}用于形状变形参数估计。与传统SSM的迭代方法不同，所提出的形状学习机制将参数空间转换为可使用递归表示学习机制有效解决的边缘子空间。此外，我们的方法首先在基于CXR的肺部分割中包括具有挑战性的逆心脏区域，以进行准确的肺容量估计。该框架在3个月至89岁之间的668名患者的CXR上进行评估。我们得到的平均骰子相似系数为0.96美元\ pm0.03 $（包括复古心脏区域）。对于给定的精度，还发现所提出的方法比传统的基于SSM的迭代分割方法更快。所提出的通用框架的计算简单性可以类似地应用于其他可变形对象的快速分割。

##### URL
[http://arxiv.org/abs/1807.04339](http://arxiv.org/abs/1807.04339)

##### PDF
[http://arxiv.org/pdf/1807.04339](http://arxiv.org/pdf/1807.04339)

