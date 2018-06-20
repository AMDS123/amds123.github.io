---
layout: post
title: "Automatic segmentation of prostate zones"
date: 2018-06-19 10:23:15
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Germonda Mooij, Ines Bagulho, Henkjan Huisman
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional networks have become state-of-the-art techniques for automatic medical image analysis, with the U-net architecture being the most popular at this moment. In this article we report the application of a 3D version of U-net to the automatic segmentation of prostate peripheral and transition zones in 3D MRI images. Our results are slightly better than recent studies that used 2D U-net and handcrafted feature approaches. 
 In addition, we test ideas for improving the 3D U-net setup, by 1) letting the network segment surrounding tissues, making use of the fixed anatomy, and 2) adjusting the network architecture to reflect the anisotropy in the dimensions of the MRI image volumes. While the latter adjustment gave a marginal improvement, the former adjustment showed a significant deterioration of the network performance. We were able to explain this deterioration by inspecting feature map activations in all layers of the network. We show that to segment more tissues the network replaces feature maps that were dedicated to detecting prostate peripheral zones, by feature maps detecting the surrounding tissues.

##### Abstract (translated by Google)
卷积网络已经成为自动医学图像分析的最先进技术，U网架构目前最受欢迎。在本文中，我们报告了3D版U-net在三维MRI图像中自动分割前列腺周边和过渡区的应用。我们的结果比最近使用2D U-net和手工特征方法的研究略好。
 此外，我们通过以下方式测试改进三维U-net设置的想法：1）让网络周围的组织，利用固定的解剖结构，2）调整网络结构以反映MRI图像的各向异性卷。虽然后者的调整略有改善，但前者的调整表明网络性能显着恶化。我们能够通过检查网络各层的功能图激活来解释这种恶化。我们表明，分割更多的组织网络取代功能地图，专门检测前列腺周边区域，通过检测周围组织的功能图。

##### URL
[http://arxiv.org/abs/1806.07146](http://arxiv.org/abs/1806.07146)

##### PDF
[http://arxiv.org/pdf/1806.07146](http://arxiv.org/pdf/1806.07146)

