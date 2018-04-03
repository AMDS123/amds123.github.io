---
layout: post
title: "FloorNet: A Unified Framework for Floorplan Reconstruction from 3D Scans"
date: 2018-03-31 00:22:27
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Chen Liu, Jiaye Wu, Yasutaka Furukawa
mathjax: true
---

* content
{:toc}

##### Abstract
The ultimate goal of this indoor mapping research is to automatically reconstruct a floorplan simply by walking through a house with a smartphone in a pocket. This paper tackles this problem by proposing FloorNet, a novel deep neural architecture. The challenge lies in the processing of RGBD streams spanning a large 3D space. FloorNet effectively processes the data through three neural network branches: 1) PointNet with 3D points, exploiting the 3D information; 2) CNN with a 2D point density image in a top-down view, enhancing the local spatial reasoning; and 3) CNN with RGB images, utilizing the full image information. FloorNet exchanges intermediate features across the branches to exploit the best of all the architectures. We have created a benchmark for floorplan reconstruction by acquiring RGBD video streams for 155 residential houses or apartments with Google Tango phones and annotating complete floorplan information. Our qualitative and quantitative evaluations demonstrate that the fusion of three branches effectively improves the reconstruction quality. We hope that the paper together with the benchmark will be an important step towards solving a challenging vector-graphics reconstruction problem. Code and data are available at https://github.com/art-programmer/FloorNet.

##### Abstract (translated by Google)
这个室内测绘研究的最终目标是自动地重建一个平面布置图，只需在智能手机的口袋里穿过一间房子。本文通过提出FloorNet这一新颖的深度神经架构来解决这个问题。面临的挑战在于处理跨越大型3D空间的RGBD流。 FloorNet通过三个神经网络分支有效地处理数据：1）带有3D点的PointNet，利用3D信息; 2）CNN在自顶向下视图中具有2D点密度图像，增强了局部空间推理;和3）使用全图像信息的RGB图像的CNN。 FloorNet在各分支之间交换中间特征，以充分利用所有架构中的优点。我们创建了一个平面图重建的基准，通过购买带有Google Tango手机的155个住宅或公寓的RGBD视频流并注释完整的平面布置图信息。我们的定性和定量评估表明，三个分支的融合有效地提高了重建质量。我们希望该论文与基准一起将是解决具有挑战性的矢量图形重构问题的重要一步。代码和数据可在https://github.com/art-programmer/FloorNet上找到。

##### URL
[http://arxiv.org/abs/1804.00090](http://arxiv.org/abs/1804.00090)

##### PDF
[http://arxiv.org/pdf/1804.00090](http://arxiv.org/pdf/1804.00090)

