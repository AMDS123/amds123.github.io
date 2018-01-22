---
layout: post
title: "A Resource-Light Method for Cross-Lingual Semantic Textual Similarity"
date: 2018-01-19 15:00:33
categories: arXiv_CL
tags: arXiv_CL Embedding Detection Recognition
author: Goran Glava&#x161;, Marc Franco-Salvador, Simone Paolo Ponzetto, Paolo Rosso
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing semantically similar sentences or paragraphs across languages is beneficial for many tasks, ranging from cross-lingual information retrieval and plagiarism detection to machine translation. Recently proposed methods for predicting cross-lingual semantic similarity of short texts, however, make use of tools and resources (e.g., machine translation systems, syntactic parsers or named entity recognition) that for many languages (or language pairs) do not exist. In contrast, we propose an unsupervised and a very resource-light approach for measuring semantic similarity between texts in different languages. To operate in the bilingual (or multilingual) space, we project continuous word vectors (i.e., word embeddings) from one language to the vector space of the other language via the linear translation model. We then align words according to the similarity of their vectors in the bilingual embedding space and investigate different unsupervised measures of semantic similarity exploiting bilingual embeddings and word alignments. Requiring only a limited-size set of word translation pairs between the languages, the proposed approach is applicable to virtually any pair of languages for which there exists a sufficiently large corpus, required to learn monolingual word embeddings. Experimental results on three different datasets for measuring semantic textual similarity show that our simple resource-light approach reaches performance close to that of supervised and resource intensive methods, displaying stability across different language pairs. Furthermore, we evaluate the proposed method on two extrinsic tasks, namely extraction of parallel sentences from comparable corpora and cross lingual plagiarism detection, and show that it yields performance comparable to those of complex resource-intensive state-of-the-art models for the respective tasks.

##### Abstract (translated by Google)
认识跨语言的语义上相似的句子或段落对于许多任务是有益的，从跨语言信息检索和抄袭检测到机器翻译。然而，最近提出的用于预测短文本的跨语言语义相似性的方法利用了对于许多语言（或语言对）不存在的工具和资源（例如，机器翻译系统，句法分析器或命名实体识别）。相比之下，我们提出了一种无监督和非常资源的方法来衡量不同语言的文本之间的语义相似度。为了在双语（或多语言）空间中操作，我们通过线性翻译模型将连续的单词向量（即单词嵌入）从一种语言投射到另一种语言的向量空间。然后，根据双向嵌入空间中的向量的相似性对单词进行对齐，并利用双语嵌入和单词对齐来研究不同的无监督的语义相似性度量。只要在语言之间只需要有限大小的单词翻译对，所提出的方法几乎适用于存在足够大的语料库的所有语言对，这是学习单语语言嵌入所必需的。在三个不同的数据集上测量语义文本相似度的实验结果表明，我们简单的资源轻量级方法的性能接近监督和资源密集型方法，显示了不同语言对之间的稳定性。此外，我们评估提出的方法在两个外在的任务，即提取平行句子从可比较的语料库和跨语言抄袭检测，表明它的性能可比得上那些复杂的资源密集型的最先进的模型各自的任务。

##### URL
[http://arxiv.org/abs/1801.06436](http://arxiv.org/abs/1801.06436)

##### PDF
[http://arxiv.org/pdf/1801.06436](http://arxiv.org/pdf/1801.06436)

