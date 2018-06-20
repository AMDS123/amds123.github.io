---
layout: post
title: "Soft Sampling for Robust Object Detection"
date: 2018-06-18 23:40:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Zhe Wu, Navaneeth Bodla, Bharat Singh, Mahyar Najibi, Rama Chellappa, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
We study the robustness of object detection under the presence of missing annotations. In this setting, the unlabeled object instances will be treated as background, which will generate an incorrect training signal for the detector. Interestingly, we observe that after dropping 30% of the annotations (and labeling them as background), the performance of CNN-based object detectors like Faster-RCNN only drops by 5% on the PASCAL VOC dataset. We provide a detailed explanation for this result. To further bridge the performance gap, we propose a simple yet effective solution, called Soft Sampling. Soft Sampling re-weights the gradients of RoIs as a function of overlap with positive instances. This ensures that the uncertain background regions are given a smaller weight compared to the hardnegatives. Extensive experiments on curated PASCAL VOC datasets demonstrate the effectiveness of the proposed Soft Sampling method at different annotation drop rates. Finally, we show that on OpenImagesV3, which is a real-world dataset with missing annotations, Soft Sampling outperforms standard detection baselines by over 3%.

##### Abstract (translated by Google)
我们研究了在缺少注释的情况下对象检测的鲁棒性。在此设置中，未标记的对象实例将被视为背景，这将为检测器生成不正确的训练信号。有趣的是，我们观察到在减少了30％的注释（并将它们标记为背景）之后，像Faster-RCNN这样的基于CNN的对象检测器的性能仅在PASCAL VOC数据集上下降了5％。我们为这个结果提供了详细的解释。为了进一步缩小性能差距，我们提出了一个简单而有效的解决方案，称为软采样。软采样将RoI的梯度重新加权为与正实例重叠的函数。这确保了不确定的背景区域与负性区域相比具有更小的权重。关于策划的PASCAL VOC数据集的大量实验证明了所提出的软抽样方法在不同注释掉落率下的有效性。最后，我们展示了在OpenImagesV3上，这是一个缺少注释的实际数据集，软采样比标准检测基线优于3％。

##### URL
[http://arxiv.org/abs/1806.06986](http://arxiv.org/abs/1806.06986)

##### PDF
[http://arxiv.org/pdf/1806.06986](http://arxiv.org/pdf/1806.06986)

