---
layout: post
title: "Are You Talking to a Machine? Dataset and Methods for Multilingual Image Question Answering"
date: 2015-11-02 21:12:15
categories: arXiv_CL
tags: arXiv_CL QA CNN RNN
author: Haoyuan Gao, Junhua Mao, Jie Zhou, Zhiheng Huang, Lei Wang, Wei Xu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present the mQA model, which is able to answer questions about the content of an image. The answer can be a sentence, a phrase or a single word. Our model contains four components: a Long Short-Term Memory (LSTM) to extract the question representation, a Convolutional Neural Network (CNN) to extract the visual representation, an LSTM for storing the linguistic context in an answer, and a fusing component to combine the information from the first three components and generate the answer. We construct a Freestyle Multilingual Image Question Answering (FM-IQA) dataset to train and evaluate our mQA model. It contains over 150,000 images and 310,000 freestyle Chinese question-answer pairs and their English translations. The quality of the generated answers of our mQA model on this dataset is evaluated by human judges through a Turing Test. Specifically, we mix the answers provided by humans and our model. The human judges need to distinguish our model from the human. They will also provide a score (i.e. 0, 1, 2, the larger the better) indicating the quality of the answer. We propose strategies to monitor the quality of this evaluation process. The experiments show that in 64.7% of cases, the human judges cannot distinguish our model from humans. The average score is 1.454 (1.918 for human). The details of this work, including the FM-IQA dataset, can be found on the project page: this http URL

##### Abstract (translated by Google)
在本文中，我们提出了mQA模型，它能够回答关于图像内容的问题。答案可以是一个句子，一个短语或一个单词。我们的模型包含四个部分：提取问题表示的长期短期记忆（LSTM），提取视觉表示的卷积神经网络（CNN），用于将语言上下文存储在答案中的LSTM以及用于结合前三个部分的信息并生成答案。我们构建了Freestyle Multilingual Image Question Answering（FM-IQA）数据集来训练和评估我们的mQA模型。它包含超过15万的图片和31万个自由式中文问答对和他们的英文翻译。我们的mQA模型在这个数据集上生成的答案的质量由人类法官通过图灵测试进行评估。具体而言，我们混合人类和我们的模型提供的答案。人类法官需要将我们的模型与人类区分开来。他们也会提供一个分数（即0,1,2，越大越好），表明答案的质量。我们提出了监测评估过程质量的策略。实验表明，在64.7％的案件中，法官不能将我们的模型与人类区分开来。平均分是1.454（人为1.918）。这项工作的细节，包括FM-IQA数据集，可以在项目页面找到：这个http URL

##### URL
[https://arxiv.org/abs/1505.05612](https://arxiv.org/abs/1505.05612)

##### PDF
[https://arxiv.org/pdf/1505.05612](https://arxiv.org/pdf/1505.05612)

