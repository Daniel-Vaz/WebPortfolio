---
layout: splash
title: "Portfólio"
permalink: /projetos/
header:
  overlay_filter: "0.1"
  overlay_image: /assets/background_proj.jpg
excerpt: "Cada Projeto uma lição. "
intro:
  - excerpt: "Cada um destes posts é sinônimo da documentação, do planeamento, investigação e materialização de todos os projetos públicos que já desenvolvi. Aconselha-se ao leitor a explorar os mesmos, sendo que estes procuram elucidar qualquer um que esteja interessado nos seus temas."

feature_row1:
  - image_path: "https://media.giphy.com/media/55cTEgOSm6A2sVj41L/source.gif"
    alt: "placeholder image 1"
    title: "Web-Portfólio"
    excerpt: "Site Estático construido em Jekyll e Servido através das GitHub Pages."
    url: "/projetos/webportfolio"
    btn_label: "Ler Mais"
    btn_class: "btn--inverse"

feature_row2:
  - image_path: "https://media.giphy.com/media/8PvAjFc4OVR79lQBoJ/giphy.gif"
    alt: "placeholder image 2"
    title: "NotasCrawler"
    excerpt: 'Script *Open-Source* escrito em *Python3*, para WebCrawling.'
    url: "/projetos/notascrawler"
    btn_label: "Ler Mais"
    btn_class: "btn--inverse"

feature_row3:
  - image_path: "https://media.giphy.com/media/1xP5O0uVR6J2okihOY/source.gif"
    alt: "placeholder image 3"
    title: "RHCSA7- Preparação"
    excerpt: 'Documentação técnica dos tópicos a serem encarados em exame.'
    url: "/projetos/rhcsa"
    btn_label: "Ler Mais"
    btn_class: "btn--inverse"

---

<br/>
---
{% include feature_row id="intro" type="center" %}
<br/>

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row2" type="left" %}
