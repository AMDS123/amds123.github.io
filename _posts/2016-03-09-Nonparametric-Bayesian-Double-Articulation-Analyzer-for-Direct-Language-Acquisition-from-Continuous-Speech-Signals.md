---
layout: post
title: "Nonparametric Bayesian Double Articulation Analyzer for Direct Language Acquisition from Continuous Speech Signals"
date: 2016-03-09 15:59:07
categories: arXiv_CL
tags: arXiv_CL GAN Speech_Recognition Inference Language_Model Recognition
author: Tadahiro Taniguchi, Ryo Nakashima, Shogo Nagasaka
mathjax: true
---

* content
{:toc}

##### Abstract
Human infants can discover words directly from unsegmented speech signals without any explicitly labeled data. In this paper, we develop a novel machine learning method called nonparametric Bayesian double articulation analyzer (NPB-DAA) that can directly acquire language and acoustic models from observed continuous speech signals. For this purpose, we propose an integrative generative model that combines a language model and an acoustic model into a single generative model called the "hierarchical Dirichlet process hidden language model" (HDP-HLM). The HDP-HLM is obtained by extending the hierarchical Dirichlet process hidden semi-Markov model (HDP-HSMM) proposed by Johnson et al. An inference procedure for the HDP-HLM is derived using the blocked Gibbs sampler originally proposed for the HDP-HSMM. This procedure enables the simultaneous and direct inference of language and acoustic models from continuous speech signals. Based on the HDP-HLM and its inference procedure, we developed a novel double articulation analyzer. By assuming HDP-HLM as a generative model of observed time series data, and by inferring latent variables of the model, the method can analyze latent double articulation structure, i.e., hierarchically organized latent words and phonemes, of the data in an unsupervised manner. The novel unsupervised double articulation analyzer is called NPB-DAA. The NPB-DAA can automatically estimate double articulation structure embedded in speech signals. We also carried out two evaluation experiments using synthetic data and actual human continuous speech signals representing Japanese vowel sequences. In the word acquisition and phoneme categorization tasks, the NPB-DAA outperformed a conventional double articulation analyzer (DAA) and baseline automatic speech recognition system whose acoustic model was trained in a supervised manner.

##### Abstract (translated by Google)
人类婴儿可以直接从未分词的语音信号中发现单词，而不需要任何明确标记的数据。在本文中，我们开发了一种新的机器学习方法，称为非参数贝叶斯双关节分析器（NPB-DAA），可以从观察到的连续语音信号直接获取语言和声学模型。为此，我们提出了一个将语言模型和声学模型结合成一个称为“分层Dirichlet过程隐藏语言模型”（HDP-HLM）的单一生成模型的综合生成模型。通过扩展Johnson等人提出的分层Dirichlet过程隐马尔可夫模型（HDP-HSMM）获得HDP-HLM。使用最初为HDP-HSMM提出的阻塞Gibbs采样器推导出HDP-HLM的推断过程。这个程序能够从连续的语音信号中同时直接推导语言和声学模型。基于HDP-HLM及其推理程序，我们开发了一种新型双关节分析仪。通过假定HDP-HLM作为观察时间序列数据的生成模型，并且通过推断模型的潜在变量，该方法可以以无监督的方式分析数据的潜在双关节结构，即分层组织的潜在词和音素。新型无监督双关节分析仪被称为NPB-DAA。 NPB-DAA可以自动估计嵌入语音信号中的双关节结构。我们还用合成数据和代表日本元音序列的实际人类连续语音信号进行了两次评估实验。在词汇采集和音素分类任务中，NPB-DAA比传统的双关节分析器（DAA）和基线自动语音识别系统更胜一筹，其声学模型是以监督的方式进行训练的。

##### URL
[https://arxiv.org/abs/1506.06646](https://arxiv.org/abs/1506.06646)

##### PDF
[https://arxiv.org/pdf/1506.06646](https://arxiv.org/pdf/1506.06646)

