---
layout: post
title: "Unsupervised Classification of PolSAR Data Using a Scattering Similarity Measure Derived from a Geodesic Distance"
date: 2017-12-01 17:58:42
categories: arXiv_CV
tags: arXiv_CV Classification
author: Debanshu Ratha, Avik Bhattacharya, Alejandro C. Frery
mathjax: true
---

* content
{:toc}

##### Abstract
In this letter, we propose a novel technique for obtaining scattering components from Polarimetric Synthetic Aperture Radar (PolSAR) data using the geodesic distance on the unit sphere. This geodesic distance is obtained between an elementary target and the observed Kennaugh matrix, and it is further utilized to compute a similarity measure between scattering mechanisms. The normalized similarity measure for each elementary target is then modulated with the total scattering power (Span). This measure is used to categorize pixels into three categories i.e. odd-bounce, double-bounce and volume, depending on which of the above scattering mechanisms dominate. Then the maximum likelihood classifier of [J.-S. Lee, M. R. Grunes, E. Pottier, and L. Ferro-Famil, Unsupervised terrain classification preserving polarimetric scattering characteristics, IEEE Trans. Geos. Rem. Sens., vol. 42, no. 4, pp. 722731, April 2004.] based on the complex Wishart distribution is iteratively used for each category. Dominant scattering mechanisms are thus preserved in this classification scheme. We show results for L-band AIRSAR and ALOS-2 datasets acquired over San Francisco and Mumbai, respectively. The scattering mechanisms are better preserved using the proposed methodology than the unsupervised classification results using the Freeman-Durden scattering powers on an orientation angle (OA) corrected PolSAR image. Furthermore, (1) the scattering similarity is a completely non-negative quantity unlike the negative powers that might occur in double- bounce and odd-bounce scattering component under Freeman Durden decomposition (FDD), and (2) the methodology can be extended to more canonical targets as well as for bistatic scattering.

##### Abstract (translated by Google)
在这封信中，我们提出了一种利用单位球上的测地距离从极化合成孔径雷达（PolSAR）数据获得散射分量的新技术。这个测地距离是在基本目标和观测Kennaugh矩阵之间获得的，并且还用于计算散射机制之间的相似性度量。然后用总散射功率（Span）调制每个基本目标的归一化相似性度量。这种测量被用于将像素分类成三类，即奇数反弹，双反弹和音量，这取决于上述哪种散射机制占优势。那么[J.-S.的最大似然分类器] Lee，M. R. Grunes，E. Pottier和L. Ferro-Famil，Unsupervised terrain classification preserving polarimetric scattering characteristics，IEEE Trans。 GEOS。雷姆。 Sens。，vol。 42，没有。 4，第722731页，2004年4月。]基于复杂的Wishart分布迭代用于每个类别。这种分类方案保留了主导散射机制。我们分别展示了在旧金山和孟买收购的L波段AIRSAR和ALOS-2数据集的结果。使用所提出的方法比使用定向角（OA）校正的PolSAR图像上的Freeman-Durden散射功率的无监督分类结果更好地保留散射机制。此外，（1）散射相似性是完全非负的量，不同于在Freeman Durden分解（FDD）下的双反弹和奇反弹散射分量中可能发生的负功率，并且（2）方法可以扩展到更典型的目标以及双基地散射。

##### URL
[https://arxiv.org/abs/1712.00427](https://arxiv.org/abs/1712.00427)

##### PDF
[https://arxiv.org/pdf/1712.00427](https://arxiv.org/pdf/1712.00427)

