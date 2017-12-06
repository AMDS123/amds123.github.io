---
layout: post
title: 'Neural Machine Translation by Minimising the Bayes-risk with Respect to Syntactic Translation Lattices'
date: 2017-02-13 14:29:34
categories: arXiv_CL
tags: arXiv_CL NMT
author: Felix Stahlberg, Adrià de Gispert, Eva Hasler, Bill Byrne
---

* content
{:toc}

##### Abstract
We present a novel scheme to combine neural machine translation (NMT) with traditional statistical machine translation (SMT). Our approach borrows ideas from linearised lattice minimum Bayes-risk decoding for SMT. The NMT score is combined with the Bayes-risk of the translation according the SMT lattice. This makes our approach much more flexible than $n$-best list or lattice rescoring as the neural decoder is not restricted to the SMT search space. We show an efficient and simple way to integrate risk estimation into the NMT decoder which is suitable for word-level as well as subword-unit-level NMT. We test our method on English-German and Japanese-English and report significant gains over lattice rescoring on several data sets for both single and ensembled NMT. The MBR decoder produces entirely new hypotheses far beyond simply rescoring the SMT search space or fixing UNKs in the NMT output.

##### Abstract (translated by Google)
我们提出了一种新的方案来结合神经机器翻译（NMT）和传统的统计机器翻译（SMT）。我们的方法借鉴了SMT的线性化最小贝叶斯风险解码思想。将NMT得分与根据SMT晶格的翻译风险相结合。这使得我们的方法比$ n $ -best list或grid rescoring更灵活，因为神经解码器不限于SMT搜索空间。我们展示了一个高效和简单的方法来将风险估计整合到适合于字级和子字级单位NMT的NMT解码器中。我们使用英德和日英两种语言测试了我们的方法，并报告了在单个和整体NMT的几个数据集上进行格重新分配的重大收益。 MBR解码器产生全新的假设，远不止简单地重新设定SMT搜索空间或在NMT输出中固定UNK。

##### URL
[https://arxiv.org/abs/1612.03791](https://arxiv.org/abs/1612.03791)

