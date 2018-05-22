---
layout: post
title: "Efficient and Robust Question Answering from Minimal Context over Documents"
date: 2018-05-21 14:48:08
categories: arXiv_CL
tags: arXiv_CL Adversarial QA Inference
author: Sewon Min, Victor Zhong, Richard Socher, Caiming Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Neural models for question answering (QA) over documents have achieved significant performance improvements. Although effective, these models do not scale to large corpora due to their complex modeling of interactions between the document and the question. Moreover, recent work has shown that such models are sensitive to adversarial inputs. In this paper, we study the minimal context required to answer the question, and find that most questions in existing datasets can be answered with a small set of sentences. Inspired by this observation, we propose a simple sentence selector to select the minimal set of sentences to feed into the QA model. Our overall system achieves significant reductions in training (up to 15 times) and inference times (up to 13 times), with accuracy comparable to or better than the state-of-the-art on SQuAD, NewsQA, TriviaQA and SQuAD-Open. Furthermore, our experimental results and analyses show that our approach is more robust to adversarial inputs.

##### Abstract (translated by Google)
针对文档的问答（QA）的神经模型已经实现了显着的性能改进。由于这些模型对文档和问题之间的交互作用进行了复杂的建模，因此这些模型虽然有效，却无法扩展到大型语料库。此外，最近的工作表明，这种模式对敌对投入很敏感。在本文中，我们研究回答问题所需的最小上下文，并发现现有数据集中的大多数问题都可以用一小组句子来回答。受这一观察的启发，我们提出了一个简单的句子选择器来选择最小的一组句子以供给QA模型。我们的整个系统在训练（最多15次）和推理时间（最多13次）方面显着减少，准确度可与SQUAD，NewsQA，TriviaQA和SQuAD-Open的最新技术相媲美或更好。此外，我们的实验结果和分析表明，我们的方法对敌对投入更为强大。

##### URL
[https://arxiv.org/abs/1805.08092](https://arxiv.org/abs/1805.08092)

##### PDF
[https://arxiv.org/pdf/1805.08092](https://arxiv.org/pdf/1805.08092)

