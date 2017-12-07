---
layout: post
title: "An Efficient Evolutionary Based Method For Image Segmentation"
date: 2017-12-06 18:06:26
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Roohollah Aslanzadeh, Kazem Qazanfari, Mohammad Rahmati
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of this paper is to present a new efficient image segmentation method based on evolutionary computation which is a model inspired from human behavior. Based on this model, a four layer process for image segmentation is proposed using the split/merge approach. In the first layer, an image is split into numerous regions using the watershed algorithm. In the second layer, a co-evolutionary process is applied to form centers of finals segments by merging similar primary regions. In the third layer, a meta-heuristic process uses two operators to connect the residual regions to their corresponding determined centers. In the final layer, an evolutionary algorithm is used to combine the resulted similar and neighbor regions. Different layers of the algorithm are totally independent, therefore for certain applications a specific layer can be changed without constraint of changing other layers. Some properties of this algorithm like the flexibility of its method, the ability to use different feature vectors for segmentation (grayscale, color, texture, etc), the ability to control uniformity and the number of final segments using free parameters and also maintaining small regions, makes it possible to apply the algorithm to different applications. Moreover, the independence of each region from other regions in the second layer, and the independence of centers in the third layer, makes parallel implementation possible. As a result the algorithm speed will increase. The presented algorithm was tested on a standard dataset (BSDS 300) of images, and the region boundaries were compared with different people segmentation contours. Results show the efficiency of the algorithm and its improvement to similar methods. As an instance, in 70% of tested images, results are better than ACT algorithm, besides in 100% of tested images, we had better results in comparison with VSP algorithm.

##### Abstract (translated by Google)
本文的目的是提出一种新的基于进化计算的高效图像分割方法，该方法是一种受人类行为启发的模型。在此模型的基础上，提出了一种使用分割/合并的方法进行图像分割的四层过程。在第一层中，使用分水岭算法将图像分割成多个区域。在第二层中，通过合并相似的主要区域，共同进化过程被用于形成决赛分段的中心。在第三层中，元启发式过程使用两个运算符将剩余区域连接到其相应的确定中心。在最后一层中，使用演化算法来组合所得到的相似区域和相邻区域。该算法的不同层是完全独立的，因此对于某些应用，可以改变特定层而不改变其他层。这种算法的一些性质，如其方法的灵活性，使用不同特征向量进行分割（灰度，颜色，纹理等）的能力，使用自由参数来控制均匀性和最终段数量的能力，以及维护小区域，使得将算法应用于不同的应用成为可能。而且，每个地区与第二层其他地区的独立性以及第三层中心的独立性使得并行实施成为可能。结果算法速度会增加。所提出的算法在图像的标准数据集（BSDS 300）上进行测试，并将区域边界与不同的人分割轮廓进行比较。结果显示了该算法的效率和对类似方法的改进。例如，在70％的测试图像中，结果比ACT算法好，除了100％的测试图像，与VSP算法相比，效果更好。

##### URL
[http://arxiv.org/abs/1709.04393](http://arxiv.org/abs/1709.04393)

##### PDF
[http://arxiv.org/pdf/1709.04393](http://arxiv.org/pdf/1709.04393)

