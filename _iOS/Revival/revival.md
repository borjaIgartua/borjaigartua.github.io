---
layout: default
title: Revival
position: Developer
date: 2015-03-01
header:
  teaser: /assets/images/revival-logo.png
gallery:
  - image_path: /assets/screens/iOS/revival/uno.png
  - image_path: /assets/screens/iOS/revival/dos.png
  - image_path: /assets/screens/iOS/revival/tres.png
  - image_path: /assets/screens/iOS/revival/cuatro.png
  - image_path: /assets/screens/iOS/revival/cinco.png
  - image_path: /assets/screens/iOS/revival/seis.png
  - image_path: /assets/screens/iOS/revival/siete.png
  - image_path: /assets/screens/iOS/revival/ocho.png
---

<div id="main" role="main">    
      <meta itemprop="headline" content="{{ page.title }}"/>
      <meta itemprop="description" content="{{ page.header.description }}"/>
      <div class="page__inner-wrap" style="margin: 30px;">
      <div class="project-container left">
        <section class="page__content" itemprop="text">
             {% include gallery layout="half" class="remove_margin_top" %}
         </section>
      </div>
      <div class="project-container right">        
        <section class="page__content" itemprop="text">
            <header>
            <h1 id="page-title" class="page__title" itemprop="headline">{{ page.title }}</h1>
            </header>
            <p>{{ site.data.ui-text[site.locale].revival_desc_1 }}</p>
            <p>{{ site.data.ui-text[site.locale].revival_desc_2 }}</p>
            <p>{{ site.data.ui-text[site.locale].revival_desc_3 }}</p>
            <p>{{ site.data.ui-text[site.locale].revival_desc_4 }}</p>
            <p>{{ site.data.ui-text[site.locale].revival_desc_5 }}</p>
            <p>{{ site.data.ui-text[site.locale].revival_desc_6 }}</p>
        </section>         
       </div>
    {% include video id="0BwH85HmD8qFgWkxpMG9EMWJEYlE" provider="google-drive" %}
    {% include video id="C86m6wukKA8" provider="youtube" %}
    {% include video id="V__rVa7vXkY" provider="youtube" %}
</div>