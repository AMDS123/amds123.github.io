---
layout: post
title: "Domain-Specific Face Synthesis for Video Face Recognition from a Single Sample Per Person"
date: 2018-01-06 06:19:52
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Face Classification Recognition Face_Recognition
author: Fania Mokhayeri, Eric Granger, Guillaume-Alexandre Bilodeau
mathjax: true
---

* content
{:toc}

##### Abstract
The performance of still-to-video face recognition (FR) systems can decline significantly because faces captured in the unconstrained operational domain (OD) have a different underlying data distribution compared to faces captured under controlled conditions in the enrollment domain (ED). This is particularly true when individuals are enrolled to the system using a single reference still. To improve the robustness of these systems, it is possible to augment the gallery set by generating synthetic faces based on the original still. However, without the OD knowledge, many synthetic faces must be generated to account for all possible capture conditions. FR systems may therefore require complex implementations and yield lower accuracy when training on less relevant images. This paper introduces an algorithm for domain-specific face synthesis (DSFS) that exploits the representative intra-class variation information available from the OD. Prior to operation (during camera calibration), a compact set of faces from unknown persons appearing in the OD is selected through clustering in the captured condition space. The domain-specific variations of these faces are projected onto the reference still of each individual by integrating an image-based face relighting technique inside a 3D reconstruction framework. A compact set of synthetic faces is generated under the OD capture conditions. In a particular implementation based on sparse representation classification, the synthetic faces generated with the DSFS are employed to form a cross-domain dictionary where the dictionary blocks combine the original and synthetic faces of each individual. Experimental results obtained with the Chokepoint and COX-S2V datasets reveal that augmenting the gallery set using the DSFS approach provide a higher level of accuracy compared to state-of-the-art methods, with only a moderate increase in its complexity.

##### Abstract (translated by Google)
静止视频人脸识别（FR）系统的性能可以显着下降，因为在无约束操作域（OD）中捕获的人脸与在注册域（ED）中受控条件下捕获的人脸具有不同的基础数据分布。当个人使用单个参考静态注册到系统时，情况尤其如此。为了提高这些系统的鲁棒性，可以通过基于原始静态生成合成人脸来增加图库集。但是，如果没有OD知识，必须生成许多合成面，以考虑所有可能的捕获条件。 FR系统因此可能需要复杂的实施，并且在不太相关的图像上训练时会产生较低的准确性本文介绍了一种面向特定领域的人脸合成（DSFS）的算法，该算法利用OD中可用的代表性类内变化信息。在操作之前（摄像机校准过程中），通过在捕获的条件空间中进行聚类来选择在OD中出现的来自未知人员的一组紧凑面。通过在3D重建框架内集成基于图像的脸部重新照明技术，将这些脸部的特定领域变化投影到每个人的参考静止图像上。在OD捕获条件下生成一组紧凑的合成面。在基于稀疏表示分类的特定实现中，使用DSFS生成的合成面形成跨域字典，其中字典块将每个个体的原始面和合成面组合起来。使用Chokepoint和COX-S2V数据集获得的实验结果表明，与最先进的方法相比，使用DSFS方法增加画廊集提供了更高水平的准确度，其复杂性仅适度增加。

##### URL
[http://arxiv.org/abs/1801.01974](http://arxiv.org/abs/1801.01974)

##### PDF
[http://arxiv.org/pdf/1801.01974](http://arxiv.org/pdf/1801.01974)

