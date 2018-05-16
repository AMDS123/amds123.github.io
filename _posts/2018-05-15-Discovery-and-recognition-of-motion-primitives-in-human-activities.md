---
layout: post
title: "Discovery and recognition of motion primitives in human activities"
date: 2018-05-15 10:24:48
categories: arXiv_AI
tags: arXiv_AI Recognition
author: Marta Sanzari, Valsamis Ntouskos, Fiora Pirri
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel framework for the automatic discovery and recognition of motion primitives in videos of human activities. Given the 3D pose of a human in a video, human motion primitives are discovered by optimizing the `motion flux', a quantity which captures the motion variation of a group of skeletal joints. A normalization of the primitives is proposed in order to make them invariant with respect to a subject anatomical variations and data sampling rate. The discovered primitives are unknown and unlabeled and are unsupervisedly collected into classes via a hierarchical non-parametric Bayes mixture model. Once classes are determined and labeled they are further analyzed for establishing models for recognizing discovered primitives. Each primitive model is defined by a set of learned parameters. 
 Given new video data and given the estimated pose of the subject appearing on the video, the motion is segmented into primitives, which are recognized with a probability given according to the parameters of the learned models. 
 Using our framework we build a publicly available dataset of human motion primitives, using sequences taken from well-known motion capture datasets. We expect that our framework, by providing an objective way for discovering and categorizing human motion, will be a useful tool in numerous research fields including video analysis, human inspired motion generation, learning by demonstration, intuitive human-robot interaction, and human behavior analysis.

##### Abstract (translated by Google)
我们提出了一个新的框架，用于自动发现和识别人类活动视频中的运动基元。考虑到视频中人的三维姿态，通过优化“运动通量”来发现人体运动基元，该运动通量是捕获一组骨骼关节的运动变化的量。提出基元的规范化以使它们相对于主题解剖变化和数据采样率不变。发现的基元是未知的，未标记的，并且通过分层非参数贝叶斯混合模型无监督地收集到类中。一旦确定并标记了类，就会进一步分析它们以建立识别发现的基元的模型。每个原始模型由一组学习参数定义。
 给定新的视频数据并给出出现在视频上的对象的估计姿态，运动被分割成基元，基元根据学习模型的参数给出概率。
 使用我们的框架，我们使用从众所周知的动作捕捉数据集中提取的序列，构建一个公开可用的人体运动基元数据集。我们期望我们的框架通过提供客观的方式来发现和分类人体运动，将成为众多研究领域的有用工具，包括视频分析，人体感应运动生成，示范学习，直观的人机交互以及人类行为分析。

##### URL
[http://arxiv.org/abs/1709.10494](http://arxiv.org/abs/1709.10494)

##### PDF
[http://arxiv.org/pdf/1709.10494](http://arxiv.org/pdf/1709.10494)

