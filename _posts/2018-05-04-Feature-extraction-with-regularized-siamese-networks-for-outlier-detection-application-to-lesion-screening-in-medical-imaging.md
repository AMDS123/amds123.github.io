---
layout: post
title: "Feature extraction with regularized siamese networks for outlier detection: application to lesion screening in medical imaging"
date: 2018-05-04 11:25:02
categories: arXiv_CV
tags: arXiv_CV Detection
author: Z. Alaverdyan, C. Lartizien
mathjax: true
---

* content
{:toc}

##### Abstract
Computer aided diagnosis (CAD) systems are designed to assist clinicians in various tasks, including highlighting abnormal regions in a medical image. A common approach consists in training a voxel-level binary classifier on a set of feature vectors extracted from normal and pathological areas in patients' scans. However, many pathologies (such as epilepsy) are characterized by lesions that may be located anywhere in the brain, have various shapes, sizes and texture. An adequate representation of such a heterogeneity requires a significant amount of annotated data which is a major issue in the medical domain. Therefore, we built on a previously proposed approach that considers epilepsy lesion detection task as a voxel-level outlier detection problem. It consists in building a oc-SVM classifier for each voxel in the brain volume using a small number of clinically-guided features El Azami et al., 2016. Our goal in this study is to make a step forward by replacing the handcrafted features with automatically learnt representations using neural networks. We propose a novel version of siamese networks trained on patches extracted from healthy patients' scans only. This network, composed of stacked autoencoders as subnetworks, is regularized by the reconstruction error of the patches. It is designed to learn representations that bring patches centered at the same voxel localization 'closer' with respect to the chosen metric (i.e. cosine). Finally, the middle layer representations of the subnetworks are fed to oc-SVM classifiers at voxel-level. The method is validated on 3 patients' MRI scans with confirmed epilepsy lesions and shows a promising performance.

##### Abstract (translated by Google)
计算机辅助诊断（CAD）系统旨在帮助临床医生完成各种任务，包括突出显示医学图像中的异常区域。一种常见的方法是在患者扫描中从正常和病理区域提取的一组特征向量上训练体素级二元分类器。然而，许多病理学（例如癫痫）的特征在于可能位于大脑中任何位置的病变，具有各种形状，大小和纹理。这种异质性的充分表示需要大量的注释数据，这是医学领域的主要问题。因此，我们建立在以前提出的方法上，将癫痫病灶检测任务视为体素级异常值检测问题。它包括使用少量的临床指导特征为大脑体积中的每个体素构建一个oc-SVM分类器El Azami等，2016。我们在这项研究中的目标是向前迈进一步，将手工特征替换为使用神经网络自动学习表示。我们提出一个新的版本的暹罗网络培训补丁只从健康的病人扫描提取。这个网络由堆叠的自动编码器组成，如子网络，由补丁的重建错误规则化。它旨在学习以相对于所选度量（即余弦）“相近”的体素定位为中心的贴图。最后，子网的中间层表示以体素级被馈送到oc-SVM分类器。该方法在3例患者确诊癫痫病灶的MRI扫描中得到验证，并显示出良好的表现。

##### URL
[http://arxiv.org/abs/1805.01717](http://arxiv.org/abs/1805.01717)

##### PDF
[http://arxiv.org/pdf/1805.01717](http://arxiv.org/pdf/1805.01717)

