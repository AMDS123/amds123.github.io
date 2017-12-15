---
layout: post
title: "Offline bilingual word vectors, orthogonal transformations and the inverted softmax"
date: 2017-02-13 16:31:06
categories: arXiv_SD
tags: arXiv_SD Knowledge Embedding
author: Samuel L. Smith, David H. P. Turban, Steven Hamblin, Nils Y. Hammerla
mathjax: true
---

* content
{:toc}

##### Abstract
Usually bilingual word vectors are trained "online". Mikolov et al. showed they can also be found "offline", whereby two pre-trained embeddings are aligned with a linear transformation, using dictionaries compiled from expert knowledge. In this work, we prove that the linear transformation between two spaces should be orthogonal. This transformation can be obtained using the singular value decomposition. We introduce a novel "inverted softmax" for identifying translation pairs, with which we improve the precision @1 of Mikolov's original mapping from 34% to 43%, when translating a test set composed of both common and rare English words into Italian. Orthogonal transformations are more robust to noise, enabling us to learn the transformation without expert bilingual signal by constructing a "pseudo-dictionary" from the identical character strings which appear in both languages, achieving 40% precision on the same test set. Finally, we extend our method to retrieve the true translations of English sentences from a corpus of 200k Italian sentences with a precision @1 of 68%.

##### Abstract (translated by Google)
通常双语词向量是“在线”训练的。 Mikolov等人显示他们也可以找到“离线”，其中两个预先训练的嵌入与线性转换，使用从专业知识编译的字典对齐。在这项工作中，我们证明了两个空间之间的线性变换应该是正交的。这个变换可以使用奇异值分解来获得。我们引入了一种新颖的“翻译softmax”来识别翻译对，在将由普通和罕见的英语单词组成的测试集翻译成意大利语时，我们将Mikolov原始映射的精确度从34％提高到了43％。正交变换对噪声更加鲁棒，使我们能够通过从两种语言中出现的相同字符串中构建一个“伪字典”，在没有专家双语信号的情况下学习变换，在相同的测试集上达到40％的精度。最后，我们扩展了我们的方法，从一个200k的意大利语句子库中检索英语句子的真实翻译，精确度为68％。

##### URL
[https://arxiv.org/abs/1702.03859](https://arxiv.org/abs/1702.03859)

##### PDF
[https://arxiv.org/pdf/1702.03859](https://arxiv.org/pdf/1702.03859)

