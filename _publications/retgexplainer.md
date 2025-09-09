---
title: "[RE] Explaining Temporal Graph Models through an Explorer-Navigator Framework"
authors: Miklos Hamar, <b>Matey Krastev</b>, Kristiyan Hristov, David Beglou
collection: publications
category: blogs
permalink: /publication/retgexplainer
excerpt: 'Temporal graphs model complex dynamic relations that change over time, and are being used in a growing number of applications. In recent years, several graph neural networks (GNNs) were proposed, designed specifically for this temporal setting (Xu et al., 2020; Rossi et al., 2020). However, these models are notoriously hard to interpret. For this reason, the original authors (Xia et al., 2023) propose the Temporal GNN Explainer (T-GNNExplainer) – an explorer-navigator framework to efficiently compute sparse explanations of target Temporal GNNs. We reproduce the main findings of the original paper, extend their work by proposing a different type of navigator method, and examine in detail the explanation capabilities and efficiency of the provided framework within various model and hyperparameter settings. We confirm that their explainer outperforms the other baselines across nearly all datasets and metrics. Our findings suggest the navigator helps bias the search process, as well as that T-GNNExplainer can find an exact influential event set. Moreover, we examine the effect of different navigator methods and quantify the runtime-fidelity tradeoff controlled by two hyper-parameters.'
date: 2024-02-05
venue: 'Transactions on Machine Learning 05/2024'
thumbnail: /images/publications/retgexplainer.png
blog: https://openreview.net/forum?id=FI1XvwpchC&noteId=XDazCeQmEX
paperurl: /files/publications/retgexplainer-paper.pdf
citation: 'Hamar, M., Krastev, M., Hristov, K. D., & Beglou, D. (2024). [RE] Explaining Temporal Graph Models through an Explorer-Navigator Framework.'
code: https://github.com/m-krastev/fact8-temporal-graph
featured: true
---

# Abstract

Temporal graphs model complex dynamic relations that change over time, and are being used in a growing number of applications. In recent years, several graph neural networks (GNNs) were proposed, designed specifically for this temporal setting (Xu et al., 2020; Rossi et al., 2020). However, these models are notoriously hard to interpret. For this reason, the original authors (Xia et al., 2023) propose the Temporal GNN Explainer (T-GNNExplainer) – an explorer-navigator framework to efficiently compute sparse explanations of target Temporal GNNs. We reproduce the main findings of the original paper, extend their work by proposing a different type of navigator method, and examine in detail the explanation capabilities and efficiency of the provided framework within various model and hyperparameter settings. We confirm that their explainer outperforms the other baselines across nearly all datasets and metrics. Our findings suggest the navigator helps bias the search process, as well as that T-GNNExplainer can find an exact influential event set. Moreover, we examine the effect of different navigator methods and quantify the runtime-fidelity tradeoff controlled by two hyper-parameters.
