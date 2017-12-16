---
layout: post
title: "3D Object Discovery and Modeling Using Single RGB-D Images Containing Multiple Object Instances"
date: 2017-10-17 12:03:34
categories: arXiv_CV
tags: arXiv_CV Salient Knowledge Segmentation Quantitative Detection
author: Wim Abbeloos, Esra Ataer-Cansizoglu, Sergio Caccamo, Yuichi Taguchi, Yukiyasu Domae
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised object modeling is important in robotics, especially for handling a large set of objects. We present a method for unsupervised 3D object discovery, reconstruction, and localization that exploits multiple instances of an identical object contained in a single RGB-D image. The proposed method does not rely on segmentation, scene knowledge, or user input, and thus is easily scalable. Our method aims to find recurrent patterns in a single RGB-D image by utilizing appearance and geometry of the salient regions. We extract keypoints and match them in pairs based on their descriptors. We then generate triplets of the keypoints matching with each other using several geometric criteria to minimize false matches. The relative poses of the matched triplets are computed and clustered to discover sets of triplet pairs with similar relative poses. Triplets belonging to the same set are likely to belong to the same object and are used to construct an initial object model. Detection of remaining instances with the initial object model using RANSAC allows to further expand and refine the model. The automatically generated object models are both compact and descriptive. We show quantitative and qualitative results on RGB-D images with various objects including some from the Amazon Picking Challenge. We also demonstrate the use of our method in an object picking scenario with a robotic arm.

##### Abstract (translated by Google)
无监督的对象建模在机器人学中非常重要，特别是处理大量的对象。我们提出了一种无监督3D对象发现，重建和定位的方法，该方法利用包含在单个RGB-D图像中的多个相同对象的实例。所提出的方法不依赖于分割，场景知识或用户输入，因此易于扩展。我们的方法旨在通过利用显着区域的外观和几何形状来在单个RGB-D图像中找到重复出现的图案。我们提取关键点，并根据它们的描述符对它们进行匹配。然后，我们使用几个几何准则来生成三个彼此匹配的关键点，以最小化错误匹配。计算匹配的三元组的相对姿态并聚类，以发现具有相似相对姿势的三元组对。属于同一组的三元组可能属于同一个对象，并被用于构建初始对象模型。使用RANSAC对初始对象模型的剩余实例进行检测可以进一步扩展和优化模型。自动生成的对象模型既简洁又具有描述性。我们展示了RGB-D图像的定量和定性结果，包括一些来自亚马逊采摘挑战的各种对象。我们还展示了我们的方法在机器人手臂对象采摘场景中的使用。

##### URL
[https://arxiv.org/abs/1710.06231](https://arxiv.org/abs/1710.06231)

##### PDF
[https://arxiv.org/pdf/1710.06231](https://arxiv.org/pdf/1710.06231)

