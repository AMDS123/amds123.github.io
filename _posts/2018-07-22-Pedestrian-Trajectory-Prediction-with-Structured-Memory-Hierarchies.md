---
layout: post
title: "Pedestrian Trajectory Prediction with Structured Memory Hierarchies"
date: 2018-07-22 23:17:12
categories: arXiv_CV
tags: arXiv_CV Salient RNN Prediction
author: Tharindu Fernando, Simon Denman, Sridha Sridharan, Clinton Fookes
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel framework for human trajectory prediction based on multimodal data (video and radar). Motivated by recent neuroscience discoveries, we propose incorporating a structured memory component in the human trajectory prediction pipeline to capture historical information to improve performance. We introduce structured LSTM cells for modelling the memory content hierarchically, preserving the spatiotemporal structure of the information and enabling us to capture both short-term and long-term context. We demonstrate how this architecture can be extended to integrate salient information from multiple modalities to automatically store and retrieve important information for decision making without any supervision. We evaluate the effectiveness of the proposed models on a novel multimodal dataset that we introduce, consisting of 40,000 pedestrian trajectories, acquired jointly from a radar system and a CCTV camera system installed in a public place. The performance is also evaluated on the publicly available New York Grand Central pedestrian database. In both settings, the proposed models demonstrate their capability to better anticipate future pedestrian motion compared to existing state of the art.

##### Abstract (translated by Google)
本文提出了一种基于多模态数据（视频和雷达）的人体轨迹预测框架。在最近的神经科学发现的推动下，我们建议在人类轨迹预测管道中加入结构化记忆组件，以捕获历史信息以提高性能。我们引入结构化LSTM单元，用于对存储器内容进行分层建模，保留信息的时空结构，使我们能够捕获短期和长期背景。我们演示了如何扩展此体系结构以集成来自多种模态的显着信息，以自动存储和检索重要信息，以便在没有任何监督的情况下进行决策。我们评估了所提出的模型对我们引入的新型多模态数据集的有效性，该数据集由40,000个行人轨迹组成，由雷达系统和安装在公共场所的闭路电视摄像系统共同获得。此表现还在公众可用的纽约中央行人数据库中进行评估。在这两种情况下，与现有技术相比，所提出的模型展示了它们更好地预测未来行人运动的能力。

##### URL
[http://arxiv.org/abs/1807.08381](http://arxiv.org/abs/1807.08381)

##### PDF
[http://arxiv.org/pdf/1807.08381](http://arxiv.org/pdf/1807.08381)

