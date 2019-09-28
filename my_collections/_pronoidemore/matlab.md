---
layout: default
title: 'Introduction to MATLAB'
position: Trainer
company: Indra
duration: 12 horas
date: 2017-09-13
header:
  teaser: /assets/images/matlab-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/matlab-logo.jpg
    text: "Trainer"
  - title: level
    text: level_basic
  - title: go_for
    text: 'Management and forecast demands department.'
accordion:
    - item:
        name: Introduction
        haschildren: true
    - item:
        name: Math operators
        haschildren: true
    - item:
        name: Basic functions
        haschildren: true
    - item:
        name: Matrix calculus
        haschildren: true
    - item:
        name: More concepts
        haschildren: true
    - item:
        name: Data filtering and other tools
        haschildren: true
    - item:
        name: Matlab coding introduction
        haschildren: true
    - item:
        name: Running a real world example
        haschildren: true
---

<div id="main" role="main">
    {% include sidebar.html %}
    <article class="page" itemscope itemtype="https://schema.org/CreativeWork">
      <meta itemprop="headline" content="{{ page.title }}"/>
      <meta itemprop="description" content="{{ page.header.description }}"/>
      <div class="page__inner-wrap">
        <header>
          <h1 id="page-title" class="page__title" itemprop="headline">{{ page.title }}</h1>
        </header>
        <section class="page__content" itemprop="text">
            <p>{{ site.data.ui-text[site.locale].matlab_desc_1 }}</p>
            <p>{{ site.data.ui-text[site.locale].matlab_desc_2 }}</p>
            <p>{{ site.data.ui-text[site.locale].matlab_desc_3 }}</p>
            <p>{{ site.data.ui-text[site.locale].matlab_desc_4 }}</p>
            <p>{{ site.data.ui-text[site.locale].matlab_desc_5 }}</p>
          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Topics</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>