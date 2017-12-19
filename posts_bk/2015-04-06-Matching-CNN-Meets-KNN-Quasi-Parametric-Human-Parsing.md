---
layout: post
title: "Matching-CNN Meets KNN: Quasi-Parametric Human Parsing"
date: 2015-04-06 07:20:02
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Si Liu, Xiaodan Liang, Luoqi Liu, Xiaohui Shen, Jianchao Yang, Changsheng Xu, Liang Lin, Xiaochun Cao, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Both parametric and non-parametric approaches have demonstrated encouraging performances in the human parsing task, namely segmenting a human image into several semantic regions (e.g., hat, bag, left arm, face). In this work, we aim to develop a new solution with the advantages of both methodologies, namely supervision from annotated data and the flexibility to use newly annotated (possibly uncommon) images, and present a quasi-parametric human parsing model. Under the classic K Nearest Neighbor (KNN)-based nonparametric framework, the parametric Matching Convolutional Neural Network (M-CNN) is proposed to predict the matching confidence and displacements of the best matched region in the testing image for a particular semantic region in one KNN image. Given a testing image, we first retrieve its KNN images from the annotated/manually-parsed human image corpus. Then each semantic region in each KNN image is matched with confidence to the testing image using M-CNN, and the matched regions from all KNN images are further fused, followed by a superpixel smoothing procedure to obtain the ultimate human parsing result. The M-CNN differs from the classic CNN in that the tailored cross image matching filters are introduced to characterize the matching between the testing image and the semantic region of a KNN image. The cross image matching filters are defined at different convolutional layers, each aiming to capture a particular range of displacements. Comprehensive evaluations over a large dataset with 7,700 annotated human images well demonstrate the significant performance gain from the quasi-parametric model over the state-of-the-arts, for the human parsing task.

##### Abstract (translated by Google)
参数化和非参数化方法在人类解析任务中都表现出令人鼓舞的性能，即将人类图像分割成若干语义区域（例如，帽子，包，左臂，脸部）。在这项工作中，我们的目标是开发一个新的解决方案，具有两种方法的优点，即从注释数据的监督和使用新注释（可能不常见）图像的灵活性，并提出一个准参数人类解析模型。在经典的基于最近邻（KNN）的非参数框架下，提出了参数化匹配卷积神经网络（M-CNN），用于预测测试图像中特定语义区域的匹配置信度和位移KNN图像。给定一个测试图像，我们首先从注释/手动解析的人体图像语料库中检索它的KNN图像。然后利用M-CNN将每个KNN图像中的每个语义区域与测试图像的置信度进行匹配，进一步融合所有KNN图像中的匹配区域，进行超像素平滑处理，得到最终的人体解析结果。 M-CNN与经典CNN的不同之处在于引入了量身定制的交叉图像匹配滤波器来表征测试图像与KNN图像的语义区域之间的匹配。交叉图像匹配滤波器被定义在不同的卷积层上，每个卷积层都旨在捕获特定的位移范围。对具有7700个带注释的人类图像的大型数据集进行全面评估，证明了准参数模型对于人类解析任务的显着性能收益。

##### URL
[https://arxiv.org/abs/1504.01220](https://arxiv.org/abs/1504.01220)

##### PDF
[https://arxiv.org/pdf/1504.01220](https://arxiv.org/pdf/1504.01220)

