---
layout: post
title: "Tubelets: Unsupervised action proposals from spatiotemporal super-voxels"
date: 2016-07-07 13:30:17
categories: arXiv_CV
tags: arXiv_CV
author: Mihir Jain, Jan van Gemert, Hervé Jégou, Patrick Bouthemy, Cees G.M. Snoek
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers the problem of localizing actions in videos as a sequences of bounding boxes. The objective is to generate action proposals that are likely to include the action of interest, ideally achieving high recall with few proposals. Our contributions are threefold. First, inspired by selective search for object proposals, we introduce an approach to generate action proposals from spatiotemporal super-voxels in an unsupervised manner, we call them Tubelets. Second, along with the static features from individual frames our approach advantageously exploits motion. We introduce independent motion evidence as a feature to characterize how the action deviates from the background and explicitly incorporate such motion information in various stages of the proposal generation. Finally, we introduce spatiotemporal refinement of Tubelets, for more precise localization of actions, and pruning to keep the number of Tubelets limited. We demonstrate the suitability of our approach by extensive experiments for action proposal quality and action localization on three public datasets: UCF Sports, MSR-II and UCF101. For action proposal quality, our unsupervised proposals beat all other existing approaches on the three datasets. For action localization, we show top performance on both the trimmed videos of UCF Sports and UCF101 as well as the untrimmed videos of MSR-II.

##### Abstract (translated by Google)
本文考虑将视频中的动作本地化为一系列边界框的问题。目标是产生可能包括感兴趣的行动的行动提案，理想情况下实现高召回率和少提案。我们的贡献是三倍的。首先，通过选择性搜索对象提议的启发，我们引入了一种方法，以无监督的方式从时空超体素生成行动建议，我们称之为“小管”。其次，随着个别框架的静态特征，我们的方法有利地利用运动。我们引入独立的运动证据作为一个特征来描述行为如何背离背景，并明确地将这些运动信息纳入提案生成的各个阶段。最后，我们介绍了小管的时空细化，以便更精确地定位动作，并修剪以保持小管的数量有限。我们通过对三个公共数据集的行动建议质量和行动定位进行广泛的实验来证明我们方法的适用性：UCF Sports，MSR-II和UCF101。对于行动建议的质量，我们的无监督提案击败了三个数据集的所有其他方法。对于动作本地化，我们展示了UCF Sports和UCF101的剪辑视频以及MSR-II的未修剪视频的最佳性能。

##### URL
[https://arxiv.org/abs/1607.02003](https://arxiv.org/abs/1607.02003)

##### PDF
[https://arxiv.org/pdf/1607.02003](https://arxiv.org/pdf/1607.02003)

