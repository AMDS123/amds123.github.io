---
layout: post
title: "Learning Multilingual Word Embeddings in a Latent Metric Space: A Geometric Approach"
date: 2018-08-27 10:37:16
categories: arXiv_AI
tags: arXiv_AI Embedding Optimization
author: Pratik Jawanpuria, Arjun Balgovind, Anoop Kunchukuttan, Bamdev Mishra
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel geometric approach for learning bilingual mappings given monolingual embeddings and a bilingual dictionary. Our approach decouples learning the transformation from the source language to the target language into (a) learning rotations for language-specific embeddings to align them to a common space, and (b) learning a similarity metric in the common space to model similarities between the embeddings. We model the bilingual mapping problem as an optimization problem on smooth Riemannian manifolds. We show that our approach outperforms previous approaches on the bilingual lexicon induction and cross-lingual word similarity tasks. Since we represent the rotated embeddings in a common latent space, our approach can easily represent multiple languages in a common space. We also show that these multilingual embeddings can be learned jointly given bilingual dictionaries for multiple language pairs. We demonstrate the effectiveness of the multilingual embeddings in one zero-shot word translation setting: word translation using these multilingual embeddings is better than word translation using a pivot language when no source-target bilingual dictionary is available, but source-pivot and pivot-target bilingual dictionaries are available.

##### Abstract (translated by Google)
我们提出了一种新颖的几何学方法，用于学习单语嵌入和双语词典的双语映射。我们的方法将学习从源语言到目标语言的转换分解为（a）学习语言特定嵌入的旋转以使它们与公共空间对齐，以及（b）在公共空间中学习相似性度量以模拟相似性。的嵌入。我们将双语映射问题建模为平滑黎曼流形上的优化问题。我们表明，我们的方法优于以前的双语词汇归纳和跨语言词汇相似性任务的方法。由于我们将旋转嵌入表示在一个共同的潜在空间中，因此我们的方法可以很容易地在一个公共空间中表示多种语言。我们还表明，这些多语言嵌入可以在多语言对的双语词典中共同学习。我们在一个零镜头单词翻译设置中展示了多语言嵌入的有效性：当没有源 - 目标双语词典可用时，使用这些多语言嵌入的单词翻译比使用枢轴语言的单词翻译更好，但是源 - 枢轴和枢轴 - 目标提供双语词典。

##### URL
[http://arxiv.org/abs/1808.08773](http://arxiv.org/abs/1808.08773)

##### PDF
[http://arxiv.org/pdf/1808.08773](http://arxiv.org/pdf/1808.08773)

