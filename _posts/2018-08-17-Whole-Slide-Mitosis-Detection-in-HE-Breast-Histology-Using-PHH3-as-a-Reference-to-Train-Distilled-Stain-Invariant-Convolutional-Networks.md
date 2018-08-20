---
layout: post
title: "Whole-Slide Mitosis Detection in H&E Breast Histology Using PHH3 as a Reference to Train Distilled Stain-Invariant Convolutional Networks"
date: 2018-08-17 15:14:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge CNN Detection
author: David Tellez, Maschenka Balkenhol, Irene Otte-Holler, Rob van de Loo, Rob Vogels, Peter Bult, Carla Wauters, Willem Vreuls, Suzanne Mol, Nico Karssemeijer, Geert Litjens, Jeroen van der Laak, Francesco Ciompi
mathjax: true
---

* content
{:toc}

##### Abstract
Manual counting of mitotic tumor cells in tissue sections constitutes one of the strongest prognostic markers for breast cancer. This procedure, however, is time-consuming and error-prone. We developed a method to automatically detect mitotic figures in breast cancer tissue sections based on convolutional neural networks (CNNs). Application of CNNs to hematoxylin and eosin (H&amp;E) stained histological tissue sections is hampered by: (1) noisy and expensive reference standards established by pathologists, (2) lack of generalization due to staining variation across laboratories, and (3) high computational requirements needed to process gigapixel whole-slide images (WSIs). In this paper, we present a method to train and evaluate CNNs to specifically solve these issues in the context of mitosis detection in breast cancer WSIs. First, by combining image analysis of mitotic activity in phosphohistone-H3 (PHH3) restained slides and registration, we built a reference standard for mitosis detection in entire H&amp;E WSIs requiring minimal manual annotation effort. Second, we designed a data augmentation strategy that creates diverse and realistic H&amp;E stain variations by modifying the hematoxylin and eosin color channels directly. Using it during training combined with network ensembling resulted in a stain invariant mitosis detector. Third, we applied knowledge distillation to reduce the computational requirements of the mitosis detection ensemble with a negligible loss of performance. The system was trained in a single-center cohort and evaluated in an independent multicenter cohort from The Cancer Genome Atlas on the three tasks of the Tumor Proliferation Assessment Challenge (TUPAC). We obtained a performance within the top-3 best methods for most of the tasks of the challenge.

##### Abstract (translated by Google)
人工计数组织切片中的有丝分裂肿瘤细胞是乳腺癌最强的预后标志之一。然而，该过程耗时且容易出错。我们开发了一种基于卷积神经网络（CNN）自动检测乳腺癌组织切片中有丝分裂图的方法。 CNNs在苏木精和伊红（H＆amp; E）染色的组织切片组织中的应用受到以下因素的阻碍：（1）由病理学家建立的嘈杂且昂贵的参考标准，（2）由于实验室之间的染色变化而缺乏概括性，以及（3）高处理千兆像素整张幻灯片图像（WSI）所需的计算要求。在本文中，我们提出了一种训练和评估CNN的方法，以在乳腺癌WSI中有丝分裂检测的背景下专门解决这些问题。首先，通过结合磷酸化组蛋白-H3（PHH3）重新定位的载玻片和登记中的有丝分裂活性的图像分析，我们在整个H＆amp; E WSI中建立了有丝分裂检测的参考标准，其需要最少的手动注释努力。其次，我们设计了一种数据增强策略，通过直接修改苏木精和伊红色通道，创建多样化和逼真的H＆amp; E染色变异。在训练期间使用它结合网络集成导致染色不变的有丝分裂检测器。第三，我们应用知识蒸馏来降低有丝分裂检测集合的计算要求，同时可忽略不计的性能损失。该系统在单中心队列中进行训练，并在来自癌症基因组图谱的独立多中心队列中评估肿瘤增殖评估挑战（TUPAC）的三个任务。对于挑战的大多数任务，我们在前3种最佳方法中获得了表现。

##### URL
[http://arxiv.org/abs/1808.05896](http://arxiv.org/abs/1808.05896)

##### PDF
[http://arxiv.org/pdf/1808.05896](http://arxiv.org/pdf/1808.05896)

