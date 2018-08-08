---
layout: post
title: "Semi-supervised Deep Generative Modelling of Incomplete Multi-Modality Emotional Data"
date: 2018-07-27 07:07:36
categories: arXiv_CV
tags: arXiv_CV Inference Classification Relation Recognition
author: Changde Du, Changying Du, Hao Wang, Jinpeng Li, Wei-Long Zheng, Bao-Liang Lu, Huiguang He
mathjax: true
---

* content
{:toc}

##### Abstract
There are threefold challenges in emotion recognition. First, it is difficult to recognize human's emotional states only considering a single modality. Second, it is expensive to manually annotate the emotional data. Third, emotional data often suffers from missing modalities due to unforeseeable sensor malfunction or configuration issues. In this paper, we address all these problems under a novel multi-view deep generative framework. Specifically, we propose to model the statistical relationships of multi-modality emotional data using multiple modality-specific generative networks with a shared latent space. By imposing a Gaussian mixture assumption on the posterior approximation of the shared latent variables, our framework can learn the joint deep representation from multiple modalities and evaluate the importance of each modality simultaneously. To solve the labeled-data-scarcity problem, we extend our multi-view model to semi-supervised learning scenario by casting the semi-supervised classification problem as a specialized missing data imputation task. To address the missing-modality problem, we further extend our semi-supervised multi-view model to deal with incomplete data, where a missing view is treated as a latent variable and integrated out during inference. This way, the proposed overall framework can utilize all available (both labeled and unlabeled, as well as both complete and incomplete) data to improve its generalization ability. The experiments conducted on two real multi-modal emotion datasets demonstrated the superiority of our framework.

##### Abstract (translated by Google)
情绪识别有三个挑战。首先，仅考虑单一形态很难识别人类的情绪状态。其次，手动注释情绪数据是昂贵的。第三，由于不可预见的传感器故障或配置问题，情绪数据经常因缺少模态而受损。在本文中，我们在一个新的多视图深度生成框架下解决所有这些问题。具体而言，我们建议使用具有共享潜在空间的多模态特定生成网络来模拟多模态情绪数据的统计关系。通过对共享潜变量的后验近似强加高斯混合假设，我们的框架可以从多种模态中学习联合深度表示，并同时评估每种模态的重要性。为了解决标签数据稀缺问题，我们将半监督分类问题作为专门的缺失数据插补任务，将我们的多视图模型扩展到半监督学习场景。为了解决缺失模态问题，我们进一步扩展了我们的半监督多视图模型来处理不完整的数据，其中缺失的视图被视为潜在变量并在推理期间被整合。这样，所提出的整体框架可以利用所有可用的（标记的和未标记的，以及完整的和不完整的）数据来提高其泛化能力。在两个真实的多模态情感数据集上进行的实验证明了我们框架的优越性。

##### URL
[http://arxiv.org/abs/1808.02096](http://arxiv.org/abs/1808.02096)

##### PDF
[http://arxiv.org/pdf/1808.02096](http://arxiv.org/pdf/1808.02096)

