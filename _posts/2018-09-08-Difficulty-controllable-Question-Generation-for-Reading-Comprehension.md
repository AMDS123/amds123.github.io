---
layout: post
title: "Difficulty-controllable Question Generation for Reading Comprehension"
date: 2018-09-08 07:01:52
categories: arXiv_AI
tags: arXiv_AI
author: Yifan Gao, Lidong Bing, Wang Chen, Jianan Wang, Irwin King, Michael R. Lyu
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the difficulty levels of questions, and propose a new setting called Difficulty-controllable Question Generation (DQG). Taking as input a reading comprehension paragraph and some text fragments (i.e. answers) in the paragraph that we want to ask questions about, a DQG method needs to generate questions each of which has a given text fragment as its answer, and meanwhile the generation is under the control of specified difficulty labels---the output questions should satisfy the specified difficulty as much as possible. To solve this task, we propose an end-to-end framework to generate questions of designated difficulty levels. Specifically, we explore a few intuitions: (i) In the input sentences, the nearer a word is to the answer fragment, the more likely it is used in the question; (ii) The easier a question is, the nearer its words are to the answer fragment in the sentence; (iii) Performing difficulty control could be regarded as a problem of sentence generation towards a specified attribute or style, namely difficulty level. For evaluation, we prepared the first dataset of reading comprehension questions with difficulty labels. The results show that our framework not only generates questions of better quality under the metrics like BLEU, but also has the capability to generate questions complying with the specified difficulty labels.

##### Abstract (translated by Google)
我们调查问题的难度级别，并提出一个称为难度可控制问题生成（DQG）的新设置。在我们想要提问的段落中将读取理解段落和一些文本片段（即答案）作为输入，DQG方法需要生成问题，每个问题都有给定的文本片段作为答案，同时生成是在指定难度标签的控制下---输出问题应尽可能满足规定的难度。为了解决这个任务，我们提出了一个端到端的框架来生成指定难度级别的问题。具体来说，我们探索了一些直觉：（i）在输入句子中，一个单词越接近答案片段，就越有可能在问题中使用它; （ii）问题越容易，其句子越接近句子中的答案片段; （iii）执行难度控制可被视为针对特定属性或风格的句子生成问题，即难度级别。为了评估，我们准备了第一个具有难度标签的阅读理解问题数据集。结果表明，我们的框架不仅可以在BLEU等指标下生成质量更高的问题，而且还能够生成符合指定难度标签的问题。

##### URL
[http://arxiv.org/abs/1807.03586](http://arxiv.org/abs/1807.03586)

##### PDF
[http://arxiv.org/pdf/1807.03586](http://arxiv.org/pdf/1807.03586)

