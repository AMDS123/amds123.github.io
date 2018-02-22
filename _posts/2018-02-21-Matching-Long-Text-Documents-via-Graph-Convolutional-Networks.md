---
layout: post
title: "Matching Long Text Documents via Graph Convolutional Networks"
date: 2018-02-21 08:01:41
categories: arXiv_CL
tags: arXiv_CL CNN Deep_Learning Relation
author: Bang Liu, Ting Zhang, Di Niu, Jinghong Lin, Kunfeng Lai, Yu Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Identifying the relationship between two text objects is a core research problem underlying many natural language processing tasks. A wide range of deep learning schemes have been proposed for text matching, mainly focusing on sentence matching, question answering or query document matching. We point out that existing approaches do not perform well at matching long documents, which is critical, for example, to AI-based news article understanding and event or story formation. The reason is that these methods either omit or fail to fully utilize complicated semantic structures in long documents. In this paper, we propose a graph approach to text matching, especially targeting long document matching, such as identifying whether two news articles report the same event in the real world, possibly with different narratives. We propose the Concept Interaction Graph to yield a graph representation for a document, with vertices representing different concepts, each being one or a group of coherent keywords in the document, and with edges representing the interactions between different concepts, connected by sentences in the document. Based on the graph representation of document pairs, we further propose a Siamese Encoded Graph Convolutional Network that learns vertex representations through a Siamese neural network and aggregates the vertex features though Graph Convolutional Networks to generate the matching result. Extensive evaluation of the proposed approach based on two labeled news article datasets created at Tencent for its intelligent news products show that the proposed graph approach to long document matching significantly outperforms a wide range of state-of-the-art methods.

##### Abstract (translated by Google)
识别两个文本对象之间的关系是许多自然语言处理任务的核心研究问题。已经提出了广泛的深度学习方案用于文本匹配，主要集中在句子匹配，问题回答或查询文档匹配。我们指出，现有的方法在匹配长文档方面表现不佳，例如，对基于人工智能的新闻文章理解和事件或故事形成至关重要。原因是这些方法要么在长文档中省略或不能充分利用复杂的语义结构。在本文中，我们提出了一种文本匹配的图表方法，特别是针对长文档匹配的方法，例如识别两篇新闻报道是否在现实世界中报告相同的事件，可能会有不同的叙述。我们提出了概念交互图来产生一个文档的图形表示，顶点代表不同的概念，每个概念在文档中都是一个或一组连贯的关键字，并且边代表不同概念之间的交互，由文档中的句子连接。基于文档对的图形表示，我们进一步提出了一个连体编码图卷积网络，通过Siamese神经网络学习顶点表示，并通过图形卷积网络聚合顶点特征以生成匹配结果。基于腾讯公司为其智能新闻产品创建的两个标签新闻文章数据集，对所提出的方法进行了广泛的评估，结果表明，提出的长图像匹配方法显着优于各种最先进的方法。

##### URL
[http://arxiv.org/abs/1802.07459](http://arxiv.org/abs/1802.07459)

##### PDF
[http://arxiv.org/pdf/1802.07459](http://arxiv.org/pdf/1802.07459)

