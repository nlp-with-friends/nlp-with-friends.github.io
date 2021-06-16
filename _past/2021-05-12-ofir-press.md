---
permalink: /speakers/ofir-press-may12
title: "Shortformer: Better Language Modeling using Shorter Inputs"
speaker: Ofir Press
author: Ofir Press
date: May 12, 2021
time: 17:00 UTC
timeconverter: "https://www.timeanddate.com/worldclock/converter.html?iso=20210428T170000&p1=1440&p2=224&p3=179&p4=136&p5=676&p6=33&p7=152"
read_time: true
layout: single
author_profile: true
---

<a href="https://lolmythesis.com/" class="one-line">Everyone is trying to improve language models by having them look at more words, we show that we can improve them by giving them less words</a>

While progress in transformer language modeling is being driven by increasing input length, we find both perplexity and efficiency gains through two different methods that decrease input length.
First, we show that initially training a model on short subsequences before moving on to longer ones both reduces overall training time and, surprisingly, substantially improves perplexity.
Second, we show how to improve the efficiency of recurrence methods in transformers, which let models condition on previously processed tokens when generating sequences that exceed the maximal length the transformer can handle at once. Existing methods require computationally expensive relative position embeddings; we introduce a simple alternative of adding absolute position embeddings to queries and keys instead of to word embeddings, which efficiently produces superior results. We show that these recurrent models also benefit from short input lengths.
Combining these techniques speeds training by a factor of 1.65, reduces memory usage, and substantially improves perplexity on WikiText-103, without adding any parameters.

<hr>

**Ofir** is a PhD student at the University of Washington advised by Noah Smith, working on better understanding the basic building blocks of neural NLP, so that we can make them faster, smaller and more accurate.

#### Presentation Materials
<i class="fas fa-fw fa-video"></i> [Talk Video](https://www.youtube.com/watch?v=lsJyvxO_27A&list=PL0zsOCvKa2iEqmPV6WGhjuP-tsrUy102C&index=21){:target="_blank"}
