---
layout: post
title: "Deep Models for Engagement Assessment With Scarce Label Information"
date: 2016-10-21 15:05:16
categories: arXiv_CV
tags: arXiv_CV
author: Feng Li, Guangfan Zhang, Wei Wang, Roger Xu, Tom Schnell, Jonathan Wen, Frederic McKenzie, Jiang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Task engagement is defined as loadings on energetic arousal (affect), task motivation, and concentration (cognition). It is usually challenging and expensive to label cognitive state data, and traditional computational models trained with limited label information for engagement assessment do not perform well because of overfitting. In this paper, we proposed two deep models (i.e., a deep classifier and a deep autoencoder) for engagement assessment with scarce label information. We recruited 15 pilots to conduct a 4-h flight simulation from Seattle to Chicago and recorded their electroencephalograph (EEG) signals during the simulation. Experts carefully examined the EEG signals and labeled 20 min of the EEG data for each pilot. The EEG signals were preprocessed and power spectral features were extracted. The deep models were pretrained by the unlabeled data and were fine-tuned by a different proportion of the labeled data (top 1%, 3%, 5%, 10%, 15%, and 20%) to learn new representations for engagement assessment. The models were then tested on the remaining labeled data. We compared performances of the new data representations with the original EEG features for engagement assessment. Experimental results show that the representations learned by the deep models yielded better accuracies for the six scenarios (77.09%, 80.45%, 83.32%, 85.74%, 85.78%, and 86.52%), based on different proportions of the labeled data for training, as compared with the corresponding accuracies (62.73%, 67.19%, 73.38%, 79.18%, 81.47%, and 84.92%) achieved by the original EEG features. Deep models are effective for engagement assessment especially when less label information was used for training.

##### Abstract (translated by Google)
任务参与被定义为精力充沛（情绪），任务动机和集中（认知）的负荷。标记认知状态数据通常是具有挑战性的和昂贵的，并且用有限的标签信息训练用于参与评估的传统计算模型由于过度拟合而表现不佳。在本文中，我们提出了两种深度模型（即深度分类器和深度自动编码器），用于稀缺标签信息的参与评估。我们招募了15名飞行员进行从西雅图到芝加哥的4小时飞行模拟，并在模拟期间记录他们的脑电图（EEG）信号。专家仔细检查了EEG信号，并标记了每个飞行员20分钟的EEG数据。对脑电信号进行预处理，提取功率谱特征。深度模型是由未标记的数据预训练，并通过不同比例的标记数据（最高1％，3％，5％，10％，15％和20％）进行微调以学习新的交涉评估。然后对剩余的标记数据进行模型测试。我们将新数据表示的性能与原始EEG特征进行了比较。实验结果表明，深度模型所学的表征对于六种情景（77.09％，80.45％，83.32％，85.74％，85.78％和86.52％），根据不同比例的训练标注数据，与原有脑电特征所对应的精度（62.73％，6​​7.19％，73.38％，79.18％，81.47％，84.92％）相比较。深度模型对于参与度评估是有效的，尤其是当较少的标签信息用于培训时。

##### URL
[https://arxiv.org/abs/1610.06815](https://arxiv.org/abs/1610.06815)

##### PDF
[https://arxiv.org/pdf/1610.06815](https://arxiv.org/pdf/1610.06815)

