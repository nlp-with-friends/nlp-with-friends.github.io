---
permalink: /speakers/hirofumi-inaguma
title: "Toward low-latency and accurate simultaneous interpretations from speech"
speaker: Hirofumi Inaguma
author: Hirofumi Inaguma
date: Dec 09, 2020
time: 14:00 UTC
timeconverter: "https://www.timeanddate.com/worldclock/converter.html?iso=20201209T140000&p1=1440&p2=224&p3=179&p4=136&p5=676&p6=33&p7=152"
read_time: true
layout: single
author_profile: true
---

<a href="https://lolmythesis.com/" class="one-line">Humans perceive speech while listening, but how about machines?</a>

Toward simultaneous interpretations from spontaneous speech, automatic speech recognition (ASR) and speech translation (ST) are crucial techniques.
Recent progress on deep learning enables the rapid development of so-called “end-to-end” ASR systems without sophisticated modularization and provides even better accuracy than traditional hybrid systems.
To generate transcriptions as soon as possible, online streaming decoding has been studied so far.
However, due to its end-to-end optimization, models are more likely to use future acoustic observations as long as the recognition accuracy is maximized, which is problematic for user’s experience and downstream NLP tasks.

In this talk, I’ll introduce novel training frameworks to realize perceived latency reduction and accuracy improvement at the same time in streaming sequence-to-sequence ASR models.
To this end, I’ll propose to leverage alignment information extracted from an external hybrid ASR model.
The method will be further extended to a purely end-to-end framework without external models.
Moreover, I’ll introduce recent efforts toward low-latency and accurate end-to-end speech translation modeling based on non-autoregressive sequence generation.

<hr>

**Hirofumi Inaguma** is a PhD student at Kyoto University, advised by Tatsuya Kawahara. He works on automatic speech recognition (ASR) and speech translation. He is one of the main contributors to ESPnet.

#### Presentation Materials
<i class="fas fa-fw fa-video"></i> [Talk Video](https://www.youtube.com/watch?v=WFTeE_93-wE&list=PL0zsOCvKa2iEqmPV6WGhjuP-tsrUy102C){:target="_blank"}  
<i class="fas fa-fw fa-file-pdf"></i> [Talk Slides](https://hirofumi0810.github.io/materials/slide/20201209_NLP_friends_inaguma.pdf){:target="_blank"}  
