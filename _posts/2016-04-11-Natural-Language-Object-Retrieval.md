---
layout: post
title: "Natural Language Object Retrieval"
date: 2016-04-11 03:36:58
categories: arXiv_CV
tags: arXiv_CV Image_Caption Image_Retrieval Knowledge Caption
author: Ronghang Hu, Huazhe Xu, Marcus Rohrbach, Jiashi Feng, Kate Saenko, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the task of natural language object retrieval, to localize a target object within a given image based on a natural language query of the object. Natural language object retrieval differs from text-based image retrieval task as it involves spatial information about objects within the scene and global scene context. To address this issue, we propose a novel Spatial Context Recurrent ConvNet (SCRC) model as scoring function on candidate boxes for object retrieval, integrating spatial configurations and global scene-level contextual information into the network. Our model processes query text, local image descriptors, spatial configurations and global context features through a recurrent network, outputs the probability of the query text conditioned on each candidate box as a score for the box, and can transfer visual-linguistic knowledge from image captioning domain to our task. Experimental results demonstrate that our method effectively utilizes both local and global information, outperforming previous baseline methods significantly on different datasets and scenarios, and can exploit large scale vision and language datasets for knowledge transfer.

##### Abstract (translated by Google)
在本文中，我们提出自然语言对象检索的任务，根据对象的自然语言查询来定位给定图像中的目标对象。自然语言对象检索不同于基于文本的图像检索任务，因为它涉及场景内的对象和全局场景上下文的空间信息。为了解决这个问题，我们提出了一种新的空间上下文递归ConvNet（SCRC）模型作为候选对象检索框的评分函数，将空间配置和全局场景级上下文信息整合到网络中。我们的模型通过循环网络处理查询文本，局部图像描述符，空间配置和全局上下文特征，将以每个候选框为条件的查询文本的概率输出为框的分数，并且可以将图像字幕的视觉语言知识域到我们的任务。实验结果表明，我们的方法有效利用本地和全球信息，显着优于以前的基线方法在不同的数据集和情景，并可以利用大规模的视觉和语言数据集的知识转移。

##### URL
[https://arxiv.org/abs/1511.04164](https://arxiv.org/abs/1511.04164)

##### PDF
[https://arxiv.org/pdf/1511.04164](https://arxiv.org/pdf/1511.04164)

