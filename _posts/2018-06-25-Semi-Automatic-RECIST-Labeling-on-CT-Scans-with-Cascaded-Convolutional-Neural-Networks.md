---
layout: post
title: "Semi-Automatic RECIST Labeling on CT Scans with Cascaded Convolutional Neural Networks"
date: 2018-06-25 14:52:07
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Relation
author: Youbao Tang, Adam P. Harrison, Mohammadhadi Bagheri, Jing Xiao, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Response evaluation criteria in solid tumors (RECIST) is the standard measurement for tumor extent to evaluate treatment responses in cancer patients. As such, RECIST annotations must be accurate. However, RECIST annotations manually labeled by radiologists require professional knowledge and are time-consuming, subjective, and prone to inconsistency among different observers. To alleviate these problems, we propose a cascaded convolutional neural network based method to semi-automatically label RECIST annotations and drastically reduce annotation time. The proposed method consists of two stages: lesion region normalization and RECIST estimation. We employ the spatial transformer network (STN) for lesion region normalization, where a localization network is designed to predict the lesion region and the transformation parameters with a multi-task learning strategy. For RECIST estimation, we adapt the stacked hourglass network (SHN), introducing a relationship constraint loss to improve the estimation precision. STN and SHN can both be learned in an end-to-end fashion. We train our system on the DeepLesion dataset, obtaining a consensus model trained on RECIST annotations performed by multiple radiologists over a multi-year period. Importantly, when judged against the inter-reader variability of two additional radiologist raters, our system performs more stably and with less variability, suggesting that RECIST annotations can be reliably obtained with reduced labor and time.

##### Abstract (translated by Google)
实体瘤中的反应评估标准（RECIST）是评估癌症患者治疗反应的肿瘤程度的标准测量。因此，RECIST注释必须准确。然而，由放射科医师手动标记的RECIST注释需要专业知识，且耗时，主观，并且倾向于不同观察者之间的不一致。为了缓解这些问题，我们提出了一种基于级联卷积神经网络的方法来半自动标注RECIST注释并大幅减少注释时间。所提出的方法由两个阶段组成：损伤区域归一化和RECIST估计。我们采用空间变换网络（STN）进行病变区域归一化，其中定位网络被设计为通过多任务学习策略来预测病变区域和变换参数。对于RECIST估计，我们调整堆积沙漏网络（SHN），引入关系约束损失来提高估计精度。 STN和SHN都可以以端到端的方式学习。我们在DeepLesion数据集上训练我们的系统，获得由多位放射科医师在多年的时间内对RECIST注释进行培训的共识模型。重要的是，当根据另外两名放射科医师评分员的读者间差异进行判断时，我们的系统执行更稳定且变异性更小，这表明RECIST注释可以在减少劳动力和时间的情况下可靠获得。

##### URL
[http://arxiv.org/abs/1806.09507](http://arxiv.org/abs/1806.09507)

##### PDF
[http://arxiv.org/pdf/1806.09507](http://arxiv.org/pdf/1806.09507)

