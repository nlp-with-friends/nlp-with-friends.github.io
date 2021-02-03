---
permalink: /speakers/clara-meister
title: "If Beam Search is the Answer, what was the Question?"
speaker: Clara Meister
author: Clara Meister
date: Feb 03, 2021
time: 14:00 UTC
timeconverter: "https://www.timeanddate.com/worldclock/converter.html?iso=20210203T140000&p1=1440&p2=224&p3=179&p4=136&p5=676&p6=33&p7=152"
read_time: true
layout: single
author_profile: true
---

<a href="https://lolmythesis.com/" class="one-line">Exact search: "Are we there yet?"<br>Beam search: "Let's take the scenic route!"</a>

Quite surprisingly, exact maximum a posteriori (MAP) decoding of neural language generators frequently leads to low-quality results. Rather, most state-of-the-art results on language generation tasks are attained using beam search despite its overwhelmingly high search error rate. This implies that the MAP objective alone does not express the properties we desire in text, which merits the question: if beam search is the answer, what was the question? We frame beam search as the exact solution to a different decoding objective in order to gain insights into why high probability under a model alone may not indicate adequacy. We find that beam search enforces uniform information density in text, a property motivated by cognitive science. We suggest a set of decoding objectives that explicitly enforce this property and find that exact decoding with these objectives alleviates the problems encountered when decoding poorly calibrated language generation models. Additionally, we analyze the text produced using various decoding strategies and see that, in our neural machine translation experiments, the extent to which this property is adhered to strongly correlates with BLEU.

<hr>

**Clara** is a PhD student at ETH Zurich (originally from the US) working on language generation and statistical methods in NLP. She misses Trader Joe's. 

#### Presentation Materials
<i class="fas fa-fw fa-video"></i> [Talk Video](https://www.youtube.com/watch?v=5cyY2XoH_Jk&list=PL0zsOCvKa2iEqmPV6WGhjuP-tsrUy102C&index=14){:target="_blank"}  
<i class="fas fa-fw fa-newspaper"></i> [Paper](https://www.aclweb.org/anthology/2020.emnlp-main.170/){:target="_blank"}  
