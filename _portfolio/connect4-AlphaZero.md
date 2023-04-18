---
title: "Connect Four AI (AlphaGo Zero style) "
excerpt: "Connect Four trained under a Reinforcement Learning paradigm, using MCTS + Deep Learning (AlphaGo Zero style), learning via pure self-play without feature engineering or expert input"
header:
  image: /assets/images/connect4/connect4.jpg
  teaser: /assets/images/connect4/connect4.jpg
gallery:
  - url: /assets/images/connect4/Reinforcement_learning_diagram.svg.png
    image_path: assets/images/connect4/Reinforcement_learning_diagram.svg.png
    alt: "Reinforcement Learning"
---

Reinforcement Learning allows the computer to play games against itself to gradually improve its play following reward-based learning algorithms without any major external influences or input.

This technique was made famous when the computer program [AlphaGo Zero](https://en.wikipedia.org/wiki/AlphaGo_Zero), with only 40 days of training via pure self-play, was able to beat the previous version of the AI AlphaGo which had already beaten South Korean Go professionals like Lee Sedol by an impressive score of 4:1. Later versions like [Alpha Zero](https://en.wikipedia.org/wiki/AlphaZero) was able to achieve superhuman capabilities in chess/shogi/go with only 24 hours of training!


{% include gallery caption="Typical Reinforcement Learning scenario" %}

<a href="https://github.com/tonberry22/connect4-AlphaZero" target="_blank">Click here to see the github repository and run it yourself!</a>