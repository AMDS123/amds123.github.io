---
layout: post
title: "Shape Robust Text Detection with Progressive Scale Expansion Network"
date: 2018-06-07 08:28:54
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Prediction Detection
author: Xiang Li, Wenhai Wang, Wenbo Hou, Ruo-Ze Liu, Tong Lu, Jian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
The challenges of shape robust text detection lie in two aspects: 1) most existing quadrangular bounding box based detectors are difficult to locate texts with arbitrary shapes, which are hard to be enclosed perfectly in a rectangle; 2) most pixel-wise segmentation-based detectors may not separate the text instances that are very close to each other. To address these problems, we propose a novel Progressive Scale Expansion Network (PSENet), designed as a segmentation-based detector with multiple predictions for each text instance. These predictions correspond to different `kernels' produced by shrinking the original text instance into various scales. Consequently, the final detection can be conducted through our progressive scale expansion algorithm which gradually expands the kernels with minimal scales to the text instances with maximal and complete shapes. Due to the fact that there are large geometrical margins among these minimal kernels, our method is effective to distinguish the adjacent text instances and is robust to arbitrary shapes. The state-of-the-art results on ICDAR 2015 and ICDAR 2017 MLT benchmarks further confirm the great effectiveness of PSENet. Notably, PSENet outperforms the previous best record by absolute 6.37\% on the curve text dataset SCUT-CTW1500. Code will be available in https://github.com/whai362/PSENet.

##### Abstract (translated by Google)
形状稳健文本检测的挑战在于两个方面：1）大多数现有的基于四边形边界框的检测器难以定位具有任意形状的文本，这些文本很难被完美地包围在矩形中; 2）大多数以像素为单位的基于分割的检测器可能不会分离彼此非常接近的文本实例。为了解决这些问题，我们提出了一种新型的渐进式扩展网络（PSENet），设计为基于分割的检测器，对每个文本实例进行多重预测。这些预测对应于通过将原始文本实例缩小到各种尺度而产生的不同“内核”。因此，最终检测可以通过我们的渐进尺度扩展算法来进行，该算法逐渐将具有最小尺度的内核扩展到具有最大和完整形状的文本实例。由于这些最小内核之间存在较大的几何边界，因此我们的方法可以有效区分相邻文本实例，并且对任意形状都很有效。 ICDAR 2015和ICDAR 2017 MLT基准测试的最新成果进一步证实了PSENet的高效性。值得注意的是，PSENet在曲线文本数据集SCUT-CTW1500上胜过以前的最佳记录绝对值6.37％。代码将在https://github.com/whai362/PSENet中提供。

##### URL
[http://arxiv.org/abs/1806.02559](http://arxiv.org/abs/1806.02559)

##### PDF
[http://arxiv.org/pdf/1806.02559](http://arxiv.org/pdf/1806.02559)

