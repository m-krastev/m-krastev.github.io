---
title: "Towards Enhancing Multi-task Learning for News Recommendation"
authors: Stefan Vasilev, <b>Matey Krastev</b>, Danilo Toapanta
collection: publications
category: blogs
permalink: /publication/recsys
excerpt: 'We reproduce and adapt MTRec, a news recommendation method
using pre-trained BERT, for the 2024th edition of the RecSys challenge. MTRec extracts a user representation
vector from clicked user articles and scores candidate articles for recommendation by calculating a dot product
with each candidate article’s representation. The authors posit auxiliary tasks to aid learning and propose
the use of gradient surgery to combine the main task and the auxiliary gradients to the respective losses. In
this research, we explore a different auxiliary task, i.e sentiment classification to aid the learning of our task.
We further propose to use LoRA instead of full fine-tuning, which we later show to have a regularizing
effect and to yield a slightly better performing model than the original authors’ model. Our ablations verify
the validity and importance of the included methodological choices.'
date: 2024-06-30
venue: 'GitHub'
thumbnail: /images/publications/recsys.png
# blog: https://github.com/danilotpnta/SegEVOLution/blob/main/blogpost.md
citation: 'Vasilev, S., Krastev, M., & Toapanta, D. (2024). Towards Enhancing Multi-task Learning for News Recommendation.'
code: https://github.com/danilotpnta/MTRec-RecSys
paperurl: /files/publications/recsys-paper.pdf
poster: /files/publications/recsys-poster.pdf
featured: true
---

# Abstract

We reproduce and adapt MTRec, a news recommendation method using pre-trained BERT, for the 2024th edition of the RecSys challenge. MTRec extracts a user representation
vector from clicked user articles and scores candidate articles for recommendation by calculating a dot product
with each candidate article’s representation. The authors posit auxiliary tasks to aid learning and propose
the use of gradient surgery to combine the main task and the auxiliary gradients to the respective losses. In
this research, we explore a different auxiliary task, i.e sentiment classification to aid the learning of our task.
We further propose to use LoRA instead of full fine-tuning, which we later show to have a regularizing
effect and to yield a slightly better performing model than the original authors’ model. Our ablations verify
the validity and importance of the included methodological choices.
