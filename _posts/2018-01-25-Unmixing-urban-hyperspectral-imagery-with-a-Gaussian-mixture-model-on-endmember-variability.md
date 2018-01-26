---
layout: post
title: "Unmixing urban hyperspectral imagery with a Gaussian mixture model on endmember variability"
date: 2018-01-25 18:22:22
categories: arXiv_CV
tags: arXiv_CV
author: Yuan Zhou, Erin B. Wetherley, Paul D. Gader
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we model a pixel as a linear combination of endmembers sampled from probability distributions of Gaussian mixture models (GMM). The parameters of the GMM distributions are estimated using spectral libraries. Abundances are estimated based on the distribution parameters. The advantage of this algorithm is that the model size grows very slowly as a function of the library size. To validate this method, we used data collected by the AVIRIS sensor over the Santa Barbara region: two 16 m spatial resolution and two 4 m spatial resolution images. 64 validated regions of interest (ROI) (180 m by 180 m) were used to assess estimate accuracy. Ground truth was obtained using 1 m images leading to the following 6 classes: turfgrass, non-photosynthetic vegetation (NPV), paved, roof, soil, and tree. Spectral libraries were built by manually identifying and extracting pure spectra from both resolution images, resulting in 3,287 spectra at 16 m and 15,426 spectra at 4 m. We then unmixed ROIs of each resolution using the following unmixing algorithms: the set-based algorithms MESMA and AAM, and the distribution-based algorithms GMM, NCM, and BCM. The original libraries were used for the distribution-based algorithms whereas set-based methods required a sophisticated reduction method, resulting in reduced libraries of 61 spectra at 16 m and 95 spectra at 4 m. The results show that GMM performs best among the distribution-based methods, producing comparable accuracy to MESMA, and may be more robust across datasets.

##### Abstract (translated by Google)
在本文中，我们将像素模型化为从高斯混合模型（GMM）的概率分布采样的端元的线性组合。 GMM分布的参数是使用谱库估计的。丰度是根据分配参数估算的。这个算法的优点在于，模型的大小随着库的大小而增长非常缓慢。为了验证这种方法，我们使用AVIRIS传感器在圣巴巴拉地区收集的数据：两个16米的空间分辨率和两个4米的空间分辨率图像。 64个经验证的感兴趣区域（ROI）（180米×180米）被用来评估估计的准确性。使用1m图像获得了地面实况，导致以下6个类别：草皮，非光合植被（NPV），铺面，屋顶，土壤和树木。通过手动识别和提取来自两个分辨率图像的纯光谱来建立谱库，得到16μm处的3287个光谱和4μm处的15,426个光谱。然后，我们使用以下解混算法来解混每个分辨率的ROI：基于集合的算法MESMA和AAM，以及基于分布的算法GMM，NCM和BCM。原始库被用于基于分布的算法，而基于集合的方法则需要复杂的还原方法，导致在16μm和在4μm的95个谱处谱减少了61个谱图。结果表明，GMM在基于分布的方法中性能最好，与MESMA的准确性相当，并且在数据集中可能更稳健。

##### URL
[http://arxiv.org/abs/1801.08513](http://arxiv.org/abs/1801.08513)

##### PDF
[http://arxiv.org/pdf/1801.08513](http://arxiv.org/pdf/1801.08513)

