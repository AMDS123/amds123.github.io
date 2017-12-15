---
layout: post
title: "Learning to Distill: The Essence Vector Modeling Framework"
date: 2016-11-22 09:11:42
categories: arXiv_CL
tags: arXiv_CL Sentiment Sentiment_Classification Summarization Speech_Recognition Embedding Represenation_Learning Classification Recognition
author: Kuan-Yu Chen, Shih-Hung Liu, Berlin Chen, Hsin-Min Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In the context of natural language processing, representation learning has emerged as a newly active research subject because of its excellent performance in many applications. Learning representations of words is a pioneering study in this school of research. However, paragraph (or sentence and document) embedding learning is more suitable/reasonable for some tasks, such as sentiment classification and document summarization. Nevertheless, as far as we are aware, there is relatively less work focusing on the development of unsupervised paragraph embedding methods. Classic paragraph embedding methods infer the representation of a given paragraph by considering all of the words occurring in the paragraph. Consequently, those stop or function words that occur frequently may mislead the embedding learning process to produce a misty paragraph representation. Motivated by these observations, our major contributions in this paper are twofold. First, we propose a novel unsupervised paragraph embedding method, named the essence vector (EV) model, which aims at not only distilling the most representative information from a paragraph but also excluding the general background information to produce a more informative low-dimensional vector representation for the paragraph. Second, in view of the increasing importance of spoken content processing, an extension of the EV model, named the denoising essence vector (D-EV) model, is proposed. The D-EV model not only inherits the advantages of the EV model but also can infer a more robust representation for a given spoken paragraph against imperfect speech recognition.

##### Abstract (translated by Google)
在自然语言处理的背景下，表征学习作为一个新兴的研究课题，由于其在许多应用中的卓越表现而出现。学习词汇表达是这一研究领域的开拓性研究。然而，段落（或句子和文档）嵌入式学习对于某些任务（如情感分类和文档摘要）更为合适/合理。尽管如此，就我们所知，关于无监督段落嵌入方法的开发工作相对较少。经典段落嵌入方法通过考虑段落中出现的所有单词来推断给定段落的表示。因此，频繁出现的那些停止词或功能词可能会误导嵌入学习过程以产生模糊的段落表示。受到这些观察的启发，我们在本文中的主要贡献是双重的。首先，我们提出了一种新的无监督段落嵌入方法，称为实质向量（EV）模型，其目的不仅在于从段落中提取最具代表性的信息，而且还排除一般背景信息以产生更多信息的低维向量表示为该段。其次，鉴于口头内容处理的重要性日益提高，提出了EV模型的扩展，即降噪实质矢量（D-EV）模型。 D-EV模型不仅继承了EV模型的优点，而且还可以针对给定的口头段落推断出针对不完全语音识别的更强健的表示。

##### URL
[https://arxiv.org/abs/1611.07206](https://arxiv.org/abs/1611.07206)

##### PDF
[https://arxiv.org/pdf/1611.07206](https://arxiv.org/pdf/1611.07206)

