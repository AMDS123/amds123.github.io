---
layout: post
title: "'RAPID' Regions-of-Interest Detection In Big Histopathological Images"
date: 2017-04-07 03:34:40
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization Prediction Detection
author: Li Sulimowicz, Ishfaq Ahmad
mathjax: true
---

* content
{:toc}

##### Abstract
The sheer volume and size of histopathological images (e.g.,10^6 MPixel) underscores the need for faster and more accurate Regions-of-interest (ROI) detection algorithms. In this paper, we propose such an algorithm, which has four main components that help achieve greater accuracy and faster speed: First, while using coarse-to-fine topology preserving segmentation as the baseline, the proposed algorithm uses a superpixel regularity optimization scheme for avoiding irregular and extremely small superpixels. Second, the proposed technique employs a prediction strategy to focus only on important superpixels at finer image levels. Third, the algorithm reuses the information gained from the coarsest image level at other finer image levels. Both the second and the third components drastically lower the complexity. Fourth, the algorithm employs a highly effective parallelization scheme using adap- tive data partitioning, which gains high speedup. Experimental results, conducted on the BSD500 [1] and 500 whole-slide histological images from the National Lung Screening Trial (NLST)1 dataset, confirm that the proposed algorithm gained 13 times speedup compared with the baseline, and around 160 times compared with SLIC [11], without losing accuracy.

##### Abstract (translated by Google)
组织病理学图像（例如，10 ^ 6M像素）的纯粹的体积和大小强调了对更快和更准确的感兴趣区域（ROI）检测算法的需求。在本文中，我们提出了这样一个算法，其中有四个主要组件，有助于实现更高的准确性和更快的速度：首先，在使用从粗到细的拓扑保留分割作为基线时，所提出的算法使用超像素规律性优化方案避免不规则和极小的超像素。其次，所提出的技术采用预测策略来仅聚焦在更精细的图像水平上的重要的超级像素。第三，该算法在其他更精细的图像层次上重用从最粗糙的图像层获得的信息。第二和第三部分都大大降低了复杂性。第四，该算法采用高效的并行化方案，利用自适应数据划分，获得高速加速。实验结果，在国家肺部筛查试验（NLST）1数据集的BSD500 [1]和500张全滑动组织图像上进行的实验结果证实，所提出的算法比基线获得了13倍的加速，比SLIC大约160倍[11]，没有失去准确性。

##### URL
[https://arxiv.org/abs/1704.02083](https://arxiv.org/abs/1704.02083)

##### PDF
[https://arxiv.org/pdf/1704.02083](https://arxiv.org/pdf/1704.02083)

