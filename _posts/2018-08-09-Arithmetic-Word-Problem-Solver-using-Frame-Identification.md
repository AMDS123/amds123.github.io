---
layout: post
title: "Arithmetic Word Problem Solver using Frame Identification"
date: 2018-08-09 05:57:13
categories: arXiv_CL
tags: arXiv_CL
author: Pruthwik Mishra, Litton J Kurisinkel, Dipti Misra Sharma
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic Word problem solving has always posed a great challenge for the NLP community. Usually a word problem is a narrative comprising of a few sentences and a question is asked about a quantity referred in the sentences. Solving word problem involves reasoning across sentences, identification of operations, their order, relevant quantities and discarding irrelevant quantities. In this paper, we present a novel approach for automatic arithmetic word problem solving. Our approach starts with frame identification. Each frame can either be classified as a state or an action frame. The frame identification is dependent on the verb in a sentence. Every frame is unique and is identified by its slots. The slots are filled using dependency parsed output of a sentence. The slots are entity holder, entity, quantity of the entity, recipient, additional information like place, time. The slots and frames helps to identify the type of question asked and the entity referred. Action frames act on state frame(s) which causes a change in quantities of the state frames. The frames are then used to build a graph where any change in quantities can be propagated to the neighboring nodes. Most of the current solvers can only answer questions related to the quantity, while our system can answer different kinds of questions like `who', `what' other than the quantity related questions `how many'. 
 There are three major contributions of this paper. 1. Frame Annotated Corpus (with a frame annotation tool) 2. Frame Identification Module 3. A new easily understandable Framework for word problem solving

##### Abstract (translated by Google)
自动解决Word问题一直是NLP社区面临的巨大挑战。通常，单词问题是包含几个句子的叙述，并且询问关于句子中引用的数量的问题。解决单词问题涉及跨句子推理，操作识别，顺序，相关数量和丢弃无关数量。在本文中，我们提出了一种新的自动算术词问题解决方法。我们的方法从帧识别开始。每个帧可以被分类为状态或动作帧。帧识别取决于句子中的动词。每个帧都是唯一的，并由其插槽标识。使用句子的依赖性解析输出填充槽。插槽是实体持有者，实体，实体数量，接收者，地点，时间等附加信息。插槽和框架有助于识别所询问的问题类型和所引用的实体。动作帧作用于状态帧，这导致状态帧的数量的改变。然后使用这些帧来构建图形，其中量的任何变化都可以传播到相邻节点。大多数当前的解算器只能回答与数量相关的问题，而我们的系统可以回答不同类型的问题，比如“谁”，“什么”以及数量相关问题“多少”。
 本文有三个主要贡献。 1.框架注释语料库（带框架注释工具）2。框架识别模块3.一个易于理解的新框架，用于解决单词问题

##### URL
[http://arxiv.org/abs/1808.03028](http://arxiv.org/abs/1808.03028)

##### PDF
[http://arxiv.org/pdf/1808.03028](http://arxiv.org/pdf/1808.03028)

