---
layout: post
title: "A Probabilistic U-Net for Segmentation of Ambiguous Images"
date: 2018-06-13 13:47:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Simon A. A. Kohl, Bernardino Romera-Paredes, Clemens Meyer, Jeffrey De Fauw, Joseph R. Ledsam, Klaus H. Maier-Hein, S. M. Ali Eslami, Danilo Jimenez Rezende, Olaf Ronneberger
mathjax: true
---

* content
{:toc}

##### Abstract
Many real-world vision problems suffer from inherent ambiguities. In clinical applications for example, it might not be clear from a CT scan alone which particular region is cancer tissue. Therefore a group of graders typically produces a set of diverse but plausible segmentations. We consider the task of learning a distribution over segmentations given an input. To this end we propose a generative segmentation model based on a combination of a U-Net with a conditional variational autoencoder that is capable of efficiently producing an unlimited number of plausible hypotheses. We show on a lung abnormalities segmentation task and on a Cityscapes segmentation task that our model reproduces the possible segmentation variants as well as the frequencies with which they occur, doing so significantly better than published approaches. These models could have a high impact in real-world applications, such as being used as clinical decision-making algorithms accounting for multiple plausible semantic segmentation hypotheses to provide possible diagnoses and recommend further actions to resolve the present ambiguities.

##### Abstract (translated by Google)
许多现实世界的视觉问题都存在固有的模糊性。例如在临床应用中，单独CT扫描可能并不清楚哪个特定区域是癌症组织。因此，一组分级人员通常会产生一组不同的但合理的分割。我们考虑在给定输入的情况下学习分段分布的任务。为此，我们提出了一种基于U-Net与条件变分自动编码器相结合的生成分割模型，该模型能够有效地产生无限数量的合理假设。我们在肺部异常分割任务和Cityscapes分割任务上展示我们的模型再现可能的分割变体以及它们发生的频率，这比已公开的方法显着更好。这些模型可能会对现实世界的应用产生很大的影响，比如被用作临床决策算法来解释多个合理的语义分割假设，以提供可能的诊断并推荐进一步的行动来解决当前的模糊问题。

##### URL
[http://arxiv.org/abs/1806.05034](http://arxiv.org/abs/1806.05034)

##### PDF
[http://arxiv.org/pdf/1806.05034](http://arxiv.org/pdf/1806.05034)

