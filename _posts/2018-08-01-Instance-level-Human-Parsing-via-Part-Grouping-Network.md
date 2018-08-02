---
layout: post
title: "Instance-level Human Parsing via Part Grouping Network"
date: 2018-08-01 03:51:59
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Represenation_Learning Optimization Inference Detection
author: Ke Gong, Xiaodan Liang, Yicheng Li, Yimin Chen, Ming Yang, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Instance-level human parsing towards real-world human analysis scenarios is still under-explored due to the absence of sufficient data resources and technical difficulty in parsing multiple instances in a single pass. Several related works all follow the "parsing-by-detection" pipeline that heavily relies on separately trained detection models to localize instances and then performs human parsing for each instance sequentially. Nonetheless, two discrepant optimization targets of detection and parsing lead to suboptimal representation learning and error accumulation for final results. In this work, we make the first attempt to explore a detection-free Part Grouping Network (PGN) for efficiently parsing multiple people in an image in a single pass. Our PGN reformulates instance-level human parsing as two twinned sub-tasks that can be jointly learned and mutually refined via a unified network: 1) semantic part segmentation for assigning each pixel as a human part (e.g., face, arms); 2) instance-aware edge detection to group semantic parts into distinct person instances. Thus the shared intermediate representation would be endowed with capabilities in both characterizing fine-grained parts and inferring instance belongings of each part. Finally, a simple instance partition process is employed to get final results during inference. We conducted experiments on PASCAL-Person-Part dataset and our PGN outperforms all state-of-the-art methods. Furthermore, we show its superiority on a newly collected multi-person parsing dataset (CIHP) including 38,280 diverse images, which is the largest dataset so far and can facilitate more advanced human analysis. The CIHP benchmark and our source code are available at this http URL

##### Abstract (translated by Google)
由于缺乏足够的数据资源和在单次通过中解析多个实例的技术难度，实例级人类对真实人类分析场景的解析仍未得到充分研究。几个相关的工作都遵循“逐个解析”管道，该管道严重依赖于单独训练的检测模型来本地化实例，然后顺序地为每个实例执行人工解析。尽管如此，检测和解析的两个不同的优化目标导致次优表示学习和最终结果的错误累积。在这项工作中，我们首次尝试探索无检测的零件分组网络（PGN），以便在一次通过中有效地解析图像中的多个人。我们的PGN将实例级人类解析重新定义为两个可以通过统一网络共同学习和相互提炼的双关联子任务：1）用于将每个像素指定为人类部分（例如，面部，手臂）的语义部分分割; 2）实例感知边缘检测，以将语义部分分组为不同的人物实例。因此，共享中间表示将赋予表征细粒度部分和推断每个部分的实例所有物的能力。最后，使用简单的实例分区过程在推理期间获得最终结果。我们在PASCAL-Person-Part数据集上进行了实验，我们的PGN优于所有最先进的方法。此外，我们展示了其在新收集的多人解析数据集（CIHP）上的优势，包括38,280种不同的图像，这是迄今为止最大的数据集，可以促进更高级的人体分析。 CIHP基准测试和我们的源代码可在此http URL上找到

##### URL
[https://arxiv.org/abs/1808.00157](https://arxiv.org/abs/1808.00157)

##### PDF
[https://arxiv.org/pdf/1808.00157](https://arxiv.org/pdf/1808.00157)

