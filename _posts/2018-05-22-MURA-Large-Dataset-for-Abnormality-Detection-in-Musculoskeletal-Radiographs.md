---
layout: post
title: "MURA: Large Dataset for Abnormality Detection in Musculoskeletal Radiographs"
date: 2018-05-22 09:19:07
categories: arXiv_AI
tags: arXiv_AI Detection
author: Pranav Rajpurkar, Jeremy Irvin, Aarti Bagul, Daisy Ding, Tony Duan, Hershel Mehta, Brandon Yang, Kaylie Zhu, Dillon Laird, Robyn L. Ball, Curtis Langlotz, Katie Shpanskaya, Matthew P. Lungren, Andrew Y. Ng
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce MURA, a large dataset of musculoskeletal radiographs containing 40,561 images from 14,863 studies, where each study is manually labeled by radiologists as either normal or abnormal. To evaluate models robustly and to get an estimate of radiologist performance, we collect additional labels from six board-certified Stanford radiologists on the test set, consisting of 207 musculoskeletal studies. On this test set, the majority vote of a group of three radiologists serves as gold standard. We train a 169-layer DenseNet baseline model to detect and localize abnormalities. Our model achieves an AUROC of 0.929, with an operating point of 0.815 sensitivity and 0.887 specificity. We compare our model and radiologists on the Cohen's kappa statistic, which expresses the agreement of our model and of each radiologist with the gold standard. Model performance is comparable to the best radiologist performance in detecting abnormalities on finger and wrist studies. However, model performance is lower than best radiologist performance in detecting abnormalities on elbow, forearm, hand, humerus, and shoulder studies. We believe that the task is a good challenge for future research. To encourage advances, we have made our dataset freely available at https://stanfordmlgroup.github.io/competitions/mura .

##### Abstract (translated by Google)
我们引入MURA，这是一个包含来自14,863项研究的40,561幅图像的大型肌肉骨骼X光片数据库，其中每项研究均由放射科医师手动标记为正常或异常。为了强有力地评估模型并获得放射科医师表现的估计值，我们从测试集上的六位董事会认证的斯坦福放射科医师那里收集了额外的标签，其中包括207项肌肉骨骼研究。在这个测试集中，一组三位放射科医生的大多数投票都是金标准。我们训练169层DenseNet基线模型来检测和定位异常。我们的模型实现了0.929的AUROC，操作点灵敏度为0.815，特异性为0.887。我们将我们的模型和放射科医师与Cohen的kappa统计量进行比较，该统计量表示我们的模型和每位放射科医师与黄金标准的一致性。在检测手指和手腕研究中的异常时，模型性能与最佳放射科医师的性能相当。然而，在检测肘，前臂，手，肱骨和肩部研究中的异常时，模型表现低于最佳放射科医师的表现。我们相信这项任务对未来的研究来说是一个很好的挑战。为了鼓励进步，我们已经通过https://stanfordmlgroup.github.io/competitions/mura免费提供了我们的数据集。

##### URL
[http://arxiv.org/abs/1712.06957](http://arxiv.org/abs/1712.06957)

##### PDF
[http://arxiv.org/pdf/1712.06957](http://arxiv.org/pdf/1712.06957)

