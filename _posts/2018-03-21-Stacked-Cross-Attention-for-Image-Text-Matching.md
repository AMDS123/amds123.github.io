---
layout: post
title: "Stacked Cross Attention for Image-Text Matching"
date: 2018-03-21 17:22:27
categories: arXiv_AI
tags: arXiv_AI Image_Retrieval Salient Attention
author: Kuang-Huei Lee, Xi Chen, Gang Hua, Houdong Hu, Xiaodong He
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the problem of image-text matching. Inferring the latent semantic alignment between objects or other salient stuffs (e.g. snow, sky, lawn) and the corresponding words in sentences allows to capture fine-grained interplay between vision and language, and makes image-text matching more interpretable. Prior works either simply aggregate the similarity of all possible pairs of regions and words without attending differentially to more and less important words or regions, or use a multi-step attentional process to capture limited number of semantic alignments which is less interpretable. In this paper, we present Stacked Cross Attention to discover the full latent alignments using both image regions and words in sentence as context and infer the image-text similarity. Our approach achieves the state-of-the-art results on the MS-COCO and Flickr30K datasets. On Flickr30K, our approach outperforms the current best methods by 22.1% in text retrieval from image query, and 18.2% in image retrieval with text query (based on Recall@1). On MS-COCO, our approach improves sentence retrieval by 17.8% and image retrieval by 16.6% (based on Recall@1 using the 5K test set).

##### Abstract (translated by Google)
在本文中，我们研究图像文本匹配问题。推断对象之间或其他显着内容（如雪，天空，草坪）和句子中相应词语之间的潜在语义对齐可以捕捉视觉和语言之间的细微相互作用，并使图像文本匹配更加可解释。以前的作品要么简单地聚合所有可能的区域和单词对的相似性，不要差别地考虑更多或更少的重要单词或区域，要么使用多步骤注意过程来捕获有限数量的不易解释的语义对齐。在本文中，我们提出Stacked Cross Attention来发现使用句子中的图像区域和词语作为上下文的完全潜在对齐，并推断图像文本的相似性。我们的方法在MS-COCO和Flickr30K数据集上实现了最先进的结果。在Flickr30K中，我们的方法比图像查询中的文本检索中的当前最佳方法提高22.1％，并且具有文本查询（基于Recall @ 1）的图像检索中的方法优于18.2％。在MS-COCO中，我们的方法将句子检索提高了17.8％，图像检索提高了16.6％（基于使用5K测试集的Recall @ 1）。

##### URL
[http://arxiv.org/abs/1803.08024](http://arxiv.org/abs/1803.08024)

##### PDF
[http://arxiv.org/pdf/1803.08024](http://arxiv.org/pdf/1803.08024)

