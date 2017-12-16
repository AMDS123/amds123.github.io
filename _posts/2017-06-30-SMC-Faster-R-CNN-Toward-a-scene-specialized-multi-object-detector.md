---
layout: post
title: "SMC Faster R-CNN: Toward a scene-specialized multi-object detector"
date: 2017-06-30 14:31:12
categories: arXiv_CV
tags: arXiv_CV Object_Detection Transfer_Learning Detection
author: Ala Mhalla, Thierry Chateau, Houda Maamatou, Sami Gazzah, Najoua Essoukri Ben Amara
mathjax: true
---

* content
{:toc}

##### Abstract
Generally, the performance of a generic detector decreases significantly when it is tested on a specific scene due to the large variation between the source training dataset and the samples from the target scene. To solve this problem, we propose a new formalism of transfer learning based on the theory of a Sequential Monte Carlo (SMC) filter to automatically specialize a scene-specific Faster R-CNN detector. The suggested framework uses different strategies based on the SMC filter steps to approximate iteratively the target distribution as a set of samples in order to specialize the Faster R-CNN detector towards a target scene. Moreover, we put forward a likelihood function that combines spatio-temporal information extracted from the target video sequence and the confidence-score given by the output layer of the Faster R-CNN, to favor the selection of target samples associated with the right label. The effectiveness of the suggested framework is demonstrated through experiments on several public traffic datasets. Compared with the state-of-the-art specialization frameworks, the proposed framework presents encouraging results for both single and multi-traffic object detections.

##### Abstract (translated by Google)
通常，由于源训练数据集与来自目标场景的样本之间的大的差异，当在特定场景上测试时，通用检测器的性能显着降低。为了解决这个问题，我们提出了一种新的基于序列蒙特卡罗（SMC）滤波器理论的转移学习形式主义，以自动专门化一个场景特定的更快的R-CNN检测器。所建议的框架使用基于SMC滤波器步骤的不同策略以迭代方式将目标分布近似为一组样本，以便将更快的R-CNN检测器专用于目标场景。此外，我们提出了一种似然函数，它将从目标视频序列中提取的时空信息与Faster R-CNN的输出层给出的置信度分数相结合，以便选择与正确标签相关联的目标样本。建议框架的有效性通过对几个公共交通数据集的实验来证明。与最先进的专业化框架相比，所提出的框架对于单个和多个交通对象检测都呈现令人鼓舞的结果。

##### URL
[https://arxiv.org/abs/1706.10217](https://arxiv.org/abs/1706.10217)

##### PDF
[https://arxiv.org/pdf/1706.10217](https://arxiv.org/pdf/1706.10217)

