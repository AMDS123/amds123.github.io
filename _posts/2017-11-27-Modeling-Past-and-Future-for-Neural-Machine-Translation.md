---
layout: post
title: "Modeling Past and Future for Neural Machine Translation"
date: 2017-11-27 01:42:00
categories: arXiv_CL
tags: arXiv_CL NMT
author: Zaixiang Zheng, Hao Zhou, Shujian Huang, Lili Mou, Xinyu Dai, Jiajun Chen, Zhaopeng Tu
---

* content
{:toc}

##### Abstract
Existing neural machine translation systems do not explicitly model what has been translated and what has not during the decoding phase. To address this problem, we propose a novel mechanism that separates the source information into two parts: translated Past contents and untranslated Future contents, which are modeled by two additional recurrent layers. The Past and Future contents are fed to both the attention model and the decoder states, which offers NMT systems the knowledge of translated and untranslated contents. Experimental results show that the proposed approach significantly improves translation performance in Chinese-English, German-English and English-German translation tasks. Specifically, the proposed model outperforms the conventional coverage model in both of the translation quality and the alignment error rate.

##### Abstract (translated by Google)
现有的神经机器翻译系统没有明确地对在翻译阶段已翻译和未翻译的内容进行建模。为了解决这个问题，我们提出了一种新的机制，将源信息分为两部分：翻译过去的内容和未翻译的未来内容，这些内容由两个附加的复发层建模。 “过去”和“将来”的内容被提供给注意模型和解码器状态，这为NMT系统提供翻译和未翻译内容的知识。实验结果表明，该方法显着提高了汉英，德语和英语 - 德语翻译任务的翻译效果。具体来说，所提出的模型在翻译质量和比对错误率方面都优于传统的覆盖模型。

##### URL
[https://arxiv.org/abs/1711.09502](https://arxiv.org/abs/1711.09502)

