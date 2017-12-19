---
layout: post
title: "Learning Semantic Similarity for Very Short Texts"
date: 2015-12-02 16:31:20
categories: arXiv_CL
tags: arXiv_CL Sparse Face Embedding
author: Cedric De Boom, Steven Van Canneyt, Steven Bohez, Thomas Demeester, Bart Dhoedt
mathjax: true
---

* content
{:toc}

##### Abstract
Levering data on social media, such as Twitter and Facebook, requires information retrieval algorithms to become able to relate very short text fragments to each other. Traditional text similarity methods such as tf-idf cosine-similarity, based on word overlap, mostly fail to produce good results in this case, since word overlap is little or non-existent. Recently, distributed word representations, or word embeddings, have been shown to successfully allow words to match on the semantic level. In order to pair short text fragments - as a concatenation of separate words - an adequate distributed sentence representation is needed, in existing literature often obtained by naively combining the individual word representations. We therefore investigated several text representations as a combination of word embeddings in the context of semantic pair matching. This paper investigates the effectiveness of several such naive techniques, as well as traditional tf-idf similarity, for fragments of different lengths. Our main contribution is a first step towards a hybrid method that combines the strength of dense distributed representations - as opposed to sparse term matching - with the strength of tf-idf based methods to automatically reduce the impact of less informative terms. Our new approach outperforms the existing techniques in a toy experimental set-up, leading to the conclusion that the combination of word embeddings and tf-idf information might lead to a better model for semantic content within very short text fragments.

##### Abstract (translated by Google)
在Twitter和Facebook等社交媒体上使用数据，要求信息检索算法能够将非常短的文本片段相互联系起来。基于词重叠的传统文本相似性方法，例如tf-idf余弦相似性，在这种情况下大多不能产生好的结果，因为词重叠很少或根本不存在。最近，已经显示分布式词表示或词嵌入已经成功地允许词语在语义级别匹配。为了将短文本片段（作为单独的单词的连接）配对，需要在现有文献中通过天真地组合单个词表示来合适的分布式句子表示。因此，我们调查了几个文本表示作为语义对匹配语境中的词嵌入的组合。本文研究了几种这样的朴素技术的有效性，以及传统的tf-idf相似性，针对不同长度的片段。我们的主要贡献是朝向混合方法的第一步，该方法将密集分布式表示的强度（而不是稀疏项匹配）与基于tf-idf的方法的强度相结合，以自动减少信息量较少的术语的影响。我们的新方法胜过了现有的玩具实验设置技术，得出的结论是，词嵌入和tf-idf信息的组合可能导致在非常短的文本片段中更好的语义内容模型。

##### URL
[https://arxiv.org/abs/1512.00765](https://arxiv.org/abs/1512.00765)

##### PDF
[https://arxiv.org/pdf/1512.00765](https://arxiv.org/pdf/1512.00765)

