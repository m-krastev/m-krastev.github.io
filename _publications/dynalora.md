---
title: "DynaLoRA: Dynamic Low-Rank Module Allocation"
authors: Jesse Brouwers, Zsombor Fulop, Miklos Hamar, <b>Matey Krastev</b>
collection: publications
category: blogs
permalink: /publication/dynalora
excerpt: 'In this project we explored the training dynamics of Parameter-Efficient Fine-Tuning (PEFT) methods, with an emphasis on Low-Rank Adaptation (LoRA). Mainly, we wanted to evaluate, whether it is possible to further reduce memory overhead of fine-tuning by selectively deactivating gradient updates for certain modules during training. In our method, we measured either activation magnitude of the adapted layers in the forward pass, or the gradient magnitude of the same vector in the backward pass.'
date: 2024-06-10
venue: 'GitHub'
thumbnail: /images/publications/dynalora.png
paperurl: /files/publications/dynalora-paper.pdf
poster: /files/publications/dynalora-poster.pdf
citation: 'Brouwers, J., Fulop, Z., Hamar, M., & Krastev, M. (2024). DynaLoRA: Dynamic Low-Rank Module Allocation.'
code: https://github.com/m-krastev/dynalora
featured: true
---

# Abstract

In this project we explored the training dynamics of Parameter-Efficient Fine-Tuning (PEFT) methods, with an emphasis on Low-Rank Adaptation (LoRA). Mainly, we wanted to evaluate, whether it is possible to further reduce memory overhead of fine-tuning by selectively deactivating gradient updates for certain modules during training. In our method, we measured either activation magnitude of the adapted layers in the forward pass, or the gradient magnitude of the same vector in the backward pass.
