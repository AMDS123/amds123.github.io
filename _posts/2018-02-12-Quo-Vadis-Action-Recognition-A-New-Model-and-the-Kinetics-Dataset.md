---
layout: post
title: "Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset"
date: 2018-02-12 17:10:11
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Image_Classification Classification Recognition
author: Joao Carreira, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
The paucity of videos in current action classification datasets (UCF-101 and HMDB-51) has made it difficult to identify good video architectures, as most methods obtain similar performance on existing small-scale benchmarks. This paper re-evaluates state-of-the-art architectures in light of the new Kinetics Human Action Video dataset. Kinetics has two orders of magnitude more data, with 400 human action classes and over 400 clips per class, and is collected from realistic, challenging YouTube videos. We provide an analysis on how current architectures fare on the task of action classification on this dataset and how much performance improves on the smaller benchmark datasets after pre-training on Kinetics. 
 We also introduce a new Two-Stream Inflated 3D ConvNet (I3D) that is based on 2D ConvNet inflation: filters and pooling kernels of very deep image classification ConvNets are expanded into 3D, making it possible to learn seamless spatio-temporal feature extractors from video while leveraging successful ImageNet architecture designs and even their parameters. We show that, after pre-training on Kinetics, I3D models considerably improve upon the state-of-the-art in action classification, reaching 80.9% on HMDB-51 and 98.0% on UCF-101.

##### Abstract (translated by Google)
目前行动分类数据集（UCF-101和HMDB-51）中缺少视频使得难以确定好的视频体系结构，因为大多数方法在现有的小规模基准测试中获得类似的性能。本文根据新的动力学人类行动视频数据集重新评估最先进的架构。动力学的数据量增加了两个数量级，包括400个人类动作班，每班有超过400个片段，并从逼真，具有挑战性的YouTube视频中收集。我们提供了关于当前体系结构在该数据集上的行为分类任务上的分析以及在对动力学进行预训练之后在较小的基准数据集上有多少性能改进的分析。
 我们还推出了基于2D ConvNet充气的新型双流充气3D ConvNet（I3D）：过滤器和集中非常深的图像分类的内核ConvNets被扩展为3D，使得可以从视频中学习无缝的时空特征提取器同时利用成功的ImageNet架构设计甚至参数。我们证明，在对动力学进行预训练之后，I3D模型在行动分类方面显着改善，HMDB-51达到80.9％，UCF-101达到98.0％。

##### URL
[http://arxiv.org/abs/1705.07750](http://arxiv.org/abs/1705.07750)

##### PDF
[http://arxiv.org/pdf/1705.07750](http://arxiv.org/pdf/1705.07750)

