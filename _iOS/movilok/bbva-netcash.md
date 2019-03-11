---
layout: default
title: BBVA NetCash
position: Developer
date: 2014-01-01
header:
  teaser: /assets/images/bbva-netcash-logo.jpg
gallery:
  - image_path: /assets/screens/iOS/netcash/uno.png
  - image_path: /assets/screens/iOS/netcash/dos.png
  - image_path: /assets/screens/iOS/netcash/tres.png
  - image_path: /assets/screens/iOS/netcash/cuatro.png
  - image_path: /assets/screens/iOS/netcash/cinco.png
  - image_path: /assets/screens/iOS/netcash/seis.png
  - image_path: /assets/screens/iOS/netcash/siete.png
  - image_path: /assets/screens/iOS/netcash/ocho.png
  - image_path: /assets/screens/iOS/netcash/nueve.png
  - image_path: /assets/screens/iOS/netcash/diez.png
  - image_path: /assets/screens/iOS/netcash/once.png
  - image_path: /assets/screens/iOS/netcash/doce.png
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
            <p>{{ site.data.ui-text[site.locale].netcash_desc_1 }}</p>
            <p>{{ site.data.ui-text[site.locale].netcash_desc_2 }}</p>
            <p>{{ site.data.ui-text[site.locale].netcash_desc_3 }}</p>
            {% include video id="u23JETAhk3g" provider="youtube" %}
        </section>         
         </div>
       </div>       
</div>