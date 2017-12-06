---
layout: post
title: 'From Captions to Visual Concepts and Back'
date: 2017-12-06 09:15:36
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Caption Detection
author: Hao Fang, Saurabh Gupta, Forrest Iandola, Rupesh Srivastava, Li Deng, Piotr Dollár, Jianfeng Gao, Xiaodong He, Margaret Mitchell, John C. Platt, C. Lawrence Zitnick, Geoffrey Zweig
---

* content
{:toc}

##### Abstract
This paper presents a novel approach for automatically generating image descriptions: visual detectors, language models, and multimodal similarity models learnt directly from a dataset of image captions. We use multiple instance learning to train visual detectors for words that commonly occur in captions, including many different parts of speech such as nouns, verbs, and adjectives. The word detector outputs serve as conditional inputs to a maximum-entropy language model. The language model learns from a set of over 400,000 image descriptions to capture the statistics of word usage. We capture global semantics by re-ranking caption candidates using sentence-level features and a deep multimodal similarity model. Our system is state-of-the-art on the official Microsoft COCO benchmark, producing a BLEU-4 score of 29.1%. When human judges compare the system captions to ones written by other people on our held-out test set, the system captions have equal or better quality 34% of the time.

##### Abstract (translated by Google)
本文提出了一种自动生成图像描述的新方法：视觉检测器，语言模型和多模态相似度模型直接从图像字幕数据集中学习。我们使用多实例学习来训练通常在字幕中出现的单词的视觉检测器，包括许多不同的词类，如名词，动词和形容词。单词检测器输出用作最大熵语言模型的条件输入。语言模型从一组超过40万个图像描述中学习，以获取单词使用的统计数据。我们通过使用句级特征和深度多模式相似性模型对候选题进行重新排序来捕捉全局语义。我们的系统是官方Microsoft COCO基准测试的最新技术，产生了29.1％的BLEU-4分数。当人们将系统字幕与其他人的字幕相比较时，系统字幕在34％的时间内具有相同或更好的质量。

##### URL
[https://arxiv.org/abs/1411.4952](https://arxiv.org/abs/1411.4952)

