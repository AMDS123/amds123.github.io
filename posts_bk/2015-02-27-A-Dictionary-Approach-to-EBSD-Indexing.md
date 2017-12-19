---
layout: post
title: "A Dictionary Approach to EBSD Indexing"
date: 2015-02-27 20:29:28
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Yu-Hui Chen, Se Un Park, Dennis Wei, Gregory Newstadt, Michael Jackson, Jeff P. Simmons, Marc De Graef, Alfred O. Hero
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a framework for indexing of grain and sub-grain structures in electron backscatter diffraction (EBSD) images of polycrystalline materials. The framework is based on a previously introduced physics-based forward model by Callahan and De Graef (2013) relating measured patterns to grain orientations (Euler angle). The forward model is tuned to the microscope and the sample symmetry group. We discretize the domain of the forward model onto a dense grid of Euler angles and for each measured pattern we identify the most similar patterns in the dictionary. These patterns are used to identify boundaries, detect anomalies, and index crystal orientations. The statistical distribution of these closest matches is used in an unsupervised binary decision tree (DT) classifier to identify grain boundaries and anomalous regions. The DT classifies a pattern as an anomaly if it has an abnormally low similarity to any pattern in the dictionary. It classifies a pixel as being near a grain boundary if the highly ranked patterns in the dictionary differ significantly over the pixels 3x3 neighborhood. Indexing is accomplished by computing the mean orientation of the closest dictionary matches to each pattern. The mean orientation is estimated using a maximum likelihood approach that models the orientation distribution as a mixture of Von Mises-Fisher distributions over the quaternionic 3-sphere. The proposed dictionary matching approach permits segmentation, anomaly detection, and indexing to be performed in a unified manner with the additional benefit of uncertainty quantification. We demonstrate the proposed dictionary-based approach on a Ni-base IN100 alloy.

##### Abstract (translated by Google)
我们提出了一个在多晶材料的电子背散射衍射（EBSD）图像中的晶粒和亚晶粒结构索引的框架。该框架基于Callahan和De Graef（2013）先前介绍的基于物理学的前向模型，将测量的模式与晶粒取向（欧拉角）相关联。正向模型被调整到显微镜和样品对称组。我们将正演模型的域离散到欧拉角的密集网格上，对于每个测量模式，我们确定字典中最相似的模式。这些模式用于识别边界，检测异常，并指示晶体的方向。这些最接近匹配的统计分布用于无监督的二元决策树（DT）分类器中以识别晶界和异常区域。如果DT与字典中的任何模式具有异常低的相似性，则DT将该模式归类为异常。如果字典中高度排列的图案在像素3×3邻域上显着不同，则将像素分类为接近晶界。索引是通过计算最接近字典匹配每个模式的平均方向来完成的。使用最大似然方法来估计平均取向，该方法将取向分布建模为四元三球上的Von Mises-Fisher分布的混合。所提出的字典匹配方法允许以不确定性量化的附加益处以统一的方式执行分割，异常检测和索引。我们展示了在镍基IN100合金上提出的基于字典的方法。

##### URL
[https://arxiv.org/abs/1502.07436](https://arxiv.org/abs/1502.07436)

##### PDF
[https://arxiv.org/pdf/1502.07436](https://arxiv.org/pdf/1502.07436)

