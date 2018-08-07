---
layout: post
title: "Entity-aware Image Caption Generation"
date: 2018-04-21 04:40:10
categories: arXiv_CV
tags: arXiv_CV Image_Caption Knowledge_Graph Knowledge Caption Inference RNN
author: Di Lu, Spencer Whitehead, Lifu Huang, Heng Ji, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Image captioning approaches currently generate descriptions which lack specific information, such as named entities that are involved in the images. In this paper we propose a new task which aims to generate informative image captions, given images and hashtags as input. We propose a simple, but effective approach in which we, first, train a CNN-LSTM model to generate a template caption based on the input image. Then we use a knowledge graph based collective inference algorithm to fill in the template with specific named entities retrieved via the hashtags. Experiments on a new benchmark dataset collected from Flickr show that our model generates news-style image descriptions with much richer information. The METEOR score of our model almost triples the score of the baseline image captioning model on our benchmark dataset, from 4.8 to 13.60.

##### Abstract (translated by Google)
图像字幕方法当前生成缺少特定信息的描述，例如图像中涉及的命名实体。在本文中，我们提出了一个新任务，旨在生成信息图像标题，给出图像和主题标签作为输入。我们提出了一种简单但有效的方法，首先，我们训练CNN-LSTM模型，以根据输入图像生成模板标题。然后我们使用基于知识图的集体推理算法，用通过主题标签检索的特定命名实体填充模板。对从Flickr收集的新基准数据集的实验表明，我们的模型生成具有更丰富信息的新闻风格图像描述。我们模型的METEOR分数几乎是我们基准数据集上基线图像字幕模型得分的三倍，从4.8到13.60。

##### URL
[https://arxiv.org/abs/1804.07889](https://arxiv.org/abs/1804.07889)

##### PDF
[https://arxiv.org/pdf/1804.07889](https://arxiv.org/pdf/1804.07889)

