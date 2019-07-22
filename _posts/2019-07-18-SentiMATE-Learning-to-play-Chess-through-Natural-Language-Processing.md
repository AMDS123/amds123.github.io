---
layout: post
title: "SentiMATE: Learning to play Chess through Natural Language Processing"
date: 2019-07-18 23:48:21
categories: arXiv_AI
tags: arXiv_AI Sentiment Classification Deep_Learning Prediction
author: Isaac Kamlish, Isaac Bentata Chcoron, Nicholas McCarthy
mathjax: true
---

* content
{:toc}

##### Abstract
We present SentiMATE, a novel end-to-end Deep Learning model for Chess, employing Natural Language Processing that aims to learn an effective evaluation function assessing move quality. This function is pre-trained on the sentiment of commentary associated with the training moves and is used to guide and optimize the agent's game-playing decision making. The contributions of this research are three-fold: we build and put forward both a classifier which extracts commentary describing the quality of Chess moves in vast commentary datasets, and a Sentiment Analysis model trained on Chess commentary to accurately predict the quality of said moves, to then use those predictions to evaluate the optimal next move of a Chess agent. Both classifiers achieve over 90 % classification accuracy. Lastly, we present a Chess engine, SentiMATE, which evaluates Chess moves based on a pre-trained sentiment evaluation function. Our results exhibit strong evidence to support our initial hypothesis - "Can Natural Language Processing be used to train a novel and sample efficient evaluation function in Chess Engines?" - as we integrate our evaluation function into modern Chess engines and play against agents with traditional Chess move evaluation functions, beating both random agents and a DeepChess implementation at a level-one search depth - representing the number of moves a traditional Chess agent (employing the alpha-beta search algorithm) looks ahead in order to evaluate a given chess state.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08321](http://arxiv.org/abs/1907.08321)

##### PDF
[http://arxiv.org/pdf/1907.08321](http://arxiv.org/pdf/1907.08321)

