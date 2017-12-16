---
layout: post
title: "Local Neighborhood Intensity Pattern: A new texture feature descriptor for image retrieval"
date: 2017-09-07 21:56:32
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Face
author: Prithaj Banerjee, Ayan Kumar Bhunia, Avirup Bhattacharyya, Partha Pratim Roy, Subrahmanyam Murala
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a new texture descriptor based on the local neighborhood intensity difference is proposed for content based image retrieval (CBIR). For computation of texture features like Local Binary Pattern (LBP), the center pixel in a 3*3 window of an image is compared with all the remaining neighbors, one pixel at a time to generate a binary bit pattern. It ignores the effect of the adjacent neighbors of a particular pixel for its binary encoding and also for texture description. The proposed method is based on the concept that neighbors of a particular pixel hold a significant amount of texture information that can be considered for efficient texture representation for CBIR. Taking this into account, we develop a new texture descriptor, named as Local Neighborhood Intensity Pattern (LNIP) which considers the relative intensity difference between a particular pixel and the center pixel by considering its adjacent neighbors and generate a sign and a magnitude pattern. Since sign and magnitude patterns hold complementary information to each other, these two patterns are concatenated into a single feature descriptor to generate a more concrete and useful feature descriptor. The proposed descriptor has been tested for image retrieval on four databases, including three texture image databases - Brodatz texture image database, MIT VisTex database and Salzburg texture database and one face database AT&T face database. The precision and recall values observed on these databases are compared with some state-of-art local patterns. The proposed method showed a significant improvement over many other existing methods.

##### Abstract (translated by Google)
针对基于内容的图像检索（CBIR），提出了一种基于局部邻域强度差异的纹理描述子。为了计算局部二值模式（LBP）等纹理特征，将图像的3 * 3窗口中的中心像素与所有剩余的邻居进行比较，每次一个像素，以产生二进制位模式。它忽略了特定像素的相邻邻居对其二进制编码的影响，也忽略了纹理描述。所提出的方法基于这样的概念：特定像素的邻居保持大量的可被考虑用于CBIR的高效纹理表示的纹理信息。考虑到这一点，我们开发了一个新的纹理描述符，被称为局部邻域强度模式（LNIP），它考虑了特定像素和中心像素之间的相对强度差异，并考虑邻近邻居并产生符号和幅度模式。由于符号和幅度模式彼此保持互补信息，因此这两个模式被连接成单个特征描述符以生成更具体和有用的特征描述符。提出的描述符经过4个数据库的检索，包括三个纹理图像数据库：Brodatz纹理图像数据库，MIT VisTex数据库和Salzburg纹理数据库，以及一个人脸数据库AT＆T人脸库。在这些数据库中观察到的精确度和召回率值与一些最先进的本地模式进行比较。所提出的方法显示出比许多其他现有方法显着的改进。

##### URL
[https://arxiv.org/abs/1709.02463](https://arxiv.org/abs/1709.02463)

##### PDF
[https://arxiv.org/pdf/1709.02463](https://arxiv.org/pdf/1709.02463)

