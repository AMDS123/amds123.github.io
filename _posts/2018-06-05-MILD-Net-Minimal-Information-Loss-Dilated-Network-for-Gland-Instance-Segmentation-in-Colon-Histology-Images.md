---
layout: post
title: "MILD-Net: Minimal Information Loss Dilated Network for Gland Instance Segmentation in Colon Histology Images"
date: 2018-06-05 23:38:01
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Simon Graham, Hao Chen, Qi Dou, Pheng-Ann Heng, Nasir Rajpoot
mathjax: true
---

* content
{:toc}

##### Abstract
The analysis of glandular morphology within colon histopathology images is a crucial step in determining the stage of colon cancer. Despite the importance of this task, manual segmentation is laborious, time-consuming and can suffer from subjectivity among pathologists. The rise of computational pathology has led to the development of automated methods for gland segmentation that aim to overcome the challenges of manual segmentation. However, this task is non-trivial due to the large variability in glandular appearance and the difficulty in differentiating between certain glandular and non-glandular histological structures. Furthermore, within pathological practice, a measure of uncertainty is essential for diagnostic decision making. For example, ambiguous areas may require further examination from numerous pathologists. To address these challenges, we propose a fully convolutional neural network that counters the loss of information caused by max- pooling by re-introducing the original image at multiple points within the network. We also use atrous spatial pyramid pooling with varying dilation rates for resolution maintenance and multi-level aggregation. To incorporate uncertainty, we introduce random transformations during test time for an enhanced segmentation result that simultaneously generates an uncertainty map, highlighting areas of ambiguity. We show that this map can be used to define a metric for disregarding predictions with high uncertainty. The proposed network achieves state-of-the-art performance on the GlaS challenge dataset, as part of MICCAI 2015, and on a second independent colorectal adenocarcinoma dataset.

##### Abstract (translated by Google)
结肠组织病理学图像中腺体形态的分析是确定结肠癌阶段的关键步骤。尽管这项任务非常重要，但手动分割费时费力，并且会受到病理学家之间的主观性的影响。计算病理学的兴起导致了腺体分割的自动化方法的发展，其目的是克服手动分割的挑战。然而，由于腺体外观的巨大变异性和区分某些腺体组织结构和非腺体组织结构的困难，这项任务并非微不足道。此外，在病理实践中，不确定性的度量对诊断决策至关重要。例如，模糊区域可能需要来自许多病理学家的进一步检查。为了应对这些挑战，我们提出了一个完全卷积神经网络，通过在网络中的多个点重新引入原始图像来对抗由最大化引起的信息丢失。我们还使用具有不同扩张速率的空间金字塔池来解决维护和多级聚合。为了结合不确定性，我们在测试时间内引入随机变换，以获得增强的分割结果，同时生成不确定性图，突出显示不明确的区域。我们证明这张图可以用来定义一个不确定性高的预测的度量。拟议的网络在GlaS挑战数据集上获得了最先进的性能，作为MICCAI 2015的一部分，以及第二个独立的结肠直肠腺癌数据集。

##### URL
[http://arxiv.org/abs/1806.01963](http://arxiv.org/abs/1806.01963)

##### PDF
[http://arxiv.org/pdf/1806.01963](http://arxiv.org/pdf/1806.01963)

