---
layout: post
title: "Liver Lesion Detection from Weakly-labeled Multi-phase CT Volumes with a Grouped Single Shot MultiBox Detector"
date: 2018-07-02 02:31:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Sang-gil Lee, Jae Seok Bae, Hyunjae Kim, Jung Hoon Kim, Sungroh Yoon
mathjax: true
---

* content
{:toc}

##### Abstract
We present a focal liver lesion detection model leveraged by custom-designed multi-phase computed tomography (CT) volumes, which reflects real-world clinical lesion detection practice using a Single Shot MultiBox Detector (SSD). We show that grouped convolutions effectively harness richer information of the multi-phase data for the object detection model, while a naive application of SSD suffers from a generalization gap. We trained and evaluated the modified SSD model and recently proposed variants with our CT dataset of 64 subjects by five-fold cross validation. Our model achieved a 53.3% average precision score and ran in under three seconds per volume, outperforming the original model and state-of-the-art variants. Results show that the one-stage object detection model is a practical solution, which runs in near real-time and can learn an unbiased feature representation from a large-volume real-world detection dataset, which requires less tedious and time consuming construction of the weak phase-level bounding box labels.

##### Abstract (translated by Google)
我们提出了一个利用定制设计的多阶段计算机断层扫描（CT）体积的局灶性肝脏病变检测模型，该模型使用单次多盒检测器（SSD）反映真实世界的临床病变检测实践。我们展示了分组卷积有效地利用了对象检测模型的多阶段数据的更丰富信息，而SSD的朴素应用遭受了泛化差距。我们通过五次交叉验证训练和评估了修改后的SSD模型和最近提出的具有64个受试者的CT数据集的变体。我们的模型平均精度得分为53.3％，每卷不超过3秒，优于原始模型和最先进的变体。结果表明，一阶段目标检测模型是一种实用的解决方案，可以近乎实时地运行，并且可以从大容量的真实世界检测数据集中学习无偏的特征表示，这需要较少的繁琐和耗时的构造。弱相位边界框标签。

##### URL
[http://arxiv.org/abs/1807.00436](http://arxiv.org/abs/1807.00436)

##### PDF
[http://arxiv.org/pdf/1807.00436](http://arxiv.org/pdf/1807.00436)

