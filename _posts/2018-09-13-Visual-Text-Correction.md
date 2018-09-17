---
layout: post
title: "Visual Text Correction"
date: 2018-09-13 20:09:12
categories: arXiv_CV
tags: arXiv_CV Knowledge Relation
author: Amir Mazaheri, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Videos, images, and sentences are mediums that can express the same semantics. One can imagine a picture by reading a sentence or can describe a scene with some words. However, even small changes in a sentence can cause a significant semantic inconsistency with the corresponding video/image. For example, by changing the verb of a sentence, the meaning may drastically change. There have been many efforts to encode a video/sentence and decode it as a sentence/video. In this research, we study a new scenario in which both the sentence and the video are given, but the sentence is inaccurate. A semantic inconsistency between the sentence and the video or between the words of a sentence can result in an inaccurate description. This paper introduces a new problem, called Visual Text Correction (VTC), i.e., finding and replacing an inaccurate word in the textual description of a video. We propose a deep network that can simultaneously detect an inaccuracy in a sentence, and fix it by replacing the inaccurate word(s). Our method leverages the semantic interdependence of videos and words, as well as the short-term and long-term relations of the words in a sentence. In our formulation, part of a visual feature vector for every single word is dynamically selected through a gating process. Furthermore, to train and evaluate our model, we propose an approach to automatically construct a large dataset for VTC problem. Our experiments and performance analysis demonstrates that the proposed method provides very good results and also highlights the general challenges in solving the VTC problem. To the best of our knowledge, this work is the first of its kind for the Visual Text Correction task.

##### Abstract (translated by Google)
视频，图像和句子是可以表达相同语义的媒介。人们可以通过阅读一个句子来想象一个图片，或者可以用一些单词描述一个场景。然而，即使句子中的微小变化也会导致与相应视频/图像的显着语义不一致。例如，通过改变句子的动词，意义可能会发生巨大变化。已经进行了许多努力来编码视频/句子并将其解码为句子/视频。在这项研究中，我们研究了一个新的场景，其中给出了句子和视频，但句子是不准确的。句子和视频之间或句子的单词之间的语义不一致可能导致不准确的描述。本文介绍了一个新问题，称为视觉文本校正（VTC），即在视频的文本描述中查找和替换不准确的单词。我们提出了一个深层网络，可以同时检测句子中的不准确性，并通过替换不准确的单词来修复它。我们的方法利用了视频和单词的语义相互依赖性，以及句子中单词的短期和长期关系。在我们的公式中，通过门控过程动态选择每个单词的视觉特征向量的一部分。此外，为了训练和评估我们的模型，我们提出了一种自动构建VTC问题的大型数据集的方法。我们的实验和性能分析表明，该方法提供了非常好的结果，并突出了解决VTC问题的一般挑战。据我们所知，这项工作是Visual Text Correction任务的第一次。

##### URL
[http://arxiv.org/abs/1801.01967](http://arxiv.org/abs/1801.01967)

##### PDF
[http://arxiv.org/pdf/1801.01967](http://arxiv.org/pdf/1801.01967)

