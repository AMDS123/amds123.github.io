---
layout: post
title: "Leveraging Uncertainty Estimates for Predicting Segmentation Quality"
date: 2018-07-02 07:42:51
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning Prediction
author: Terrance DeVries, Graham W. Taylor
mathjax: true
---

* content
{:toc}

##### Abstract
The use of deep learning for medical imaging has seen tremendous growth in the research community. One reason for the slow uptake of these systems in the clinical setting is that they are complex, opaque and tend to fail silently. Outside of the medical imaging domain, the machine learning community has recently proposed several techniques for quantifying model uncertainty (i.e.~a model knowing when it has failed). This is important in practical settings, as we can refer such cases to manual inspection or correction by humans. In this paper, we aim to bring these recent results on estimating uncertainty to bear on two important outputs in deep learning-based segmentation. The first is producing spatial uncertainty maps, from which a clinician can observe where and why a system thinks it is failing. The second is quantifying an image-level prediction of failure, which is useful for isolating specific cases and removing them from automated pipelines. We also show that reasoning about spatial uncertainty, the first output, is a useful intermediate representation for generating segmentation quality predictions, the second output. We propose a two-stage architecture for producing these measures of uncertainty, which can accommodate any deep learning-based medical segmentation pipeline.

##### Abstract (translated by Google)
利用深度学习进行医学成像已经在研究界取得了巨大的发展。在临床环境中缓慢摄取这些系统的一个原因是它们复杂，不透明并且倾向于无声地失败。在医学成像领域之外，机器学习社区最近提出了几种用于量化模型不确定性的技术（即知道何时失败的模型）。这在实际环境中很重要，因为我们可以将这些情况提交给人工进行人工检查或校正。在本文中，我们的目标是将这些最近的结果用于估计不确定性，以支持基于深度学习的分割中的两个重要输出。第一个是生成空间不确定性图，临床医生可以从中观察系统认为失败的位置和原因。第二个是量化图像级别的故障预测，这对于隔离特定情况并从自动化管道中删除它们非常有用。我们还表明，关于空间不确定性的推理，第一个输出，是用于生成分割质量预测的有用中间表示，第二个输出。我们提出了一种用于产生这些不确定性测量的两阶段架构，它可以适应任何基于深度学习的医学分割管道。

##### URL
[http://arxiv.org/abs/1807.00502](http://arxiv.org/abs/1807.00502)

##### PDF
[http://arxiv.org/pdf/1807.00502](http://arxiv.org/pdf/1807.00502)

