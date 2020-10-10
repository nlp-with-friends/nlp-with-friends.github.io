---
permalink: /speakers/john-hewitt
title: "Language Probes as V-information Estimators"
speaker: John Hewitt
author: John Hewitt
date: Sept 9, 2020
time: 14:00 UTC
timeconverter: "https://www.timeanddate.com/worldclock/converter.html?iso=20200902T140000&p1=1440&p2=224&p3=179&p4=136&p5=676&p6=33&p7=152"
bio: "John is a 3rd year PhD student in computer science at Stanford University, advised by Chris Manning and Percy Liang. He works on understanding and improving how neural networks learn and process human languages."
read_time: true
author_profile: true
layout: single
---

<a href="https://lolmythesis.com/" class="one-line">A clarifying way to think about (and improve) probing neural networks for linguistic properties</a>

To grapple with the question of what deep contextual models learn about language, probing experiments train classifiers to predict linguistic properties from neural representations. Probing has provided insight into the layers of deep models, but substantial debate has arisen around how probing experiments should be designed and interpreted. In this talk on ongoing work, I'll present a framework casting probing as estimating the V-information between representations and linguistic properties. Conceptually, V-information probes measure how much usable information about a property is contained in a representation. Our framework provides clarity into the roles of the decisions made when designing probes, like the model family chosen for the probing classifier.

Under this framework, I'll present conditional probes, a general method for controlling for unwanted effects in probing, enabling us to ask questions like “what has this representation encoded about a linguistic property other than what’s explainable by a baseline representation?” I'll then show why this can matter: for example, in English probing experiments, I'll use conditional probes to study what RoBERTa encodes about part-of-speech other than what’s explainable by non-contextual embeddings, finding that this information propagates much deeper into the model than earlier probing results suggest.

<hr>

**John** is a 3rd year PhD student in computer science at Stanford University, advised by Chris Manning and Percy Liang. He works on understanding and improving how neural networks learn and process human languages.