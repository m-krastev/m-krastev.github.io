---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* MSc in Artificial Intelligence, University of Amsterdam, 2023 - 2025
  * Relevant Subjects: Machine Learning and Deep Learning · NLP · Computer Vision · Graph Neural Networks · Recommender Systems · Foundation Models · Reinforcement Learning

* BSc in Computer Science, University of Aberdeen, 2019 - 2023 (1st Class, GPA: 3.8/4.0)
  * Relevant Subjects: Artificial Intelligence · Machine Learning · Security · Distributed Systems · Operating Systems · Modern Programming Languages

Work experience
======

* Teaching Assistant, University of Amsterdam, Sep 2024 - Jun 2025
  * Prepared assignments and led practical sessions for the following courses: Computer Vision, Deep Learning, Information Retrieval, and Recommender Systems.

* Teaching Assistant, University of Aberdeen, Jan 2022 - Jun 2023
  * Collaborated with teachers to organize and lead practical sessions for several informatics-oriented courses, including web development, operating systems, distributed systems, and discrete mathematics.

* Software Engineer Intern, Together for Success, Jun 2022 - Sep 2022
  * Focus on developing a SaaS platform for building e-commerce websites, specific tasks included testing, standardization, and quality assurance. Provided extensive system documentation and requirements specification, and developed the API backend reference website.

Projects
======

* [InPars-Plus: Supercharging Synthetic Data Generation for IR](https://github.com/danilotpnta/IR2-project) (keywords: IR, synthetic data, LLMs)
  * Co-authored a method improving upon the InPars framework. We augment generation using CoT and preference fine-tuning to improve downstream performance in diverse information retrieval tasks.

* [Towards Multimodal Medical Image Segmentation with Context-Prior Learning](https://github.com/SergheiMihailov/adapt_med_seg) (keywords: SAM, MedAI, Segmentation)
  * Co-authored a project to evaluate the transferability of SegVol, a 3D SAM-based segmentation foundation model, across different medical imaging modalities (CT and MRI). We extended SegVol's capabilities through LoRA fine-tuning and context-priors (Gao et al., 2023), improving segmentation scores with both approaches.

* [DynaLora: Dynamic Low-Rank Module Allocation](https://github.com/m-krastev/dynalora) (keywords: LoRA, PEFT)
  * Co-authored a method for fine-tuning foundation models which dynamically allocates trainable parameters and is orthogonal to other methods, reducing the required maximum GPU memory during training.

Skills
======

* Programming Languages: Python, Rust, C/C++, JavaScript
* Libraries and Technologies: PyTorch, NumPy, JAX, Docker, Google Cloud, Azure
  
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
