---
layout: post
title: "IAN: The Individual Aggregation Network for Person Search"
date: 2017-05-16 06:55:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Jimin Xiao, Yanchun Xie, Tammam Tillo, Kaizhu Huang, Yunchao Wei, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Person search in real-world scenarios is a new challenging computer version task with many meaningful applications. The challenge of this task mainly comes from: (1) unavailable bounding boxes for pedestrians and the model needs to search for the person over the whole gallery images; (2) huge variance of visual appearance of a particular person owing to varying poses, lighting conditions, and occlusions. To address these two critical issues in modern person search applications, we propose a novel Individual Aggregation Network (IAN) that can accurately localize persons by learning to minimize intra-person feature variations. IAN is built upon the state-of-the-art object detection framework, i.e., faster R-CNN, so that high-quality region proposals for pedestrians can be produced in an online manner. In addition, to relieve the negative effect caused by varying visual appearances of the same individual, IAN introduces a novel center loss that can increase the intra-class compactness of feature representations. The engaged center loss encourages persons with the same identity to have similar feature characteristics. Extensive experimental results on two benchmarks, i.e., CUHK-SYSU and PRW, well demonstrate the superiority of the proposed model. In particular, IAN achieves 77.23% mAP and 80.45% top-1 accuracy on CUHK-SYSU, which outperform the state-of-the-art by 1.7% and 1.85%, respectively.

##### Abstract (translated by Google)
在真实场景中进行人员搜索是一个具有许多有意义的应用程序的新的具有挑战性的电脑版本任务这项任务的挑战主要来自：（1）行人无法使用的边界框，模型需要搜索整个画廊的图像; （2）由于姿势，照明条件和遮挡的不同，特定人物的视觉外观差异很大。为了解决现代人类搜索应用中的这两个关键问题，我们提出了一种新颖的个体聚合网络（IAN），通过学习最小化人内特征变化来准确地定位人。 IAN建立在最先进的目标检测框架上，即更快的R-CNN，从而可以以在线方式生成高质量的行人区域提案。此外，为了缓解由于同一个人的不同视觉效果所带来的负面影响，IAN引入了新的中心损失，可以增加特征表示的类内紧致性。参与中心的损失鼓励具有相同身份的人具有相似的特征。在两个基准，即中大和苏维埃，广泛的实验结果很好地证明了所提出的模型的优越性。尤其是中国中大，IAN达到77.23％的mAP和80.45％的顶级精确度，分别超过了最新的1.7％和1.85％。

##### URL
[https://arxiv.org/abs/1705.05552](https://arxiv.org/abs/1705.05552)

##### PDF
[https://arxiv.org/pdf/1705.05552](https://arxiv.org/pdf/1705.05552)

