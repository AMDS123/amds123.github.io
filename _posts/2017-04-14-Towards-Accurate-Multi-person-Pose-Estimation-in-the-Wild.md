---
layout: post
title: "Towards Accurate Multi-person Pose Estimation in the Wild"
date: 2017-04-14 18:30:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation CNN Prediction Detection
author: George Papandreou, Tyler Zhu, Nori Kanazawa, Alexander Toshev, Jonathan Tompson, Chris Bregler, Kevin Murphy
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for multi-person detection and 2-D pose estimation that achieves state-of-art results on the challenging COCO keypoints task. It is a simple, yet powerful, top-down approach consisting of two stages. In the first stage, we predict the location and scale of boxes which are likely to contain people; for this we use the Faster RCNN detector. In the second stage, we estimate the keypoints of the person potentially contained in each proposed bounding box. For each keypoint type we predict dense heatmaps and offsets using a fully convolutional ResNet. To combine these outputs we introduce a novel aggregation procedure to obtain highly localized keypoint predictions. We also use a novel form of keypoint-based Non-Maximum-Suppression (NMS), instead of the cruder box-level NMS, and a novel form of keypoint-based confidence score estimation, instead of box-level scoring. Trained on COCO data alone, our final system achieves average precision of 0.649 on the COCO test-dev set and the 0.643 test-standard sets, outperforming the winner of the 2016 COCO keypoints challenge and other recent state-of-art. Further, by using additional in-house labeled data we obtain an even higher average precision of 0.685 on the test-dev set and 0.673 on the test-standard set, more than 5% absolute improvement compared to the previous best performing method on the same dataset.

##### Abstract (translated by Google)
我们提出了一种多人检测和二维姿态估计的方法，在具有挑战性的COCO关键点任务上实现了最新的结果。这是一个简单而强大的自上而下的方法，由两个阶段组成。在第一阶段，我们预测可能包含人的盒子的位置和规模;为此我们使用更快的RCNN检测器。在第二阶段，我们估计可能包含在每个提出的边界框中的人的关键点。对于每个关键点类型，我们使用完全卷积ResNet预测密集的热图和偏移量。为了结合这些输出，我们引入了一种新颖的聚合程序来获得高度本地化的关键点预测。我们还使用基于关键点的非最大抑制（NMS）的新形式，而不是更粗糙的盒级NMS，以及基于关键点的新型形式的置信度评估，而不是框级评分。我们的最终系统仅依靠COCO数据进行训练，COCO测试开发套件和0.643测试标准套件的平均精度为0.649，优于2016年COCO关键挑战获胜者和其他最新技术水平。此外，通过使用附加的内部标记数据，我们获得了更高的测试开发集合上的0.685和测试标准集合上的0.673的平均精度，与之前的同类最佳执行方法相比，绝对性提高了5％以上数据集。

##### URL
[https://arxiv.org/abs/1701.01779](https://arxiv.org/abs/1701.01779)

##### PDF
[https://arxiv.org/pdf/1701.01779](https://arxiv.org/pdf/1701.01779)

