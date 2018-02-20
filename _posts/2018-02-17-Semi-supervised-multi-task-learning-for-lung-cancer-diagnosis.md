---
layout: post
title: "Semi-supervised multi-task learning for lung cancer diagnosis"
date: 2018-02-17 03:49:32
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Naji Khosravan, Ulas Bagci
mathjax: true
---

* content
{:toc}

##### Abstract
Early detection of lung nodules is of great importance in lung cancer screening. Existing research recognizes the critical role played by CAD systems in early detection and diagnosis of lung nodules. However, many CAD systems, which are used as cancer detection tools, produce a lot of false positives (FP) and require a further FP reduction step. Furthermore, guidelines for early diagnosis and treatment of lung cancer are consist of different shape and volume measurements of abnormalities. Segmentation is at the heart of our understanding of nodules morphology making it a major area of interest within the field of computer aided diagnosis systems. This study set out to test the hypothesis that joint learning of false positive (FP) nodule reduction and nodule segmentation can improve the computer aided diagnosis (CAD) systems' performance on both tasks. To support this hypothesis we propose a 3D deep multi-task CNN to tackle these two problems jointly. We tested our system on LUNA16 dataset and achieved an average dice similarity coefficient (DSC) of 91% as segmentation accuracy and a score of nearly 92% for FP reduction. As a proof of our hypothesis, we showed improvements of segmentation and FP reduction tasks over two baselines. Our results support that joint training of these two tasks through a multi-task learning approach improves system performance on both. We also showed that a semi-supervised approach can be used to overcome the limitation of lack of labeled data for the 3D segmentation task.

##### Abstract (translated by Google)
早期发现肺结节在肺癌筛查中具有重要意义。现有研究认识到CAD系统在早期发现和诊断肺结节方面所发挥的关键作用。然而，许多用作癌症检测工具的CAD系统会产生大量的误报（FP）并需要进一步的FP降低步骤。此外，肺癌的早期诊断和治疗指南由异常的不同形状和体积测量组成。分割是我们理解结节形态的核心，使其成为计算机辅助诊断系统领域的主要兴趣领域。本研究旨在检验联合学习假阳性（FP）结节减少和结节分割可以提高计算机辅助诊断（CAD）系统在两项任务中的表现的假设。为了支持这个假设，我们提出了一个3D深度多任务CNN来共同解决这两个问题。我们在LUNA16数据集上测试了我们的系统，实现了91％的平均模子相似系数（DSC）作为分割准确性，FP降低的分数接近92％。作为我们假设的一个证明，我们在两条基线上显示了细分和FP减少任务的改进。我们的研究结果支持通过多任务学习方法对这两项任务进行联合培训可以提高两者的系统性能。我们还表明，可以使用半监督方法来克服3D分割任务缺乏标记数据的局限性。

##### URL
[http://arxiv.org/abs/1802.06181](http://arxiv.org/abs/1802.06181)

##### PDF
[http://arxiv.org/pdf/1802.06181](http://arxiv.org/pdf/1802.06181)

