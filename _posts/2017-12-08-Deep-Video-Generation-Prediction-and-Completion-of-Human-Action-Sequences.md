---
layout: post
title: "Deep Video Generation, Prediction and Completion of Human Action Sequences"
date: 2017-12-08 12:17:15
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction Quantitative
author: Haoye Cai, Chunyan Bai, Yu-Wing Tai, Chi-Keung Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Current deep learning results on video generation are limited while there are only a few first results on video prediction and no relevant significant results on video completion. This is due to the severe ill-posedness inherent in these three problems. In this paper, we focus on human action videos, and propose a general, two-stage deep framework to generate human action videos with no constraints or arbitrary number of constraints, which uniformly address the three problems: video generation given no input frames, video prediction given the first few frames, and video completion given the first and last frames. To make the problem tractable, in the first stage we train a deep generative model that generates a human pose sequence from random noise. In the second stage, a skeleton-to-image network is trained, which is used to generate a human action video given the complete human pose sequence generated in the first stage. By introducing the two-stage strategy, we sidestep the original ill-posed problems while producing for the first time high-quality video generation/prediction/completion results of much longer duration. We present quantitative and qualitative evaluation to show that our two-stage approach outperforms state-of-the-art methods in video generation, prediction and video completion. Our video result demonstration can be viewed at https://iamacewhite.github.io/supp/index.html

##### Abstract (translated by Google)
视频生成的当前深度学习结果是有限的，而在视频预测中仅有少量第一结果，并且在视频完成上没有相关的显着结果。这是由于这三个问题所固有的严重病态。在本文中，我们专注于人类活动视频，并提出了一个通用的，两阶段的深层框架来生成没有约束或任意数量约束的人类活动视频，它统一地解决了三个问题：视频生成没有输入帧，视频给出前几帧的预测，给出第一帧和最后一帧的视频完成。为了使问题变得易于处理，在第一阶段，我们训练一个深度生成模型，从随机噪声中产生一个人体姿势序列。在第二阶段，骨架到图像网络被训练，用于在第一阶段生成完整的人体姿势序列的情况下生成人类动作视频。通过引入两阶段策略，我们避开了原有的不适应问题，同时首次产生了更长时间的高质量视频生成/预测/完成结果。我们提出定量和定性评估，以表明我们的两阶段方法胜过视频生成，预测和视频完成方面的最先进的方法。我们的视频结果演示可以在https://iamacewhite.github.io/supp/index.html查看

##### URL
[http://arxiv.org/abs/1711.08682](http://arxiv.org/abs/1711.08682)

##### PDF
[http://arxiv.org/pdf/1711.08682](http://arxiv.org/pdf/1711.08682)

