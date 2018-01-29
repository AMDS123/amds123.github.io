---
layout: post
title: "Deep LOGISMOS: Deep Learning Graph-based 3D Segmentation of Pancreatic Tumors on CT scans"
date: 2018-01-25 21:34:44
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Deep_Learning
author: Zhihui Guo, Ling Zhang, Le Lu, Mohammadhadi Bagheri, Ronald M. Summers, Milan Sonka, Jianhua Yao
mathjax: true
---

* content
{:toc}

##### Abstract
This paper reports Deep LOGISMOS approach to 3D tumor segmentation by incorporating boundary information derived from deep contextual learning to LOGISMOS - layered optimal graph image segmentation of multiple objects and surfaces. Accurate and reliable tumor segmentation is essential to tumor growth analysis and treatment selection. A fully convolutional network (FCN), UNet, is first trained using three adjacent 2D patches centered at the tumor, providing contextual UNet segmentation and probability map for each 2D patch. The UNet segmentation is then refined by Gaussian Mixture Model (GMM) and morphological operations. The refined UNet segmentation is used to provide the initial shape boundary to build a segmentation graph. The cost for each node of the graph is determined by the UNet probability maps. Finally, a max-flow algorithm is employed to find the globally optimal solution thus obtaining the final segmentation. For evaluation, we applied the method to pancreatic tumor segmentation on a dataset of 51 CT scans, among which 30 scans were used for training and 21 for testing. With Deep LOGISMOS, DICE Similarity Coefficient (DSC) and Relative Volume Difference (RVD) reached 83.2+-7.8% and 18.6+-17.4% respectively, both are significantly improved (p&lt;0.05) compared with contextual UNet and/or LOGISMOS alone.

##### Abstract (translated by Google)
本文报道深LOGISMOS方法的三维肿瘤分割，纳入深层背景学习的边界信息LOGITHOSOS分层最优图分割的多个对象和表面。准确和可靠的肿瘤分割对肿瘤生长分析和治疗选择至关重要。完全卷积网络（FCN）UNet首先使用以肿瘤为中心的三个相邻2D贴片进行训练，为每个2D贴片提供上下文UNet分割和概率图。然后通过高斯混合模型（GMM）和形态学操作来细化UNet分割。细化的UNet分割用于提供初始形状边界来构建分割图。图的每个节点的成本由UNet概率图确定。最后，采用最大流算法寻找全局最优解，从而得到最终的分割结果。为了进行评价，我们将该方法应用于胰腺肿瘤分割51个CT扫描的数据集，其中30个扫描用于训练，21个用于测试。对于深LOGISMOS，DICE相似系数（DSC）和相对体积差（RVD）分别达到83.2±7.8％和18.6±17.4％，与单独的情景UNet和/或LOGISMOS相比，二者都显着改善（p <0.05）。

##### URL
[http://arxiv.org/abs/1801.08599](http://arxiv.org/abs/1801.08599)

##### PDF
[http://arxiv.org/pdf/1801.08599](http://arxiv.org/pdf/1801.08599)

