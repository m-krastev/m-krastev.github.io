---
permalink: /
title: "Matey Krastev"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Introduction

I am an independent AI/ML enthusiast looking for opportunities in AI research and development.

I obtained my M.Sci. in Artificial Intelligence at the University of Amsterdam (UvA), where I was advised by [Prof. Martin R. Oswald](https://oswaldm.github.io/) and supervised by [Dr. Yunchao Yin](https://www.linkedin.com/in/yunchao-yin-345974136/) in the field of AI for healthcare. I received my B. Sc. degree in Computer Science at the University of Aberdeen, where I was first introduced to NLP research by [Prof. Arabella Sinclair](https://j-anie.github.io/index.html).

My current research interests are in AI for science, particularly in the areas of healthcare and life sciences. I have a strong background in Deep Learning and its applications in natural language processing, bioinformatics, and physical simulation. Other than that, I also have a keen interest in AI architectures, efficient fine-tuning, reinforcement learning, and knowledge distillation. :rocket:

Furthermore, I have had the pleasure to work as a Teaching Assistant alongside the wonderful teaching teams on the CV, DL, and IR courses at UvA to deliver tutorials and design assignments. Similarly, I assisted for several courses on Automata Theory, Operating Systems, and Distributed Systems at University of Aberdeen.

{% include admonition.html type="warning" title="Hey!" body="I am actively looking for work and research positions in AI. Please reach out if you have any opportunities or collaborations in mind.
" %}

## Projects

Many thanks to my wonderful collaborators!

<div class="pub-list">
  {% assign featured_pubs = site.publications | where: "featured", true %}
  {% for pub in featured_pubs reversed %}
  <div class="pub-item">
    {% if pub.thumbnail %}
    <div class="pub-thumb">
        <a href="{{ pub.thumbnail }}"
            class="lightbox-link"
            data-type="image"
            data-caption="{{ pub.excerpt | escape }}">
            <img src="{{ pub.thumbnail }}" alt="Thumbnail for {{ pub.title }}">
        </a>
    </div>
    {% endif %}
    <div class="pub-details">
      <div class="pub-title">
        {% if pub.paperurl %}
          <a href="{{ pub.paperurl }}" class="lightbox-link" data-type="pdf">{{ pub.title }}</a>
        {% else %}
          {{ pub.title }}
        {% endif %}
      </div>

      <div class="pub-authors">{{ pub.authors }}</div>
      <div class="pub-venue">{{ pub.venue }}</div>

      <div class="pub-links">
        {% if pub.paperurl %}
          <a href="{{ pub.paperurl }}" class="lightbox-link" data-type="pdf">
            <i class="fa-solid fa-file-pdf"></i> [PDF]
          </a>
        {% endif %}   
        {% if pub.blog %}
          <a href="{{ pub.blog }}" target="_blank" rel="noopener">
            <i class="fa-solid fa-blog"></i> [Blog]
          </a>   
        {% endif %}
        {% if pub.code %}
          <a href="{{ pub.code }}" target="_blank" rel="noopener">
            <i class="fa-brands fa-github"></i> [Code]
          </a>   
        {% endif %}
        {% if pub.poster %}
          <a href="{{ pub.poster }}" class="lightbox-link" data-type="pdf">
            <i class="fa-solid fa-print"></i> [Poster]
          </a>   
        {% endif %}
      </div>
    </div>
  </div>
  {% endfor %}
</div>

<div id="lightbox" class="lightbox">
  <div class="lightbox-content">
    <span class="lightbox-close">&times;</span>
    <div class="lightbox-body">
      <iframe id="lightbox-frame" src="" frameborder="0"></iframe>
      <img id="lightbox-image" src="" alt="" />
    </div>
    <div id="lightbox-caption" class="lightbox-caption"></div>
  </div>
</div>
