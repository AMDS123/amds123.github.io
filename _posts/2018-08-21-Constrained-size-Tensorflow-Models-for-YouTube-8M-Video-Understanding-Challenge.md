---
layout: post
title: "Constrained-size Tensorflow Models for YouTube-8M Video Understanding Challenge"
date: 2018-08-21 02:22:44
categories: arXiv_CV
tags: arXiv_CV Video_Caption Inference
author: Tianqi Liu, Bo Liu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents our 10th place solution to the second YouTube-8M video understanding competition which challenges participates to build a constrained-size model to classify millions of YouTube videos into thousands of classes. Our final model consists of four single models aggregated into one tensorflow graph. For each single model, we use the same network architecture as in the winning solution of the first YouTube-8M video understanding competition, namely Gated NetVLAD. We train the single models separately in tensorflow's default float32 precision, then replace weights with float16 precision and ensemble them in the evaluation and inference stages., achieving 48.5% compression rate without loss of precision. Our best model achieved 88.324% GAP on private leaderboard. The code is publicly available at https://github.com/boliu61/youtube-8m

##### Abstract (translated by Google)
本文介绍了第二个YouTube-8M视频理解竞赛的第10个解决方案，挑战参与构建一个受限大小的模型，将数百万个YouTube视频分类为数千个课程。我们的最终模型由四个单一模型聚合到一个张量流图中组成。对于每个单一型号，我们使用与第一个YouTube-8M视频理解竞赛的获胜解决方案相同的网络架构，即Gated NetVLAD。我们在tensorflow的默认float32精度中单独训练单个模型，然后用float16精度替换权重，并在评估和推理阶段对它们进行整合，达到48.5％的压缩率而不会损失精度。我们的最佳模式在私人排行榜上实现了88.324％的GAP。该代码可在https://github.com/boliu61/youtube-8m上公开获取

##### URL
[http://arxiv.org/abs/1808.06739](http://arxiv.org/abs/1808.06739)

##### PDF
[http://arxiv.org/pdf/1808.06739](http://arxiv.org/pdf/1808.06739)

