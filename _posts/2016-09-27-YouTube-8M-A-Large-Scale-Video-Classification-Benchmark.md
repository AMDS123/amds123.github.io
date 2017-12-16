---
layout: post
title: "YouTube-8M: A Large-Scale Video Classification Benchmark"
date: 2016-09-27 21:21:49
categories: arXiv_CV
tags: arXiv_CV Image_Caption Knowledge_Graph Knowledge Video_Classification Classification
author: Sami Abu-El-Haija, Nisarg Kothari, Joonseok Lee, Paul Natsev, George Toderici, Balakrishnan Varadarajan, Sudheendra Vijayanarasimhan
mathjax: true
---

* content
{:toc}

##### Abstract
Many recent advancements in Computer Vision are attributed to large datasets. Open-source software packages for Machine Learning and inexpensive commodity hardware have reduced the barrier of entry for exploring novel approaches at scale. It is possible to train models over millions of examples within a few days. Although large-scale datasets exist for image understanding, such as ImageNet, there are no comparable size video classification datasets. In this paper, we introduce YouTube-8M, the largest multi-label video classification dataset, composed of ~8 million videos (500K hours of video), annotated with a vocabulary of 4800 visual entities. To get the videos and their labels, we used a YouTube video annotation system, which labels videos with their main topics. While the labels are machine-generated, they have high-precision and are derived from a variety of human-based signals including metadata and query click signals. We filtered the video labels (Knowledge Graph entities) using both automated and manual curation strategies, including asking human raters if the labels are visually recognizable. Then, we decoded each video at one-frame-per-second, and used a Deep CNN pre-trained on ImageNet to extract the hidden representation immediately prior to the classification layer. Finally, we compressed the frame features and make both the features and video-level labels available for download. We trained various (modest) classification models on the dataset, evaluated them using popular evaluation metrics, and report them as baselines. Despite the size of the dataset, some of our models train to convergence in less than a day on a single machine using TensorFlow. We plan to release code for training a TensorFlow model and for computing metrics.

##### Abstract (translated by Google)
计算机视觉的许多最新进展归因于大型数据集。机器学习的开源软件包和便宜的商品硬件已经减少了进入大规模探索新方法的门槛。在几天内就可以训练数百万个示例。虽然大规模的数据集存在的图像理解，如ImageNet，没有可比尺寸的视频分类数据集。在本文中，我们介绍了最大的多标签视频分类数据集YouTube-8M，它由800万个视频（500K小时的视频）组成，用4800个视觉实体的词汇表注释。要获取视频及其标签，我们使用了YouTube视频注释系统，该视频注释系统将视频标记为主要主题。虽然标签是由机器生成的，但是它们具有高精度，并且源自各种基于人的信号，包括元数据和查询点击信号。我们使用自动和手动策略策略过滤了视频标签（知识图实体），包括询问人类评估者标签是否在视觉上可识别。然后，我们以每帧一帧的速度对每个视频进行解码，并且使用在ImageNet上预先训练过的深度CNN来在分类层之前提取隐藏表示。最后，我们压缩了框架功能，并使功能和视频标签都可供下载。我们在数据集上训练了各种不同的（适度的）分类模型，使用流行的评估指标对它们进行评估，并将其作为基线进行报告。尽管数据集的大小，我们的一些模型在使用TensorFlow的单台机器上不到一天的时间内就会收敛。我们计划发布用于训练TensorFlow模型和计算度量标准的代码。

##### URL
[https://arxiv.org/abs/1609.08675](https://arxiv.org/abs/1609.08675)

##### PDF
[https://arxiv.org/pdf/1609.08675](https://arxiv.org/pdf/1609.08675)

