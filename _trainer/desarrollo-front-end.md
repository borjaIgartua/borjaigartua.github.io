---
layout: default
title: 'Front end Development I Edition'
position: Trainer
company: Telefónica
duration: 195 horas
date: 2017-03-15
header:
  teaser: /assets/images/telefonica-educacion-digital-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/telefonica-educacion-digital-logo.jpg
    text: "Trainer"
  - title: level
    text: Basic
  - title: "Responsibilities"
    text: "IT Trainer of the first two modules."
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
            <p>{{ site.data.ui-text[site.locale].tlf_front_desc_1 }}</p>
            <p>{{ site.data.ui-text[site.locale].tlf_front_desc_2 }}</p>
            <p>{{ site.data.ui-text[site.locale].tlf_front_desc_3 }}<p>
            <ul>
                <li>{{ site.data.ui-text[site.locale].tlf_front_desc_4 }}<br/><span style="font-size: 0.7em;">{{ site.data.ui-text[site.locale].tlf_front_desc_41 }}</span></li>
                <li> {{ site.data.ui-text[site.locale].tlf_front_desc_5 }}<br/><span style="font-size: 0.7em;">{{ site.data.ui-text[site.locale].tlf_front_desc_51 }}</span></li>
                <li> {{ site.data.ui-text[site.locale].tlf_front_desc_6 }}<br/><span style="font-size: 0.7em;">{{ site.data.ui-text[site.locale].tlf_front_desc_61 }}</span></li>
                <li> {{ site.data.ui-text[site.locale].tlf_front_desc_7 }}<br/><span style="font-size: 0.7em;">{{ site.data.ui-text[site.locale].tlf_front_desc_71 }}</span></li>
            </ul>
        <!-- </section>
      </div>
    </article>
</div>-->