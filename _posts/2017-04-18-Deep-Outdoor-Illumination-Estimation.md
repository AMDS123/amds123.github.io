---
layout: post
title: "Deep Outdoor Illumination Estimation"
date: 2017-04-18 21:38:27
categories: arXiv_CV
tags: arXiv_CV
author: Yannick Hold-Geoffroy, Kalyan Sunkavalli, Sunil Hadap, Emiliano Gambaretto, Jean-François Lalonde
mathjax: true
---

* content
{:toc}

##### Abstract
We present a CNN-based technique to estimate high-dynamic range outdoor illumination from a single low dynamic range image. To train the CNN, we leverage a large dataset of outdoor panoramas. We fit a low-dimensional physically-based outdoor illumination model to the skies in these panoramas giving us a compact set of parameters (including sun position, atmospheric conditions, and camera parameters). We extract limited field-of-view images from the panoramas, and train a CNN with this large set of input image--output lighting parameter pairs. Given a test image, this network can be used to infer illumination parameters that can, in turn, be used to reconstruct an outdoor illumination environment map. We demonstrate that our approach allows the recovery of plausible illumination conditions and enables photorealistic virtual object insertion from a single image. An extensive evaluation on both the panorama dataset and captured HDR environment maps shows that our technique significantly outperforms previous solutions to this problem.

##### Abstract (translated by Google)
我们提出了一种基于CNN的技术来估计来自单个低动态范围图像的高动态范围的户外照明。为了训练CNN，我们利用了大型的户外全景数据集。我们在这些全景图中为天空安装了一个低维的基于物理的室外照明模型，为我们提供了一系列紧凑的参数（包括太阳位置，大气条件和摄像机参数）。我们从全景中提取有限的视场图像，并用这一大组输入图像输出光照参数对训练一个CNN。给定一个测试图像，这个网络可以用来推断照明参数，然后可以用来重建一个户外照明环境地图。我们证明，我们的方法允许恢复合理的照明条件，并从一个图像启用照片级虚拟对象插入。对全景数据集和捕获的HDR环境地图进行广泛的评估表明，我们的技术明显优于以前对这个问题的解决方案。

##### URL
[https://arxiv.org/abs/1611.06403](https://arxiv.org/abs/1611.06403)

##### PDF
[https://arxiv.org/pdf/1611.06403](https://arxiv.org/pdf/1611.06403)

